# EX-5 CLOUD DATA STORAGE SERVER
## CLOUD DATA STORAGE SERVER
### REG NO : 212224100012
### NAME : DHARSHINI S

## AIM

To create and configure an Amazon RDS MySQL DB instance with Multi-AZ deployment, connect it to a web application using a security group and DB subnet group, and perform CRUD (Create, Read, Update, Delete) operations on the database through the application.

## ALGORITHM

1. Log in to the AWS Management Console.
2. Create a DB Security Group allowing MySQL (3306) access from the Web Security Group.
3. Create a DB Subnet Group with subnets in two Availability Zones.
4. Launch an Amazon RDS MySQL Multi-AZ DB instance.
5. Configure the DB instance with the required username, password, and database name. Wait until the database status becomes Available and copy the endpoint.
6. Open the provided web application using the Web Server IP.
7. Enter the RDS endpoint, database name, username, and password.
8. Connect the application to the database.
9. Test the application by adding, editing, viewing, and deleting records.

## OUTPUT

<img width="1240" height="1087" alt="Screenshot 2026-08-19 135252" src="https://github.com/user-attachments/assets/8b5c4506-3caa-42ab-9de1-aefb876ac436" />

<img width="1240" height="1073" alt="Screenshot 2026-08-19 140358" src="https://github.com/user-attachments/assets/ea36b098-6d5c-4eff-8b64-0bf4ae7b011f" />

<img width="1242" height="1087" alt="Screenshot 2026-08-19 141239" src="https://github.com/user-attachments/assets/898f2e84-da16-4c39-bb55-2c5debe53b81" />

<img width="1150" height="1132" alt="Screenshot 2026-08-19 142216" src="https://github.com/user-attachments/assets/877fb296-f8e5-423e-a419-492e90fe4876" />

<img width="1152" height="1032" alt="Screenshot 2026-08-19 142245" src="https://github.com/user-attachments/assets/f5cff9de-26bb-43f1-8c16-bfc76f8d4f03" />

<img width="1163" height="1132" alt="Screenshot 2026-08-19 142322" src="https://github.com/user-attachments/assets/28551ca1-cf96-46c9-9957-f24dc0aedac9" />

<img width="1920" height="1200" alt="Screenshot 2026-08-19 142521" src="https://github.com/user-attachments/assets/22fee86e-731b-41e7-bf76-5c6dfa16c080" />







## RESULT

The Amazon RDS MySQL Multi-AZ DB instance was successfully created and connected to the web application, and CRUD operations were performed successfully on the database.

