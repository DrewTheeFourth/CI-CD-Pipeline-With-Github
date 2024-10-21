# CI-CD-Pipeline-With-Github
ABOUT CI/CD 

CI/CD stands for Continuous lIntegration and Continuous Deployment/Delivery and it is a necessary component of contemporary software development because they expedite the delivery of updates and the integration of code modifications. Continuous Integration (CI) ensures that new code integrates seamlessly with current systems by automating code integration and testing. Subsequently, Continuous Deployment (CD) streamlines the update release process by automating it, improving deliver speed and reliabilitv while decreasing

Key Benefits Of CI/CD.

Faster Time to Market: CI/CD pipelines automate repetitive tasks, allowing teams to release software more frequently.
Improved Quality: Automated testing helps identify and fix issues early in the development process, reducing the risk of defects in production.
Reduced Risk: Automated processes minimize human error and ensure consistency across releases.
Enhanced Collaboration: CI/CD promotes collaboration between development, testing, and operations teams.

PROJECT OVERVIEW

In this project, I created a simple HTML page and committed changes to it by building a CI/CD pipeline using AWS resources.

Write HTML code for a simple website and store locally, optionally, test your code using Live Server in Visual Studio Code.
Push code to a dedicated Github repository.
Create two IAM roles for EC2 and Amazon CodeDeploy to enable smooth communication between the services.
Create an EC2 instance and write some User Data Scripts to install certain dependencies such as Ruby and wget to install the AWS CodeDeploy agent on the instance.
Launch instance.
Create an application in Amazon CodeDeploy.
Create a Deployment Group.
Create a pipeline in Amazon CodePipeline, connecting to Github and configuring the repository and also configuring Amazon CodeDeploy and selecting the deployment group.
Load the instance IP address in any web browser.
Commit small changes in HTML code and push to Github repo.
Wait a few minutes and refresh instance IP address to see the changes implemented.

CHALLENGES ENCOUNTERED

During the course of this project, I encountered no compelling challenge.

AWS RESOURCES UTILIZED

IAM - Created two roles for EC2 and CodeDeploy respectively, to enable these services interact with each other directly.
EC2 - Hosted the HTML webpage on an EC2 instance.
CodeDeplox - Created an application to contain deployment configurations and resources.
CodePipeline - Created a pipeline to orchestrate the build, test and deploy stages of CI/CD.

TECHNOLOGIES EMPLOYED

The use of Al tools in this project have been instrumental, they include ChatGPT, Perplexity and Google Gemini  . I resorted to YouTube and Stack Overflow to figure out some complexities in this project.

LINKS

Stack Overflow
Perplexity AI
ChatGPT
YouTube
