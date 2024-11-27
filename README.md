# Host a Website on Amazon S3

This project demonstrates how to host a static website using *Amazon S3*, a scalable cloud storage service by AWS. It's a simple, beginner-friendly project that helps you understand the basics of hosting static content on the cloud.

---

## What is Amazon S3?

Amazon S3 (Simple Storage Service) is a secure, durable, and highly available object storage service. It is primarily used for storing and retrieving data from anywhere on the web. An unexpected yet powerful feature of S3 is its ability to host static websites.

---

## Project Highlights

- *Duration: The project took only **30 minutes* to complete.
- *Hosting Type*: Static website hosting directly from an S3 bucket.
- *Outcome*: Successfully hosted a portfolio page (index.html) with images.

---

## Steps to Host a Website on Amazon S3

### 1. Set Up an S3 Bucket
1. Log in to the AWS Management Console and navigate to S3.
2. Create a new bucket and pick a unique name (bucket names must be globally unique).
3. Select a region (e.g., us-east-1 for North Virginia, the closest region).

### 2. Upload Website Files
1. Upload your index.html file and any assets (like images) to the bucket.
2. Ensure that the files are correctly uploaded for hosting.

### 3. Enable Static Website Hosting
1. Go to the bucket properties and enable the *Static Website Hosting* option.
2. Set the index.html as the index document.

### 4. Update Permissions
1. Initially, you may encounter a *403 Forbidden Error* when accessing the site.
2. Fix this by updating the permissions of the files in the bucket to public.

---

## Accessing Your Website
After enabling static website hosting, Amazon S3 generates a *bucket endpoint URL*. Use this URL to access your hosted site from anywhere.

---

## Lessons Learned
- *Error Handling*: Encountered a 403 Forbidden Error due to private object permissions, which was resolved by updating the access settings.
- *Public Accessibility*: Properly managing permissions is crucial for making the website accessible over the internet.

---

## Project Outcomes
Successfully deployed a portfolio website on Amazon S3, demonstrating the process of hosting static files in a cloud environment.

---

## Want to Explore More?
Check out [NextWork.org](https://community.nextwork.org) for more exciting projects and resources!

---

Feel free to clone or fork this repository to experiment with static website hosting on S3!
