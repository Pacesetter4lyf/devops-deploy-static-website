ALX pre course on DevOps: Deploying static website

In this project, I have configured, an S3 bucket to host static files. To be able to make the files accessible to the public, I have configured the s3 to accept traffic from the public. 

Cloudfront is a service that allows caching of files and quick access of same. We would sent up the cloudfront and point it to the s3 bucket.


CloudFront domain name
d2pf9nlct1q5lr.cloudfront.net

S3 object URL
http://my-322600968886-bucket.s3-website-us-east-1.amazonaws.com/

website-endpoint
https://my-322600968886-bucket.s3.amazonaws.com/index.html


Questions:
1. I wonder why the files took very long to upload.

2. I also am not sure i fully understand the below:
"If we were not "hosting" the website on S3, we could have made the bucket private and host the content only through the CloudFront domain name. In such a case, we cannot access the private content using S3 object URL and website-endpoint."



