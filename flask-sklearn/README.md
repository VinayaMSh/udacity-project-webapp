# Overview

This project is intended as an example/exercise project to test complete CI/CD with Azure pipelines.

The project deploys a Python flask web application in Azure App services

Whenever there is a commit to the repostory, an automatic build is started in GitHub Actions and then is deployed to the App Services

The detailed instructions of how to start and configure the complete pipeline using this repository can be found below in detailed instructions. 

So, lets get started!

## Project Plan
<TODO: Project Plan

* A link to a Trello board for the project
* A link to a spreadsheet that includes the original and final project plan>

## Instructions

<TODO:  
* Architectural Diagram (Shows how key parts of the system work)>

<TODO:  Instructions for running the Python project.  How could a user with no context run this project without asking you for any help.  Include screenshots with explicit steps to create that work. Be sure to at least include the following screenshots:

* Project running on Azure App Service
  -  This project is already deployed and can be accessed with url https://flask-ml-1203.azurewebsites.net/
  -  ![image](https://github.com/VinayaMSh/udacity-project-webapp/assets/37274214/8f6023b3-db98-44cd-86e7-d95c0e5de346)



* Project cloned into Azure Cloud Shell
  -  Start by cloning this repository in your Azure Cloud shell
  
  ```
  git clone https://github.com/VinayaMSh/udacity-project-webapp.git
  ```

  -  Once successfully cloned, go to the repo folder on the shell
 
    The flask webapp code is found in the folder flask-sklearn in the repository, so change to this folder in the repository with the command below
  ```
  cd ~/udacity-project-webapp/flask-sklearn/
  ```



* Passing tests that are displayed after running the `make all` command from the `Makefile`

* Output of a test run

* Successful deploy of the project in Azure Pipelines.  [Note the official documentation should be referred to and double checked as you setup CI/CD](https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/python-webapp?view=azure-devops).

* Running Azure App Service from Azure Pipelines automatic deployment

* Successful prediction from deployed flask app in Azure Cloud Shell.  [Use this file as a template for the deployed prediction](https://github.com/udacity/nd082-Azure-Cloud-DevOps-Starter-Code/blob/master/C2-AgileDevelopmentwithAzure/project/starter_files/flask-sklearn/make_predict_azure_app.sh).
The output should look similar to this:

```bash
udacity@Azure:~$ ./make_predict_azure_app.sh
Port: 443
{"prediction":[20.35373177134412]}
```

* Output of streamed log files from deployed application

> 

## Enhancements

<TODO: A short description of how to improve the project in the future>

## Demo 

<TODO: Add link Screencast on YouTube>


