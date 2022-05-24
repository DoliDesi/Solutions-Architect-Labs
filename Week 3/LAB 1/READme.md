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
5.  <img src="blob:chrome-untrusted://media-app/b917f22e-bff9-4b62-8c69-38907699fdf5" alt="Screenshot 2022-05-23 10.23.53 PM.png"/>![image](https://user-images.githubusercontent.com/94450478/169908375-9bc0a961-ff54-4637-b731-e947de44d70c.png)

<img src="blob:chrome-untrusted://media-app/deef3523-1426-4c2a-9f18-ab14791b8206" alt="Screenshot 2022-05-24 8.35.13 PM.png"/>![image](https://user-images.githubusercontent.com/94450478/170122943-01da6a15-b827-4cb2-9995-6b2dee0af0c9.png)

6. <img src="blob:chrome-untrusted://media-app/c4b94ee2-c236-4e1e-999f-54018dab756b" alt="Screenshot 2022-05-24 9.01.08 PM.png"/>![image](https://user-images.githubusercontent.com/94450478/170123116-ce014ebb-ad27-48d8-907d-746b743b0c66.png)

<img src="blob:chrome-untrusted://media-app/9a625475-3bb5-49b5-bac1-9612ef41f84b" alt="Screenshot 2022-05-24 9.01.59 PM.png"/>![image](https://user-images.githubusercontent.com/94450478/170123190-3657b328-9722-4b57-8412-6e927606a41a.png)

7. Clean up
<img src="blob:chrome-untrusted://media-app/63fd6192-2b2f-4ffa-a334-6e92c72891aa" alt="Screenshot 2022-05-24 9.15.38 PM.png"/>![image](https://user-images.githubusercontent.com/94450478/170124242-2d791d5c-d1ca-4622-8325-f1b351b1e35b.png)

