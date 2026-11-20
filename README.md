# EX-5 CLOUD DATA STORAGE SERVER
# REG NO : 212225230255
# NAME : S.Sathya Priyan

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
<img width="1917" height="961" alt="Screenshot 2026-11-20 153707" src="https://github.com/user-attachments/assets/e0def3ef-0aba-4066-907a-2eb956bc1daf" />
<img width="1917" height="901" alt="Screenshot 2026-11-20 154106" src="https://github.com/user-attachments/assets/0daf8348-482c-468b-b98f-40b9dd967045" />
<img width="1917" height="837" alt="Screenshot 2026-11-20 154120" src="https://github.com/user-attachments/assets/5efd92cd-2b91-405f-a192-7fe93cbd31d9" />
<img width="1917" height="892" alt="Screenshot 2026-11-20 154527" src="https://github.com/user-attachments/assets/eca7acbe-8ceb-4b22-8faf-60828a45b4cb" />
<img width="1917" height="710" alt="Screenshot 2026-11-20 154539" src="https://github.com/user-attachments/assets/94169913-4417-4c4b-8fe2-f325ac059927" />
<img width="1916" height="796" alt="Screenshot 2026-11-20 160028" src="https://github.com/user-attachments/assets/a9cda068-3048-4366-96b4-0aa04b2f9e76" />
<img width="1917" height="766" alt="Screenshot 2026-11-20 160929" src="https://github.com/user-attachments/assets/6b85a7f3-8fc1-4184-b1ec-7ad62fe9e4a0" />
<img width="1917" height="652" alt="Screenshot 2026-11-20 161133" src="https://github.com/user-attachments/assets/871fbc82-5247-4c0a-b1eb-4b20b3373b29" />
<img width="1772" height="602" alt="Screenshot 2026-11-20 161153" src="https://github.com/user-attachments/assets/021eff13-6967-4133-be09-a949fe6ed838" />
<img width="1917" height="897" alt="Screenshot 2026-11-20 161312" src="https://github.com/user-attachments/assets/2256b084-3467-486c-95fe-934cfefc5391" />














## RESULT

The Amazon RDS MySQL Multi-AZ DB instance was successfully created and connected to the web application, and CRUD operations were performed successfully on the database.
