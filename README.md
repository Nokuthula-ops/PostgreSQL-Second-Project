# PostgreSQL-Second-Project
The task is to use DBeaver to see and manage my AWS PosgreSQL database, Perfom CRUD operation, and test Persistance.

*This task was not difficult even though it is was my first time using DBeaver*

 -To connect DBeaver with my AWS PostgreSQL database, I used Session Management to use EC2 as bridge to connect to the database and i succeeded (USING POWERSHELL COMMANDS).
 
 -Then on DBeaver, I connected my database which is 'PostgreSQL database', and was able to view the information I have stored previously from my first project.

### AWS RDS PostgreSQL
![AWS RDS](screenshots/aws-rds-Screenshot(22).png)

 -I then performed a CRUD operation by adding 2 customers, updated the information, and deleteting one of them.
 While doing CRUD, i've been checking after every step. The screenshot attached is the results of of the DELETE operation.

### Customer Records in DBeaver
![Customer Records](screenshots/dbeaver-Screenshot(25).png)
 
 -Lastly, testing persistance. I disconnected DBeaver from the database and reconnected again, checked whether customer information is there and they were still there. I also closed DBeaver entirely and restarted the laptop. I started DBeaver again, connected it to the database, and checked for customer, and GOOD NEWS! persistances passed!.
 
 ### Persistence Test
![Persistence Test](screenshots/persistence-Screenshot(27).png)























