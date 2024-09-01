## Creating a Static Website with Amazon S3

### Introduction to S3:

- Amazon S3 (Simple Storage Service) is introduced as the service that will host your static content.
- You'll create a static web page using HTML, CSS, and JavaScript, and store it in an S3 bucket.

### Steps to Create a Bucket and Upload Files:

- Create a Bucket: You’ll create a globally unique S3 bucket name.

- Configure Bucket Settings
  -- Object Ownership: Enable Access Control Lists (ACLs) to manage access permissions.
  -- Public Access: Uncheck "Block all public access" to make the bucket publicly accessible.

- Upload Static Content: Upload your HTML, CSS, and JavaScript files into the S3 bucket.

- Set Up Static Website Hosting: Enable static website hosting in the bucket settings and specify index.html as the index document.

### Testing the Website:

- After setting up, you can access your site using the endpoint provided by AWS.
- Initially, you might encounter a 403 error if the index.html file isn't created yet. You can test the setup by manually navigating to other HTML files, such as chats.html.
