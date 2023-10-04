# VCN
Virtual Cloud network  10.0.0.0/16
Divided in subnets 10.0.1.0/24 10.0.2.0/2 etc

# Internet Gateway
IN/OUT traffic Router 

# NAT Gateway
Only Outbound network
Public IP address for internet access to private networks

# Service Gateway
Let resources in VCN access public OCI services like  Object storage

# Dynamic Routing Gateway
Enable routing between onpremise and cloud (VPN or Fast Connect)

# Local Peering
Connect two different VCN within same REGION

# Remote Peering
Connect one VCN with another VCN outside of the region

# Security  List
Rules that allow or deny incoming traffic based on source, destination port range, protocol type...

# Network Security
Firewall rules applied at network interface

# Load balancer comparison
Load balancer -  web application firewall.
Network load balancer - low-latency network integrated load balancer 