# Task 2: Create S3 bucket with bucket policies and life cycle management

1. Launch AWS Console
2. Create a S3 bucket with enforced ownership
3. Create a single lifecycle policy
4. Create a single bucket policy
5. Delete all policies
6. Delete S3 bucket



For guide, kindly visit

https://docs.aws.amazon.com/cli/latest/reference/s3api/create-bucket.html

https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html

https://docs.aws.amazon.com/cli/latest/userguide/cli-services-s3-commands.html



1. Creating a s3 bucket with enforced ownership

![image](https://user-images.githubusercontent.com/94450478/169142971-5351c63f-d4a2-4655-8926-c7101bef1d1e.png)

2. Create a single lifecycle policy: Lifecycle policies allow you to automatically review objects within your S3 Buckets and have them moved to Glacier or have the objects deleted from S3. You may want to do this for security, legislative compliance, internal policy compliance, or general housekeeping. Glacier is often used as a ‘cold storage’ solution for information that needs to be retained but rarely accessed and offers a significantly cheaper storage service than S3.
 
 ![image](https://user-images.githubusercontent.com/94450478/169142656-0cc1ad93-70cf-45d1-ad47-f5a4139347f8.png)
 
 3. Create a single bucket policy: An S3 bucket policy is an object that allows you to manage access to specific Amazon S3 storage resources. You can specify permissions for each resource to allow or deny actions requested by a principal (a user or role).
 ![image](https://user-images.githubusercontent.com/94450478/169151300-d0e1a85f-7253-4fd8-b7d4-975695703a8a.png)
 
 ![image](https://user-images.githubusercontent.com/94450478/169151780-1aeca3e3-758e-40b3-b406-a6b572421cc1.png)
 
 ![image](https://user-images.githubusercontent.com/94450478/169152129-f3a8e022-e70e-46b4-9f26-0e77c3935c50.png)




 
