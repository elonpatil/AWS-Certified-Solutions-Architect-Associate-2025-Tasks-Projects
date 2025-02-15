**AWS S3 Bucket Hands-On: Public Access Setup**

I created an S3 bucket and successfully uploaded an object into it. Additionally, I configured the S3 bucket to allow public access, ensuring that the objects stored inside are accessible to anyone on the internet.

1. Created an S3 bucket with a unique name.
2. Uploaded an object (such as an image or file) to the bucket.
3. Configured the bucket policy and permissions to allow public access.
4. Verified that the object was publicly accessible by retrieving its URL.

By granting public access to the object, I made it available to anyone with the link, which is often useful for static websites, publicly accessible files, or serving media content.

1.	Creating the S3 bucket.
![image](https://github.com/user-attachments/assets/2241eb64-296f-444d-92c7-61a8e6db496a)
![image](https://github.com/user-attachments/assets/cef77939-a517-4677-acb7-72bb0904ecb3)
2.	Uploading the objects in the bucket
![image](https://github.com/user-attachments/assets/e30c1dcb-e371-4866-b76a-0f85b35ca26e)
3.	We can see the object by means of the long S3 **pre-signed URL**.
![image](https://github.com/user-attachments/assets/261798c7-e89e-47ae-9d72-ba0088f574fc)
4.	To **make the object accessible publically** we uncheck the Block public access checkBox.
![image](https://github.com/user-attachments/assets/bbce4030-145b-425f-ad1e-5347a0e4eda9)
5.	And, Create bucker policies for public access to that image/object.
![image](https://github.com/user-attachments/assets/2078657b-fa5f-4038-b24b-204935eef098)
6.	Now we can access the bucker object **through the object URL**.
![image](https://github.com/user-attachments/assets/88f51cea-cf4f-44dc-aaf9-880c864f3c9a)


