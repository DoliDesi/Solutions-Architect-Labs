Working with IAM management console

Tasks

1. Login to your root account
2. Create an IAM group with S3 read only acess (S3 support).
3. Create an IAM group with EC2 read only acess (EC2 support)
4. Create an IAM group with EC2 full access (EC2 admin)
5. Create 3 IAM users and add to the each group above as descibe below:


user      group          permissions
user1     EC2 support     Read-Only access to Amazon EC2
user2     S3 support      Read-Only access to Amazon S3
user3     EC2 admin       Full access to Amazon EC2 instances

6. Test your design

7. Perform clean up operations


Replicate the process above for  Schulltech organization descrcibed below:


user               group                       permissions
adminstaff         EC2 support          Read-Only access to Amazon EC2
Techstaff          S3 support           Full access to S3
ITexpert           EC2/SDK admin        full access to EC2 and SDK
financialmanager     billingcontrol      Billing Full Access  
financeuser          billinguser          Billing view access



https://docs.aws.amazon.com/IAM/latest/UserGuide/tutorial_users-self-manage-mfa-and-creds.html



2. IAM Group with S3 read only access
<img src="blob:chrome-untrusted://media-app/4db84935-9f8a-46e1-9e96-a5f0b90322d3" alt="Screenshot 2022-05-23 5.41.11 PM.png"/>![image](https://user-images.githubusercontent.com/94450478/169868128-df51db36-deab-4ac8-85bb-97b94377acf8.png)

3. IAM Group with EC2 read only access
<img src="blob:chrome-untrusted://media-app/1d71398d-8107-45d2-9b21-b18633eceea7" alt="Screenshot 2022-05-23 5.49.16 PM.png"/>![image](https://user-images.githubusercontent.com/94450478/169869434-47bd0cf2-52a8-4ac8-a894-e3139dfe274f.png)

4. IAM Group with EC2 full access

<img src="blob:chrome-untrusted://media-app/d9a87f48-3170-46c6-aea5-c318a0d6c48a" alt="Screenshot 2022-05-23 9.57.53 PM.png"/>![image](https://user-images.githubusercontent.com/94450478/169905104-1abc2794-ab1e-4d90-b960-2ca63ccef6a7.png)
5. <img src="blob:chrome-untrusted://media-app/afe3d24b-d2b9-4c62-87c0-256bf76499d8" alt="Screenshot 2022-05-23 10.15.43 PM.png"/>![image](https://user-images.githubusercontent.com/94450478/169907398-e42f2b98-32bb-477f-b939-9252b0c50d81.png)

<img src="blob:chrome-untrusted://media-app/b917f22e-bff9-4b62-8c69-38907699fdf5" alt="Screenshot 2022-05-23 10.23.53 PM.png"/>![image](https://user-images.githubusercontent.com/94450478/169908375-9bc0a961-ff54-4637-b731-e947de44d70c.png)
