# This markdown is instruction of our AWS IAC codes
## what did we have(after apply, what will be created)
1. a k8s cluster with vpc
2. AWS code build
## what variables do we need
1. test_mongo: test mongodb url
2. codebuild_image: customer image from ecr
3. mongoDBip: production mongo url
4. AWS_ACCESS_KEY_ID: aws access key
5. AWS_SECRET_ACCESS_KEY: aws secret key
6. dockerusername
7. dockerpassword
## what need to set before terraform apply:
1. A ECR or docker hub that have docker write in docerAssets.d folder
## How to run this project:
1. `terraform init`
2. filled all variables
3. `terraform apply`