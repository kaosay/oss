# oss
How to use Object Storage Service

## create bucket
[https://oss.console.alibabacloud.com/](https://oss.console.alibabacloud.com/bucket)

Create Bucket -> Bucket Name -> Region -> Create

#### access control list ACL
Block Public Access:

Enabled

Bucket ACL:

Public Read

Bucket Policy:

Authorized User -> RAM User

## create RAM user
https://ram.console.alibabacloud.com/  
Users -> create user -> user login name -> Permanent AccessKey -> OK

Attach policy -> AliyunOSSReadOnlyAccess

Then return to bucket policy!


