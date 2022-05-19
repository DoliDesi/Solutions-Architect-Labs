This task will get you acquainted on how to deploy VPC 


Task 1: Deploy VPC using Management console
1. Launch the AWS Management Console
2. Launch a VPC with one public and one private subnets.
3. Create two route table and associate  each one to each subnets
4. Attach an internet gateway to the VPC and a NAT gateway to the private subnet.
5. Lauch a Linux instance into this VPC and attach the subnet
6. Test the network connectivity
7. Perform clean up actions







For guide, you are check the links below:

https://docs.aws.amazon.com/cli/latest/reference/ec2/

https://docs.aws.amazon.com/cli/latest/reference/ec2/describe-vpcs.html

Using the Management console
1. Launching the vpc 
2. I searched 'VPC' on the management console and I proceeded to create. It gave me the below response
![image](https://user-images.githubusercontent.com/94450478/169289573-0f35f1a6-657d-45f6-8b17-26154f60ea60.png)

![image](https://user-images.githubusercontent.com/94450478/169290066-05dd430c-0d24-46cc-83d4-9b78f2cec2b6.png)

In creating a subnet, on the left hand side of the console, click on it. Then, in the VPC ID, choose the vpc you recently created. Showing below
![image](https://user-images.githubusercontent.com/94450478/169291431-12e2f202-6e72-4f8b-8e52-9c9f05c2f52c.png)
![image](https://user-images.githubusercontent.com/94450478/169312447-7f051fc6-f06a-4449-895b-15f6f521531e.png)
![image](https://user-images.githubusercontent.com/94450478/169312696-9bed7f6c-694c-4ae9-9844-d151aea62e7a.png)
![image](https://user-images.githubusercontent.com/94450478/169312925-c39ee4ed-7b29-4d80-a787-58e2581bd8f1.png)
![image](https://user-images.githubusercontent.com/94450478/169313101-ee9bde4b-faaa-4283-8234-b1e7b38ce4e6.png)

5. Launch a Linux instance into this VPC and attach the subnet





