# Infrastructure

we are using cloudformation to use build vpc and infrastructure on aws that will be needed to deploy ec2 instance 

## create stack

aws cloudformation create-stack --stack-name CSYE6225 --template-body file://infra.json --parameters file://vars.json

## delete stack

aws cloudformation delete-stack --stack-name CSYE6225

## update stack

aws cloudformation update-stack --stack-name CSYE6225 --template-body file://infra.json --parameters file://vars.json

add --profie while using aws cli