**Cross-Region S3 Buckets with CORS Configuration**

In this hands-on project, I created two S3 buckets to explore cross-region access. The primary bucket was deployed in the Mumbai region, while the secondary bucket, containing additional code content, was set up in the Singapore region. 
To enable seamless access between the two buckets, I configured Cross-Origin Resource Sharing (CORS), allowing resources from the secondary bucket to be accessed by the primary bucket. 
This setup demonstrates how CORS can facilitate cross-region data sharing within AWS S3.

1.	Created the main S3 bucket where the main web page is uploaded. Uploaded the index.html file and required images for the index page. Given the necessary getObject access to the bucket.
![image](https://github.com/user-attachments/assets/501e8211-f480-4211-a11d-0e82acb5d96c)
2.	Created another bucket in a different region and uploaded the other part of the main index.html which is deployed in the Mumbai region.
![image](https://github.com/user-attachments/assets/5b1a267a-b751-4030-b9ce-baa16adbf128)
![image](https://github.com/user-attachments/assets/f94bd4fd-ba60-4728-be34-6e76b71a6bf7)
3.	Updated the index.html file with the following code.
http://demo-other-origin-mayur-8788.s3-website-ap-southeast-1.amazonaws.com/extra-page.html. 
![image](https://github.com/user-attachments/assets/1e52b047-bd20-4e46-bed2-b84492e8d4f3)
![image](https://github.com/user-attachments/assets/eef0f793-984b-42d3-8d04-26918fce4cbb)
4.	While accessing the content of another bucket, we are getting the access issue. 
![image](https://github.com/user-attachments/assets/fdc72f57-f667-4cd9-baa4-0001ab0b796c)
5.	To resolve this, we have to set the other bucket for CORS.
![image](https://github.com/user-attachments/assets/b1fc2738-3d75-4d3e-a6c8-61be2e840d91)
Before core setting
![image](https://github.com/user-attachments/assets/824bd598-4bc6-4171-9aa2-d17c5d7a18df)
After the CORS setting
![image](https://github.com/user-attachments/assets/26f3a9c1-26fc-4c85-b60c-18af33229081) 
Proof: 
![image](https://github.com/user-attachments/assets/3f4c2548-fd44-4c23-9ce6-4e4373e30950)
 
