# AWS IAM and S3 Access Control Lab

## Objective
To demonstrate the basic working of AWS IAM by creating an IAM user, creating an IAM group, attaching an S3 access policy, and testing user permissions through the AWS Management Console.

## Services Used
- AWS IAM
- Amazon S3

## IAM Components Practiced
- IAM User
- IAM Group
- IAM Policy
- AWS Managed Policy
- S3 Access Permission

## Lab Overview
In this hands-on lab, I created an IAM user named StudentUser and an IAM group named S3ReadWriteGroup. Then I attached the AmazonS3FullAccess policy to the group. After adding the user to the group, I tested the permissions using the AWS Management Console.

## Steps Performed
1. Logged in to AWS Management Console using the root/admin account.
2. Opened the IAM service.
3. Created an IAM group named S3ReadWriteGroup.
4. Attached the AmazonS3FullAccess policy to the group.
5. Created an IAM user named StudentUser.
6. Enabled AWS Management Console access for the user.
7. Added the user to the S3ReadWriteGroup.
8. Logged in using IAM user credentials.
9. Opened Amazon S3 and tested access permissions.

## Permission Used
Policy attached: AmazonS3FullAccess

This policy provides read and write access to Amazon S3.

## Principle of Least Privilege
The principle of least privilege means giving a user only the minimum permissions required to perform a task. In this lab, the IAM user was given access only for Amazon S3 instead of full administrator access to the AWS account.

## Screenshots
Sensitive information such as AWS account ID, ARN, email, sign-in URL, access keys, and password are hidden for security.

### IAM User Permissions
Add screenshot here showing IAM user permissions and attached policy.

## Output
The IAM user was successfully created and added to the IAM group. The AmazonS3FullAccess policy was attached to the group. The IAM user was able to access Amazon S3 according to the assigned permission.

## Key Learnings
- How to create an IAM user
- How to create an IAM group
- How to attach AWS managed policies
- How IAM permissions work through groups
- Basics of S3 access control
- Importance of least privilege in cloud security

## Conclusion
This lab helped me understand the basics of AWS IAM and how access permissions are managed using users, groups, and policies.
