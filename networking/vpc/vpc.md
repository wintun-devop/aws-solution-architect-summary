### AWS VPC Official Docs
```
https://docs.aws.amazon.com/vpc/
```
### VPC FAQ
```
https://aws.amazon.com/vpc/faqs/?saa=sec&sec=prep
```
- VPC
  - Default VPC
  - Custom VPC
     - Public Subnet
     - Private Subnet
     - Route Table
        - Main Route Table
        - Non Main Route Table
  - Security 
     - SG
     - Network ACL
     - Network Firewall
  - Monitoring
     - Cloud Watch
        - Monitoring
        - Logging
     - VPC Flow Logs

  - Gatewway
    - Internet Gateway -> inbound/outbound public traffic for ipv4 and ipv6
    - Egress Only Inernet Gateway -> outbound private traffic for ipv6
    - Carrier Gateway -> aws partnered telecom network
    - NAT Gateway -> outbound private traffic for ipv4
    - Virtual Private Gateway -> endpoint for aws account VPN connection
    - Customer Gateway -> enpoint for on-premise VPN connection
    - GLBP(Gateway Loadbalancer) -> load balancer for third-party virtual application
    - Direct Connect Gateway -> endpoint connection to a fiber optic connection at co-location data center.
    - Backup Gateway -> endpoint connection for aws managed backups
    - IOT Device Gateway -> endpoint connection to send data to iot devices
    - Transit Gateway  -> Hub and spoke model for  pvc peering and vpn connection
    - API Gateway -> endpoint to create api services
    - AWS Storage Gateway -> Syncing,caching or extend local storage to cloud storage
  - VPC Endpoints
    - Gateway Endpoints
    - Interface Endpoints
    - Gateway Loadbalancer Endpoints
  - Private Links
  

### AWS Private Links
```
https://docs.aws.amazon.com/vpc/latest/privatelink/concepts.html
```

### VPC Reachability Analyzer vs VPC Network Access Analyzer
- VPC Reachability Analyzer is a configuration analysis tool that allows you to test connectivity between a source and destination 
   resource in your VPCs. If the destination is reachable, it provides hop-by-hop details of the network path. If it's not reachable, it identifies the blocking component, such as security groups, network ACLs, or route tables.
- VPC Network Access Analyzer helps you identify unintended network access to your AWS resources.You can define your network access 
   requirements and use the tool to detect potential paths that do not meet your specified rules
- Key difference is that Reachability Analyzer focuses on troubleshooting specific connectivity issues, while Network Access Analyzer is more 
  about governing and validating network access across your environment.