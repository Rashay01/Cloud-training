# Connecting EC2 to S3

you need create iam role which will give permission to ec2 to access s3 on your behalf

then you go to ec2 -> select machine -> actions -> modify iam roles -> attach the role

go inside your machine and run: 
1. sudo su
2. sudo apt update
3. apt install awscli -y
4. aws s3 ls 

(you will see the list of buckets)

![Cloud computing](./images/Connecting%20EC2%20to%20S3/EC2%20message.png "Cloud computing image notes")