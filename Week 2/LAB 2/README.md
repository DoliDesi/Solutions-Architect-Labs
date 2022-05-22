Task: Create a nondefault VPC using AWS CLI

1. Open your CLI and run a configuration setting
2. Lauch a VPC 
3. Create two subnets (a public and a private subnet)
4. Make your subnet public by creating and attaching an internet gateway
5. Create a security group and add a SSH access from anywhere
6. Lauch an instance into your subnet 
7. Clean Up

https://docs.aws.amazon.com/vpc/latest/userguide/vpc-subnets-commands-example.html

https://docs.aws.amazon.com/vpc/latest/userguide/vpc-subnets-commands-example-ipv6.html

https://docs.aws.amazon.com/vpc/indx.html


To run a configuration setting, I used the code,
aws configure


3. To create subnets(Private and Public)

![image](https://user-images.githubusercontent.com/94450478/169668624-0266dd20-d4b9-4263-86e4-298b40d58759.png)

![image](https://user-images.githubusercontent.com/94450478/169668651-e127da3f-58d1-4de4-b105-8dbf064b940d.png)

![image](https://user-images.githubusercontent.com/94450478/169668659-04a6cacb-744b-409c-a0ca-fb9387e869aa.png)

![image](https://user-images.githubusercontent.com/94450478/169668674-d899b368-e2b1-4f07-ac5a-44b160bf3fe1.png)
