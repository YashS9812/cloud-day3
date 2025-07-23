# ☁️ AWS Cloud — Day 3: IAM & S3 via AWS CLI

## 🔐 What I Did
- Created a new IAM user with programmatic access
- Configured AWS CLI on local machine using Access Key & Secret
- Created an S3 bucket from the command line using:
  aws s3api create-bucket --bucket cloud-day3-yashs9812-v2 --region eu-north-1 --create-bucket-configuration LocationConstraint=eu-north-1

  Verified the bucket with:   aws s3 ls


Took CLI screenshot for proof
Cleaned up resources to avoid billing:
Deleted IAM user
Terminated EC2 instance
Verified volume deletion

🖼️ Screenshot
Screenshot shows:
aws configure process
Successful bucket creation
Bucket listed with aws s3 ls

🔗 Learning Summary
Gained hands-on with IAM and AWS CLI
Understood how S3 buckets are created and managed via terminal
Practiced secure and clean cloud resource management

