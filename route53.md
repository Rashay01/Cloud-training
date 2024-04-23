# Route 53

It is a DNS service

we can use route 53 to register new domains, transfer exsting domains, route traffic to your domain and also does the health checks of your resources.

![Cloud computing](./images/route%2053/route%2053%20-1.png "Cloud computing image notes")


we can also route the traffic to AWS Resources.

name servercies - address of the DNS service

Route 53 creates a record where the traffic would be 

![Cloud computing](./images/route%2053/route%2053%20-2.png "Cloud computing image notes")


## Record

1.  ARecord -> url to IPV4 
    - give the IP addresss of the EC2 
2. AAAA record -> url to IPV6
3. CNAME -> URL to URL
    - fb.com --> CNAME --> facbook.com
4. Alias --> URL --> points to AWS Resource (Endpoint)
    - www.example.com --> record (Route 53) ALis to endpoint --> load bancer

 
![Cloud computing](./images/route%2053/route%2053%20-3.png "Cloud computing image notes")
![Cloud computing](./images/route%2053/route%2053%20-4.png "Cloud computing image notes")

## Creating one

Two things one should take care of :
1. S3 bucketname is same as your domain 
2. S3 bucket and object should be public 


### On AWs:
- Create hosted zone 
- Give name of domain
- give type :
    - public hosted zone - when website is publically hosted 
    - private hosted zone - when website is publically hosted 
- Creates
    - NAME Server (name Server) - addess of route 53 
    - SOA (start of Authority)

[Video on hosting website](https://www.youtube.com/watch?v=gzgwtnqCJz0)