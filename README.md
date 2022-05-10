# udacity_project2
this is a GitHub repo use for Udacity project 2: Building a CI/CD Pipeline.\
*YOUTUBE demo link:* https://youtu.be/JfLo00u9xa0
## 1. Project Plan:
  Project plan for the third quarter of 2022:
<img width="1440" alt="Screen Shot 2022-05-10 at 11 08 40" src="https://user-images.githubusercontent.com/50902568/167569272-386b7964-7c7e-4aca-b5c6-6273a48adb7f.png">
  Trello board for task tracking as well as a spreadsheet with the estimated project plan:
<img width="1440" alt="Screen Shot 2022-05-10 at 11 36 40" src="https://user-images.githubusercontent.com/50902568/167570603-ad66f3df-4a67-451f-8222-547e1ab546c3.png">
## 2. Set Up Azure Cloud Shell:
### a. Create the Cloud-Based Development Environment.
I set up an initial project structure in the Azure Cloud Shell environment. First, I'll create a Github repository. Next, I'll launch an Azure Cloud Shell environment and integrate Github repository communication.
<img width="1440" alt="Screen Shot 2022-05-09 at 17 41 22" src="https://user-images.githubusercontent.com/50902568/167571259-65daa6da-5d32-4486-a9b8-e4599403d210.png">
### b. Create Project Scaffolding
  - Create the Makefile
  - Create requirements.txt
  - Create the Python Virtual Environment
  - Create the script file and test file
### c. Local Test
 <img width="1440" alt="Screen Shot 2022-05-09 at 17 44 23" src="https://user-images.githubusercontent.com/50902568/167571820-171372bc-6148-4ba6-87fc-0213f3145739.png">
<img width="1440" alt="Screen Shot 2022-05-09 at 17 44 56" src="https://user-images.githubusercontent.com/50902568/167571959-d6515158-f901-4566-8556-9cff37954877.png">

## 3. Configure GitHub Actions:
Configuring a SaaS build server like GitHub Actions is an essential step for any software project that wants to apply DevOps best practices. This completes the final section of Continous Integration and enables us to then move on to the later step of Continuous Delivery once this is complete.\
The remote Tests pass as below.
<img width="1440" alt="Screen Shot 2022-05-09 at 17 56 05" src="https://user-images.githubusercontent.com/50902568/167572473-af587b0b-5780-4d9a-9d96-58e3c2416b64.png">
## 4. Continuous Delivery on Azure:
Set up Continuous Delivery using Azure technologies. This will involve setting up Azure Pipelines to deploy the Flask starter code to Azure App Services.\
I have use another repo to setup/test Azure Pipeline. Althought it has been add into this repo.\
(https://github.com/hanganhhung123/flask-ml-service.git) \
Application online successfull.
<img width="1440" alt="Screen Shot 2022-05-10 at 14 26 11" src="https://user-images.githubusercontent.com/50902568/167572828-90991795-15d7-4d9f-9697-210ec272fd8c.png">
successfull predictation.
<img width="559" alt="Screen Shot 2022-05-10 at 14 27 23" src="https://user-images.githubusercontent.com/50902568/167573060-aba1b3c6-bd7c-416d-a3d0-a66642c620b7.png">


