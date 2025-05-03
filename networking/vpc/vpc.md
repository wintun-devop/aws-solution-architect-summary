### AWS VPC Official Docs
```
https://docs.aws.amazon.com/vpc/
```
###
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