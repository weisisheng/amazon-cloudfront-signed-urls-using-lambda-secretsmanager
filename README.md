## Create Amazon CloudFront Signed URLs using Lambda and Secrets Manager

In this example we will provide step-by-step instructions to create **Amazon CloudFront Signed URLs** with both canned and custom policies using:
- **AWS Lambda** as the execution tool
- **AWS Secrets Manager** to manage the private signing key for security best practices
- **Amazon S3** as a restricted content source

Detailed information about:
- [Amazon CloudFront Signed URLs](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/private-content-signed-urls.html)
- [AWS Secrets Manager](https://docs.aws.amazon.com/secretsmanager/latest/userguide/intro.html)

**What you will need:**
- An AWS account with root access to configure the Amazon CloudFront key pair
- An AWS IAM user for other operations as security best practices
- Working knowledge of Amazon IAM, S3, CloudFront, Secrets Managers, and Lambda
- Working knowledge of Node.js

Please start with Step 1 to begin the exercise.    
[Step 1: Create Amazon S3 Bucket](1-Create_S3_Bucket/README.md)  
[Step 2: Create Amazon CloudFront Distribution](2-Create_CloudFront_Distribution/README.md)  
[Step 3: Create Amazon CloudFront Key Pair](3-Create_CloudFront_Keypair/README.md)  
[Step 4: Create AWS Secrets Manager](4-Create_Secrets_Manager/README.md)  
[Step 5: Create AWS CloudFront SignedURL with Canned Policy](5-Create_CloudFront_SignedURL_Canned/README.md)  
[Step 6: Create AWS CloudFront SignedURL with Custom Policy](6-Create_CloudFront_SignedURL_Custom/README.md)
