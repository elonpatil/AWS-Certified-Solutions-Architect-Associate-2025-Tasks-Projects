**AWS CloudFront Hands-on Project**

I implemented AWS CloudFront to serve content efficiently via a CDN. I created an S3 bucket to store static files, then set up a CloudFront distribution to deliver content securely. After modifying the S3 bucket's access policy, I successfully accessed the index.html file through CloudFront. This exercise enhanced my understanding of Cloudfront configurations and secure content delivery using AWS.

1.	Create the bucket in S3.
![image](https://github.com/user-attachments/assets/ec5cba16-eca2-4d99-888d-22fd97e21bf9)
2.	Upload the code files.
![image](https://github.com/user-attachments/assets/1741232c-6687-4dc2-9f17-7c60e81513e8)
3.	Created the Cloudfront distribution with OAC (Origin Access Control) choosing the default root object index.html.
![image](https://github.com/user-attachments/assets/c00db70d-5489-4f1b-a41e-d1c6810f2968)
4.	Copy the policy code from coudfront and edit the origin bucket policy.
![image](https://github.com/user-attachments/assets/3cb3032e-9dbc-4a0a-ad92-0030ddc1d3b4)
![image](https://github.com/user-attachments/assets/6ae906f4-6a8e-4b21-8911-2db6df337381)
5. We can access the the content via Cloudfront distribution name. 
https://d2gekv6i7o5vcn.cloudfront.net
Now if we refresh the page, the content of the index.html file will be served from the cloud front cache and not from the origin. So, 2nd time this will be accessed more quickly as its served from the nearest edge location.
![image](https://github.com/user-attachments/assets/e4e4600d-712c-4da5-b7b0-0ce0638e8d03)
