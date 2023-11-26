## What is cloud computing
- cloud computing is the delivery of computing services including servers,storage,databases,networking,software etc.
## benfits 
- faster time to market
- scalability and flexibility
- cost savings
- better collaboration
- advanced security
- data loss prevention
## disadvantage 
- risk of vendor lock-in
- less control over underlying cloud insfra
- concerns about security risks like data privacy and online threats
- integration complexity with exisiting systems
- unforseen costs and unexpected expenses

![Screenshot from 2023-11-26 11-13-28](https://github.com/KRIISHSHARMA/AWS/assets/86760658/5cb528d2-0305-4def-af70-743624f9f1e5)

![Screenshot from 2023-11-26 11-14-43](https://github.com/KRIISHSHARMA/AWS/assets/86760658/72395079-6a3a-4a2d-a61a-e9a23fb50506)

- example of private implementation softwares : openstack , opennebula 


## Hyperscalars : A hyperscaler is a type of large-scale data center that offers massive computing resources, typically in the form of an elastic cloud platform. Organizations use them to deploy and manage large-scale applications and services.

![Screenshot from 2023-11-26 11-17-36](https://github.com/KRIISHSHARMA/AWS/assets/86760658/a37cc108-bf86-481f-80cd-ea7ec4b1e5a1)

![Screenshot from 2023-11-26 11-19-52](https://github.com/KRIISHSHARMA/AWS/assets/86760658/7f6c1e83-29b4-43dc-9cf5-2e20cdc321fa)

## Compute services 
- EC2  
- ECS/EKS : containerized services `
  - Fargate
- lambda : serverless 

## Storage Services
- S3
- EBS : Amazon Elastic Block Storage is a storage service wherein each block of storage acts like a separate hard drive (volume) . 
- EFS : dont need to assign any volume , can do on its own , seamless storage , database on EC2 instances 
- Archival service - Glacier : Amazon Glacier is extremely low cost, secure, and durable storage service for data archiving and
backup. That data stored which are not needed instantly , eg old data . Takes time min 4 hours or 1 day to retrieve request ( S3 instantly returns request)

## Network Services
- VPC : own insolated environment in a public cloud
- Domain Name Service - Route 53

![Screenshot from 2023-11-26 13-40-57](https://github.com/KRIISHSHARMA/AWS/assets/86760658/3dcafdd0-84f9-4ecd-9843-e6ea71061a3f)
![Screenshot from 2023-11-26 13-46-08](https://github.com/KRIISHSHARMA/AWS/assets/86760658/2ba98aae-9871-40a1-89a9-3bbcaa961fdc)
![Screenshot from 2023-11-26 13-47-33](https://github.com/KRIISHSHARMA/AWS/assets/86760658/a7b8c06a-c163-4b80-a052-d433928260ff)
![Screenshot from 2023-11-26 13-57-52](https://github.com/KRIISHSHARMA/AWS/assets/86760658/86722cee-9cc8-47be-9e62-a4f6fb8dc842)
![Screenshot from 2023-11-26 13-59-20](https://github.com/KRIISHSHARMA/AWS/assets/86760658/2edee858-bceb-49da-8c19-d87403bf0582)

- **Apache web server works on layer 7 , using single apache server one can deploy multiple applications on different ports based on paths (URLbased) (virtual hosts) . virtual hosting can only work on layer 7**

## Application based LB 
- key pair : kind of like a password (public key is username; private key is password)
  - PPK (PuTTY Private Key) and PEM (Privacy Enhanced Mail) are two file formats that are commonly used for SSH and SSL/TLS connections. While PPK files are primarily used with PuTTY on Windows, PEM files are more widely supported and can be used with various tools and platforms

- security groups : A security group controls the traffic that is allowed to reach and leave the resources that it is associated with. For example, after you associate a security group with an EC2 instance, it controls the inbound and outbound traffic for the instance. When you create a VPC, it comes with a default security group. (acts as a firewall)

![Screenshot from 2023-11-26 15-39-41](https://github.com/KRIISHSHARMA/AWS/assets/86760658/90eeb7f4-8428-4876-8a3e-288feb952aa1)
![Screenshot from 2023-11-26 15-39-41](https://github.com/KRIISHSHARMA/AWS/assets/86760658/73bc04f3-081a-4451-adf4-f89c488b8a67)
![Screenshot from 2023-11-26 15-40-34](https://github.com/KRIISHSHARMA/AWS/assets/86760658/e96e05df-b33c-400a-8264-946d9a878644)
![Screenshot from 2023-11-26 15-40-51](https://github.com/KRIISHSHARMA/AWS/assets/86760658/bb9edf0e-42cb-49b8-abe9-34f0c2d35e87)

### Creating a target group 
- Your load balancer routes requests to the targets in a target group and performs health checks on the targets.
- LB routes traffic to target group then traffic group routes traffic to the back end ec2 instances or IP addresses etc

![Screenshot from 2023-11-26 15-49-16](https://github.com/KRIISHSHARMA/AWS/assets/86760658/eff46d2f-b504-44e9-9269-7a2b877930d6)
![Screenshot from 2023-11-26 15-49-16](https://github.com/KRIISHSHARMA/AWS/assets/86760658/5500b66f-9467-4353-9599-5186bcbb156a)
![Screenshot from 2023-11-26 15-50-48](https://github.com/KRIISHSHARMA/AWS/assets/86760658/848472d8-4fda-4580-9563-d10d1e17202c)

![Screenshot from 2023-11-26 16-19-25](https://github.com/KRIISHSHARMA/AWS/assets/86760658/bb5bbe47-681f-4383-8825-a3974aef26a4)
![Screenshot from 2023-11-26 16-24-54](https://github.com/KRIISHSHARMA/AWS/assets/86760658/f9a7faaf-0855-4cc3-afa5-fc65e9793b22)






























