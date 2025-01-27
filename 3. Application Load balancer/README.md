**Application Load Balancer.**

Deployed two EC2 instances on AWS and configured an Application Load Balancer (ALB) to distribute traffic between them.
Mapped the EC2 instances to the ALB, ensuring high availability and load balancing for the application.

1.	Launch ec2 instances
![image](https://github.com/user-attachments/assets/5b67c2ce-ce91-438a-970b-d41a4dc534d6)
2.	We have given the user data script as the below which will install the apache server and create the web page that shows the host IPs.
![image](https://github.com/user-attachments/assets/913d0895-7369-456b-91c6-c4b1c4c80f9d)
![image](https://github.com/user-attachments/assets/cda1db17-a68c-42b6-8bcf-e22398189e6d)
![image](https://github.com/user-attachments/assets/b6ba707e-9a7c-45e4-98d1-3bbd074d9029)
3.	Create the Application Load balancer.
![image](https://github.com/user-attachments/assets/4643b125-4894-492b-a566-a7e3cd605f21)
![image](https://github.com/user-attachments/assets/28af1a21-d155-4883-8c64-fc26cb29619f)
4.	Create the Security group with http allowed from anywhere in inbound rules to make make the webpage visible when it shown via the ALB.
![image](https://github.com/user-attachments/assets/dfa1c087-3321-4449-815b-a0b60260f7b6)
5.	Create the target group
![image](https://github.com/user-attachments/assets/5afb10cd-ec2d-459c-a994-530b5f7dcee5)
![image](https://github.com/user-attachments/assets/d847b331-e090-4eab-9bee-8cc1ba221388)
![image](https://github.com/user-attachments/assets/95e66f12-f336-43c5-b1df-fa72ea5ecdc6)
![image](https://github.com/user-attachments/assets/aa3f2d9c-8f74-4369-ad72-054cee786287)
6.	By means of the DNS name we can access the webpages deployed on both the ec2 instances through the Application Load Balancer. 
![image](https://github.com/user-attachments/assets/dcd6f008-7eb1-4e07-8e30-31afae745486)
![image](https://github.com/user-attachments/assets/aae5b552-2bb2-417c-9401-8085b76b6eb1)
