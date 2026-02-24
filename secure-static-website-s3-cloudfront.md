#  Project 1: Hosting a Secure Static Website with Amazon S3 and CloudFront

##  Project Overview

In this project, I demonstrate how I hosted a static website using **Amazon S3** and secured it with **CloudFront**.

The goal was to:

- Keep the S3 bucket **private**
- Enable **secure HTTPS access**
- Use **CloudFront as a secure entry point**
- Follow production-style architecture principles

Final Architecture:
User → CloudFront (HTTPS) → Private S3 Bucket

---

# Step 1: Creating and Configuring the S3 Bucket

I logged into the AWS Management Console and searched for **Amazon S3**.

Before creating the bucket, I carefully selected the region based on:

- Compliance considerations  
- Pricing  
- Service availability  
- Proximity  

For this project, I selected:
