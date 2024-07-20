# AWS
AWS DEMOS

* AMAZONE PROVIDED DNS SERVER

  
* DHCP OPTION SET

  DOMAIN-NAME = DIPENDRASAINI.INTERNAL

  name-server = IP of DNS Server 
  

Note: Route 53 Private Hosted Zone should be equal to DOMAIN-NAME In DHCP OPtion set

<img width="1051" alt="Screenshot 2024-07-20 at 1 32 26 PM" src="https://github.com/user-attachments/assets/ebb60847-00f1-4a79-99a0-459cc94298c2">


IMP:

When u create VPC from Scrate Make Sure do entry in main route table for 0.0.0.0/0 to igw 

* Enable Dns Hostname -> it is used to assign Public DNS to EC2 Machine

* Enable DNS Support

Both Configuration should be enable to work this Demo

* Create EC2 Key while lanuching new ec2

Your DHCP Option set will take 

domain-name: dipendrasaini.com

domain-name-servers: AmazonProvidedDNS


Route53 Internal Domain should be same 

 dipendrasaini.com

 
