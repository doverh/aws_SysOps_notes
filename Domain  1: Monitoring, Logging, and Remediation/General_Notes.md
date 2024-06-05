# GENERAL NOTES

## Practice Exam

<https://www.udemy.com/course/practice-exams-aws-certified-sysops-administrator-associate/?_gl=1*snug29*_ga*MTIwMDEwMzc3Mi4xNzE1MjkzNTE3*_ga_6GZZTGGX7H*MTcxNTI5MzUxNy4xLjAuMTcxNTI5MzUxNy42MC4wLjA.&couponCode=MAY_24_GET_STARTED>

<https://portal.tutorialsdojo.com/cart/>

## SHARED RESPONSABILITY MODEL

[AWS Shared Responsability Model](../../Images/Shared-responsability-model.png)

## VIDEOS

<https://www.udemy.com/course/ultimate-aws-certified-sysops-administrator-associate/?_gl=1*snug29*_ga*MTIwMDEwMzc3Mi4xNzE1MjkzNTE3*_ga_6GZZTGGX7H*MTcxNTI5MzUxNy4xLjAuMTcxNTI5MzUxNy42MC4wLjA.&couponCode=MAY_24_GET_STARTED>

## REFERENCE

<https://digitalcloud.training/category/aws-cheat-sheets/aws-sysops-administrator-associate/>

## CONTAINERS

A sandboxed process running on a host machine that is isolated from all other processes running on that host machine.

1. Create a instance using a stack
2. When stack is completed click on Stack Name > Resources Tab > Public EC2
3. Right click on Instance Id > Connect  
# Install Docker Engine on EC2 Instance
sudo dnf install docker
sudo service docker start
sudo usermod -a -G docker ec2-user

LOGOUT and login

sudo su - ec2-user

## Build Docker Image

cd container
docker build -t containerofdogs .
docker images --filter reference=containerofdogs

## Run Container from Image

docker run -t -i -p 80:80 containerofdogs .

## Upload Container to Dockerhub (optional)
docker login --username=YOUR_USER
docker images
docker tag IMAGEID YOUR_USER/   
docker push YOUR_USER/containerofdogs:latest



Create a docker image
docker build -t getting-started .

from https://docs.docker.com/get-started/02_our_app/