## Amazon VPC
1. vpc provides the private network within the public network which provides the security.
2. we can add security rules as per our requirement using security group and NACL feature of vpc.

### Subnet
1. We can devide the network in multiple subnet.
2. Suppose we have multiple departments and we want devide them and want to keep them isolated, we can create the subnet
   from the CIDR ipaddress range and devide them.
3. And inside subnets we can keep this instances, while creting instance you have to attach this created subnet.

### Difference between security group and NACL
Security group:
1. Security groups are used at instnace level to define inbound and outbond traffic.
2. It is one kind of firewall

NACL:
1. NACL stands for network access control list.
2. NACL are used at subnet level to define the inbound and outbond traffic.

### Internet gateway
1. Intenet gateway are used to give internet access to the VPC.
2. create intenet gateway and simply attached to vpc.

### Route table:
1. To define the internet traffice route tables are used.

