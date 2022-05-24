# Working with EC2 instance using the AWS CLI / Programmable access

Tasks:

1. Using your default vpc, find the public subnet
2. Create a security group
3. Launch an instance with a web server with termination protection enabled
4. Monitor Your EC2 instance; view the types of metrics that are collected for an EC2 instance
5. Modify the security group that your web server is using to allow HTTP access
6. Resize your Amazon EC2 instance to scale


Guide
https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/terminating-instances.html


https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-instance-resize.html


Public subnet using default vpc
<img src="blob:chrome-untrusted://media-app/419a4ea0-5486-4c92-8fea-f5fa127593a6" alt="Screenshot 2022-05-24 10.36.30 PM.png"/>![image](https://user-images.githubusercontent.com/94450478/170144630-dd0fa42b-2aca-4796-99d5-f8f479d91336.png)

Security group
<img src="blob:chrome-untrusted://media-app/1e42026e-cc3c-46be-a5de-795c0ebfa66a" alt="Screenshot 2022-05-24 10.46.54 PM.png"/>![image](https://user-images.githubusercontent.com/94450478/170144704-477b6cc5-5fe5-4f41-841f-343daafa4710.png)

Launch an Instance

  `
