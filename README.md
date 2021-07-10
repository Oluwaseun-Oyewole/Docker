##### Docker Django setup and deployment on AWS

##### deploying Docker to Amazon Elastic Cloud Registry
##### install awscli, check the version with aws --version,
##### configure awscli with IAM user(aws configure)

#### for deploying

##### aws ecr get-login-password --region us-east-1 | docker login --username AWS --password-stdin 182484352246.dkr.ecr.us-east-1.amazonaws.com
##### docker tag dockertest:latest 182484352246.dkr.ecr.us-east-1.amazonaws.com/dockertest:latest
##### docker push 182484352246.dkr.ecr.us-east-1.amazonaws.com/dockertest:latest  