CI/CD pipeline deployment1 - URL Shortner

Deployment Procedure File: https://github.com/bikigrg11/kuralabs_deployment_1/blob/main/deploy_proc.docx

Deployment 1                                                                                                            
Name: Biki Gurung
Date: 09/02/2022
Description: Build, Test and Deploy a repo from a Developer using Jenkins and Elastic Beanstalk.


Pre-requisites:
•	AWS account
•	CI tool of choice (Jenkins)
•	GitHub repository you’d like to deploy



Tables of Contents: 

Install Jenkins on an EC2:	2
Install Virtual Environment	4
Connect GitHub to Jenkins Server	6
Create an access token from GitHub	7
How to setup Jenkins:	8
Create a multibranch build	10
How to Download application files from GitHub and Deploy to Elastic Beanstalk	15
How to create an Elastic Beanstalk Env	16
List of Issues and their solution	18
Issue #1 – Couldn’t download zip file using SCP from the Server	18
Issue #2: Elastic beanstalk kept on failing with HTTP 502	21
What Improvements can be made?	23
Idea #1) Rapid Deployment with Jenkins	23
Upon sucessful Jenkins build and test. Use jenkins to compress the github repo and deploy to the Elasticbean automatically.	23
Idea #2) Create a separate Staging and Production Env so you can test your codes before you sent the developers code to production.	23
Idea #3) Scripts need to be checked against known attacks and malicious scripts databases to make sure that bad lines of code never get to the production environment.	23
CI/CD Pipeline Diagram:	24



CI/CD Pipeline Diagram: https://github.com/bikigrg11/kuralabs_deployment_1/blob/main/URL%20Shortener.jpeg
<img src="https://github.com/bikigrg11/kuralabs_deployment_1/blob/main/URL%20Shortener.jpeg">
