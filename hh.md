**S3 Cross-Region Replication**

I created two S3 buckets in different AWS regions and configured Cross-Region Replication (CRR). I set up a replication rule to automatically copy objects from the origin bucket to the destination bucket. To validate the setup, I uploaded an object to the origin bucket, which was successfully replicated to the target bucket in another region. This exercise helped me understand S3 replication, bucket policies, and IAM role permissions required for cross-region data transfer.

1.	Created the bucket name “mayur-bucket-origin” in “ap-south-1” and replication bucket name “mayur-bucket-replication” in Singapore “ap-southeast-1”. Enabled the versioning to them as the replication is not possible without versioning.
![image](https://github.com/user-attachments/assets/fed81241-7630-43eb-9570-58a6968a1fc7)
2.	On the origin bucket set the replication rule.
![image](https://github.com/user-attachments/assets/77c457d7-3c67-4081-88cf-4d1e24da8e2d)
![image](https://github.com/user-attachments/assets/d7ff202b-0594-4b74-ba2e-c2e1f304e654)
![image](https://github.com/user-attachments/assets/e17363ae-9823-4ef4-a580-90be2a0d9b51)
![image](https://github.com/user-attachments/assets/b2125194-337e-4741-80d5-9f5c3c1bc370)
3.	I uploaded the new file to the origin to check the replication.
![image](https://github.com/user-attachments/assets/308d1d99-cf3f-427f-b7c8-aa7e752f7bee)
YES, it's replicated in another region as seen in below SS.
![image](https://github.com/user-attachments/assets/6831fc8a-172b-45b7-95eb-ec5518a2acbe)
4.	Versioning also replicated.
![image](https://github.com/user-attachments/assets/6801339a-91cc-439a-be25-6808daeeb671)
![image](https://github.com/user-attachments/assets/3828750c-e031-453e-8ef1-ff5eb72a143b)
