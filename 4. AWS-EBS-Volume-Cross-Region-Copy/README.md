# AWS EBS Volume Cross-Region Copy (ap-south-1 to eu-north-1)

This repository demonstrates the process of copying an AWS Elastic Block Store (EBS) volume from one region to another. Specifically, this project involves the following tasks:
- Creating an EBS volume in the ap-south-1 (Mumbai) region.
- Taking a snapshot of the EBS volume.
- Copying the snapshot to the eu-north-1 (Stockholm) region.
- Creating a new EBS volume from the copied snapshot in the eu-north-1 region.

1.	Create the EBS volume.
![image](https://github.com/user-attachments/assets/488c15b5-f9fb-4c59-a19f-f950d052c961)
2.	Snapshot created from the existing EBS volume.
![image](https://github.com/user-attachments/assets/bf8e3e6f-65a0-412c-9311-5069fda73494)
3. Copy the snapshot in eu-north-1 from the ap-south-1
![image](https://github.com/user-attachments/assets/0705de6f-7a12-4082-9b1c-708f2ef15289)
![image](https://github.com/user-attachments/assets/30dd4e30-e9af-4933-85a5-9065ba55e45b)
![image](https://github.com/user-attachments/assets/b45a0c6a-cb66-4b1c-8ba5-581a5fc08843)
4. Create the volume from the snapshot eu-north-1
![image](https://github.com/user-attachments/assets/2488474e-66ab-4585-a934-52178aa49a95)