#Easy (1 hour 30 mins)
1) launch ubuntu ec2
2) launch a hello world website in the machine
3) Attach a elastic ip and stop and restart the machine to check if ip address is changing
4) create a autoscaling with desired capacity :1 , min capacity : 1 and max capacity: 2
Terminate all the machines to see if the new machines are taking its place.
5) delete autoscaling group, ami,snapshots , machines
6) create two machine with different content .
example: in machine 1 : hello world
                 In machine2 : hi amdocs
Distribute the load via application load balancer .
Delete the load balancers and machinez
7) 
create two machine with different content .
example: in machine 1 : hello world
                 In machine2 : hi amdocs
Distribute the load via network load balancer .
Delete the load balancers and machine
# Intermediate questions (2 hours)
1) launch an ubuntu machine and enable termination protection on that machine.
2)  launch the website in ubuntu machine and create a snapshot. Copy the snapshot in other region. And launch the replica of the machine in other region from the snapshot
3) launch a machine …enable autoscaling . With autoscaling also enable load balancing. 