### EC2 Official Documentaion
```
https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html
```
### EC2 Instance Metadata
```
http://instance-ip/latest/meta-data/
```
```
http://instance-ip/latest/meta-data/instance-id
```
### On-Demand Capacity Reservations
```
https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-capacity-reservations.html
```
EC2
 - Instances
   - On-demand
   - Reserved
     - Stand
     - Convertible
     - Scheduled
   - Spot Instance
 - Types (https://docs.aws.amazon.com/ec2/latest/instancetypes/instance-types.html)
   - General Purpose (T, M series): Balanced CPU, memory, and network, suitable for web applications and development environments.
   - Compute Optimized (C series): High-performance processors, ideal for batch processing and gaming.
   - Memory Optimized (R, X, Z series): Designed for applications requiring high RAM, such as large databases and in-memory caching.
   - Storage Optimized (I, D series): Optimized for high-speed storage operations, great for NoSQL databases and big data analytics.
   - Accelerated Computing (P, G, F series): Designed for specialized workloads like machine learning, gaming, and high-performance computing.
 - ec2 storage option
   - ebs
   - instance store
   - s3 for object  store
   - efs for  linux instance
   - fsx for window instance
   - Amazon File Cache (https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AmazonEFC.html)
 - ec2-auto scaling(hz scaling)
   - Scaling Policy
   - 
