# Automate the snapshot creation

Every 2 hours my AWS will go and create the snapshot

# Event Bridge 
Event will create the snapshts for me


Cron-based schedule:
- create a cron job to perform the activity by cron expression
- repetitive activity 

Rate based schedule:
- After certain duration the job will e executed 


Cron job expression:

1. write cron job for 31st dec 11:59 pm

`59 23 31 12 *`

2. Write cron job for every 2 mins
`*/2 * * * *`

3. Write cron job which should execute weekly on friday at 7 pm 

`00 19 * * 5`

4. write a cron job which should execute if in any month of the year wednesday is coming on 25th date 

`* * 25 * 3`


[Create snapshot](https://drive.google.com/drive/folders/1NGub2fahqUh1rykkkeHKxqgInoinPiVh?usp=sharing)

