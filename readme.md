# Homework 8  Devops - Automated Builds Pushing to Dockeruhub

This repository contains code to setup a GitHub Action to implement a CI/CD workflow to automatically test, build and push my program's image to Dockerhub.  

## On cloning the repository

You can run the following command to run the python file directly:

pip install -r requirements.txt && python main.py

            OR
            
Run the following commands to pull the docker image from DockerHub and run

docker image pull mallikakasi/is601_hw8_devops:latest

docker run -d mallikakasi/is601_hw8_devops:latest


## Screenshot of the image in my Docker account .

### Screenshot that shows GitHub Actions CI Workflow to run tests and build and push the docker image to DockerHub

  ![image](https://github.com/user-attachments/assets/eadf8d7f-f5b7-432c-a37d-c0f4b5f6be76)

##3 Screenshot that shows successful Build Image and pushed to my Docker Hub account

![image](https://github.com/user-attachments/assets/a2cd2c38-1072-40e5-9d3a-cca535185b80)

![image](https://github.com/user-attachments/assets/b320238c-5640-4876-a1a6-0181f430cb11)
![image](https://github.com/user-attachments/assets/e90e542c-bec5-4925-97e5-3be0fe4a76f2)

