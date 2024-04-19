# Serverless Computing
- Aws mangaed services
- we just need to upload the application and rest all AWS will take care of.
- we do not manage/access the servers

![Cloud computing](./images/serverless%20computing/serverless%20computing.png "Cloud computing image notes")

## Lamda(λ)
AWS lambda is a computing service that lets yo run the code without provisioning one manges the serves.

We can run code virtually for any kind of application with zero administration

AWS Lambda manages :
- provisioning of server
- OS need to be used
- Increase the avalability 
- Deploy the code
- patches/ updates

If The traffic Increases then the lambda function is also capable to scale the Infrastrucure whenever needed

You only need to pay only when your code executes/runs

could be zero billing

![Cloud computing](./images/serverless%20computing/Lambda.png "Cloud computing image notes")

### How lambda works
1. first you upload your code to lambda in one or more lambda functions
2. AWS lambda will then execute the code on your behalf
3. After the code is invoked, λ automatically takes care of provisioning and managinging the required servers

![Cloud computing](./images/serverless%20computing/how%20lambda%20works.png "Cloud computing image notes")


| Lambda         | EC2     | 
|--------------|-----------|
| Suports limited languages like nodejs, python, c#, Java, Ruby, Go, powershell | No environment restrictions you can run any code or language      | 
| Write code and push it to lambda      | Create Instance --> Select OS | 
|      |   | 


![Cloud computing](./images/serverless%20computing/Lambda%20vs%20EC2.png "Cloud computing image notes")
### Case Study
![Cloud computing](./images/serverless%20computing/Case%20Study.png "Cloud computing image notes")










1. Create a S3 Bucket
2. DynamoDB Create a table
    - give a table name
3. Create IAM Role
    - Create a role for lambda function to access dynamoDB and S3 bucket
    - select lambda
    - S3 Full access + DynamboDBFullAccess
    - dynambodb-s3
4. Create a lambda function
    - function name
    - Choose language
    - x86_64 is intel architecture, arm64 generally for gaming
    - choose exising IAM role with lambda function 

### Types of Lambda:
- From scratch 
    - You have the code that you will use
- Blueprint
    - the code is already code is there 
- Container image

[How to do a lamda dunction with S3 bucket ](https://docs.google.com/document/d/1Y5aRM5d8g6FJ02e51q1525e9LA9NH02r/edit?usp=sharing&ouid=103157204066713600014&rtpof=true&sd=true)
