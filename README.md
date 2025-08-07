# 2.----static-website-hosting
 Hosting static website in Amazon s3 service 
PROJECT DOCUMENTATION

Amazon S3 (Simple Storage Service) is a cloud-based object storage service offered by AWS. It allows users to store and retrieve any amount of data, from anywhere on the web, with industry-leading scalability, data availability, security, and performance. S3 is designed for storing and retrieving any kind of data, including structured, semi-structured, and unstructured data



Overview of project
This project documents the methodologies in using an Amazon S3 to store host a website on the web.

Tools /AWS services used
Amazon s3

PHASE 1 : Creation of bucket

1.	At the start of this project you log on into your aws management console,  and navigate to s3. And go to create bucket at the topright hand corner of your management console.
 
NB: with s3 there are no management fees and yo only pay for what you use. Prices are however based on the location of your s3 buckets.

![image](https://github.com/user-attachments/assets/669e03b5-0503-430b-a0fb-6c3ac16b810e)



2.	You then have to select the aws region that is closest to your point of location
   ![image](https://github.com/user-attachments/assets/a45e409e-915e-4eef-a2a4-eb961722e7ba)

 
4.	We make sure to uncheck the mark to unblock all public access to this bucket
 ![image](https://github.com/user-attachments/assets/e8da2e79-7720-45cb-b41e-a57abc23d6fb)







5.	Creation of an s3 bucket
 ![image](https://github.com/user-attachments/assets/6342c8c7-3881-4133-829b-0c6d34d145ad)

6.	Upload all files that are needed for the hosting of t he website
![image](https://github.com/user-attachments/assets/bc7207b1-fa07-44f0-a3b0-a1531f2b7290)


 


7.	We are to enable static website hosting
 
![image](https://github.com/user-attachments/assets/bf597c12-27bd-4864-895e-370ccc7c1e2a)


8.	Enabling static static website hosting
 ![image](https://github.com/user-attachments/assets/8b7b199b-315b-4b9e-95e3-faf2ef29df31)


9.	Edit static website hosting
    
 ![image](https://github.com/user-attachments/assets/0d1228c9-01b6-4266-b259-52a3c5e114a6)


11.	We tried logging into the website and we had an error.
 ![image](https://github.com/user-attachments/assets/c6c067d6-6856-49f4-956c-2ef6450e1cc1)


12.	We wiill get a caution to make it public
 ![image](https://github.com/user-attachments/assets/d2c28758-bfc3-45c1-bb43-2f62877e8cb2)


13.	 To solve the error we have to make the ACL public
 ![image](https://github.com/user-attachments/assets/5654385a-7f2b-4ee2-9011-b52137f429c9)

14.	Successfully made it public
 ![image](https://github.com/user-attachments/assets/59ecf7ba-95e9-4d71-afba-c5153feec885)


15.	Successfully made it public
    ![image](https://github.com/user-attachments/assets/76382235-dec4-47ef-9660-5b95466dbe87)

 





