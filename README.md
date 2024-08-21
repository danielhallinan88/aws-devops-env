# Jenkins  
This template creates the latest Jenkins server with a security group to allow SSH and the UI over port 8080
Command to run the Cloudformation
```bash
aws cloudformation deploy --template-file jenkins-cloudformation-template.yaml --stack-name JenkinsStack
```
