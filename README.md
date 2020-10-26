# Overview

![Python application test with Github Actions](https://github.com/PaulNWms/udacity-cicd-pipeline/workflows/Python%20application%20test%20with%20Github%20Actions/badge.svg)

~~<TODO: complete this with an overview of your project>~~

This project is a template implementation of a devops CI/CD pipeline.  Upon code checkin, the project is linted, built and API tested.  If all these are successful, a service is deployed to a live server.  The target server could be in a dev, staging or production environment.

A sample flask service is provided.  This is a placeholder; the intention is to replace it with your own microservice.

The code is stored in a GitHub repository.  Azure Pipelines is used to build the project, which hooks into Azure App Services for deployment.

## Project Plan

This project was done in the context of agile methods.  A CI/CD pipeline can be used with any project methodology, but agile relies on rapid, if not continuous, delivery to market (hence the name).

To start things off, a quick look ahead at the course contents and project requirements was done.  From this, milestones and time estimates were made, and a rough schedule in [Google docs](https://docs.google.com/spreadsheets/d/1MzGub0FddyPmF_IfvbL_cvbgdg01KYJ0uMRwSX69rHM/edit#gid=1348135932) was created.

A [Trello](https://trello.com/b/ySyI22ET/ci-cd-pipeline) board was created and tickets corresponding to the milestones were made.  The tickets are more detailed and (hopefully) broken down into ~4-hour jobs.  Of course these are just estimates, the actual time required can vary greatly.

(**Note to grader:** the Trello board was left in an incomplete state.  It's not much to look at if everything's in the Done column...)


~~<TODO: Project Plan~~

* ~~A link to a Trello board for the project~~

* ~~A link to a spreadsheet that includes the original and final project plan>~~

As mentioned in lecture, the management process overhead should be right-sized for the project.  But in this case, part of the assignment is the application of agile methods, so it's a bit process-heavy by design.

## Instructions

<TODO:  
* Architectural Diagram (Shows how key parts of the system work)>

<TODO:  Instructions for running the Python project.  How could a user with no context run this project without asking you for any help.  Include screenshots with explicit steps to create that work. Be sure to at least include the following screenshots:

* Project running on Azure App Service

* Project cloned into Azure Cloud Shell

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


