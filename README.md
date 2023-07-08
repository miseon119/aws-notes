# aws-notes

## Setup EKS

1. Create AWS account
2. Create a VPC
3. Create an [IAM role](https://ukayzm.github.io/aws-create-iam-user/) with Security Group (create AWS user with list of permissions)

Install awscli
```
brew install awscli
```

check configure list
```
aws configure list
```

Set `aws_access_key_id` and `aws_secret_access_key`

```
vi ~/.aws/credentials
```

