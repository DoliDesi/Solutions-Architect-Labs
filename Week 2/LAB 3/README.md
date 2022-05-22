Task :  Create a dual Stack VPC and subnets using AWS CLI

Step:
1. Launch a non-default VPC
2. Create two subnets 
3. Create an internet gateway to one of the subnets with route table 
4. Configure an egress-only private subnet
5. Modify the IPv6 addressing behavior of the subnets
6. Lauch an instance into your public subnet
7. Launch an instance into your private subnet
8. Perform clean up operations. 


https://docs.aws.amazon.com/vpc/latest/userguide/vpc-subnets-commands-example.html

https://docs.aws.amazon.com/vpc/latest/userguide/vpc-subnets-commands-example-ipv6.html

https://docs.aws.amazon.com/vpc/index.html


Launch a non-default vpc using the CLI
I used the below code
aws ec2 create-vpc --cidr-block 10.0.0.0/16
<img src="blob:chrome-untrusted://media-app/b74ea363-558b-485e-bc3d-3849f5f6689a" alt="Screenshot 2022-05-22 5.38.03 PM.png"/>![image](https://user-images.githubusercontent.com/94450478/169706179-dfc1434b-26ef-4886-b38c-6f5747ac73b2.png)
Create two subnets
a. Public
<img src="blob:chrome-untrusted://media-app/4a75755f-65ff-4c7f-80a0-16ca18591d05" alt="Screenshot 2022-05-22 7.52.38 PM.png"/>![image](https://user-images.githubusercontent.com/94450478/169711267-7cabfa0a-ee61-4bf9-86c4-fdf7b751df20.png)
b. Private
<img src="blob:chrome-untrusted://media-app/d88c6406-09f0-4757-8516-b906463c9fda" alt="Screenshot 2022-05-22 7.52.38 PM.png"/>![image](https://user-images.githubusercontent.com/94450478/169713686-e7e6594d-942a-48a8-9edb-f2fcdc9456df.png)
Internet Gateway
<img src="blob:chrome-untrusted://media-app/a2641907-ec7c-4310-ab26-4e77618243d7" alt="Screenshot 2022-05-22 9.08.48 PM.png"/>![image](https://user-images.githubusercontent.com/94450478/169713898-298dfcbe-d3e0-425f-a75c-44f0ffdd2d56.png)
Attach internet Gateway to VPC

aws ec2 attach-internet-gateway \
--vpc-id "vpc-0f368730cf83e30f6" \
--internet-gateway-id "igw-0f7a5ae8682ac0eb8" \
--region us-east-2 \

We create route table

<img src="blob:chrome-untrusted://media-app/6e7d2da4-2c9e-4f97-a8b7-015df39f7391" alt="Screenshot 2022-05-22 9.31.56 PM.png"/>![image](https://user-images.githubusercontent.com/94450478/169714735-06a2107a-b803-4648-b755-8ccd87df01c0.png)

<img src="blob:chrome-untrusted://media-app/2481eb26-c642-4caa-b7e6-2f90b540de6d" alt="Screenshot 2022-05-22 9.58.39 PM.png"/>![image](https://user-images.githubusercontent.com/94450478/169715550-8872f779-4279-47ba-9112-9af980135c1b.png)
