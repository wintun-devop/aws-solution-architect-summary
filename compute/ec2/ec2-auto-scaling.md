### EC2 Auto Scaling
```
https://docs.aws.amazon.com/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html
```

### AWS Auto Scaling
```
https://aws.amazon.com/autoscaling/
```

### Scale In vs Scale Out
- Scale-Out Process (Adding Instances)
  - Scale-out occurs when additional EC2 instances are launched to handle increased load:
    - CloudWatch Alarm Trigger – If CPU utilization or other metrics exceed a predefined threshold, a CloudWatch alarm activates.
    - Scaling Policy Executes – The Auto Scaling group receives the signal and follows the configured scaling policy.
    - Instance Launching – New EC2 instances are provisioned according to the specified settings.
    - Elastic Load Balancer (ELB) Integration – If ELB is used, new instances are automatically registered to distribute incoming traffic.
    - Application Handles Increased Load – The infrastructure adapts to meet rising demand, improving performance.

- Scale-In Process (Removing Instances)
  - Scale-in happens when demand decreases, and fewer instances are required:
    - CloudWatch Alarm Trigger – If CPU utilization or other metrics fall below the set threshold, a CloudWatch alarm triggers a scale-in action.
    - Scaling Policy Executes – The Auto Scaling group starts terminating instances based on predefined rules.
    - Instance Termination – The system removes EC2 instances safely, ensuring that running workloads are unaffected.
    - Load Balancer Adjusts – If ELB is in use, it deregisters terminating instances to maintain smooth traffic flow.
    - Cost Optimization – The infrastructure scales down to reduce unnecessary expenses while maintaining required performance levels.