To Do
AWS Exercise
Task 1
Login to AWS web console

Create a test EC2 instance with type t2.micro based on Ubuntu. Use public IP

![](https://github.com/Visemir/homework13/blob/main/createc2-1.jpg)
![](https://github.com/Visemir/homework13/blob/main/createc2-2.jpg)

Connect to EC2 via SSH. Check that it works

![](https://github.com/Visemir/homework13/blob/main/ssh.jpg)

Destroy the test EC2 instance

Task 2
Create an S3 bucket. Give it any unique name

![](https://github.com/Visemir/homework13/blob/main/creates3.jpg)

Upload any test file to S3. Download this file to your PC

![](https://github.com/Visemir/homework13/blob/main/upload%20file.jpg)
![](https://github.com/Visemir/homework13/blob/main/download%20file.jpg)

Create your own IAM policy which allows access to only this specific S3 bucket

![](https://github.com/Visemir/homework13/blob/main/policyjson.jpg)

Create your own test user and provide them only this policy

![](https://github.com/Visemir/homework13/blob/main/useradd.jpg)
![](https://github.com/Visemir/homework13/blob/main/attachpolicy.jpg)


Login to AWS console with the created user and check that this user has access only to this S3 bucket

![](https://github.com/Visemir/homework13/blob/main/testuser-bucket.jpg)

Remove the created user, created policy, and S3 bucket
