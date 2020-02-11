# cloudformation-ec2

Just an util repo to store and upload my Cloudformation templates to an hard-coded s3 bucket

```
yarn deploy
```

# Deployment

Manually create Stack in CloudFormation using template S3 url => https://cf-template-acloudguru-2020.s3-eu-west-1.amazonaws.com/cf-template.yml

# SSH into the instance

```
ssh -i ~/.ssh/<keyName>.pem ec2-user@<Public Ip> 
```
