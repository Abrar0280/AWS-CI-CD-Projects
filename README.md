## End to End MAchine Learning Project

1. Docker Build checked
2. Github Workflow
3. Iam User In AWS

## Docker Setup In EC2 commands to be Executed

#optinal

sudo apt-get update -y

sudo apt-get upgrade

#required

curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu

newgrp docker

## Configure EC2 as self-hosted runner:

## Setup github secrets:

AWS_ACCESS_KEY_ID=

AWS_SECRET_ACCESS_KEY=

AWS_REGION = us-east-1

AWS_ECR_LOGIN_URI = demo>>  566373416292.dkr.ecr.ap-south-1.amazonaws.com

ECR_REPOSITORY_NAME = simple-app


### Steps to check before:

1. Docker build checked

2. Github workflow

3. IAM user in AWS.

    - AWSEC@ContainerRegistryFullAccess
    - AWSEC2FullAccess

    Then click on the user and security config and then craeate access keys.

4. The search for Elastic container Registry


5. create EC2 instance:

    once command line is open :

        sudo apt-get update -y

        sudo apt-get upgrade

        curl -fsSL https://get.docker.com -o get-docker.sh

        sudo sh get-docker.sh

        sudo usermod -aG docker ubuntu

        newgrp docker
