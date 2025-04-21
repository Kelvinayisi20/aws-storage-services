# aws-storage-services
# S3 Static Website Hosting & Object Management – Completed Setup

## Objective  
Successfully hosted static HTML files from mentees on an S3 bucket, configured public access permissions, and managed resources using the AWS CLI.

---

## 1. S3 Bucket Created  
I created an S3 bucket named `greatestdemos3` in my chosen region.  
- Disabled “Block all public access” to allow website hosting.

---

## 2. HTML Files Uploaded  
Uploaded the `index.html` file into a folder named `log/` inside the bucket using the S3 console.

---

## 3. Permissions Set to Public  
Set public read access for the uploaded file:  
- Used the “Make public” option under Actions.

---

## 4. Static Website Hosting Enabled  
- Enabled static website hosting in the bucket properties.  
- Set `index.html` as the index document.
