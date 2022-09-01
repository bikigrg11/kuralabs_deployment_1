<h1> CI/CD pipeline Deployment 1 - URL Shortner </h1>

<h3> Please download the documentation from :  https://github.com/bikigrg11/kuralabs_deployment_1/blob/main/deploy_proc.docx </h3>
                                                                                                
Name: Biki Gurung <br>
Description: Build, Test and Deploy a repo from a Developer using Jenkins and Elastic Beanstalk. <br>

Pre-requisites: <br>
<li>	AWS account
<li> CI tool of choice (Jenkins)
<li> GitHub repository you’d like to deploy



Tables of Contents: <br>

Install Jenkins on an EC2:	2 <br>
Install Virtual Environment	4<br>
Connect GitHub to Jenkins Server	6<br>
Create an access token from GitHub	7<br>
How to setup Jenkins:	8<br>
Create a multibranch build	10<br>
How to Download application files from GitHub and Deploy to Elastic Beanstalk	15<br>
How to create an Elastic Beanstalk Env	16<br>
List of Issues and their solution	18<br>
Issue #1 – Couldn’t download zip file using SCP from the Server	18<br>
Issue #2: Elastic beanstalk kept on failing with HTTP 502	21<br>
What Improvements can be made?	23<br>
Idea #1) Rapid Deployment with Jenkins	23<br>
Upon sucessful Jenkins build and test. Use jenkins to compress the github repo and deploy to the Elasticbean automatically.	23<br>
Idea #2) Create a separate Staging and Production Env so you can test your codes before you sent the developers code to production.	23<br>
Idea #3) Scripts need to be checked against known attacks and malicious scripts databases to make sure that bad lines of code never get to the production environment.	23<br>
CI/CD Pipeline Diagram:	24<br>



CI/CD Pipeline Diagram: https://github.com/bikigrg11/kuralabs_deployment_1/blob/main/URL%20Shortener.jpeg
<img src="https://github.com/bikigrg11/kuralabs_deployment_1/blob/main/URL%20Shortener.jpeg">
