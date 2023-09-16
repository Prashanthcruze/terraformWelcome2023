**CDX – Azure Web App**

GitHub URL’s:

1. WebApp Code: <https://github.com/Prashanthcruze/projectwelcome2023>
2. Terraform Code: <https://github.com/Prashanthcruze/terraformWelcome2023>
3. Web Application URL: <https://projectwelcome-app-service.azurewebsites.net>

Prerequisites:

1. Azure account with active Azure subscription
2. Terraform for IAC
3. GitHub Account for deploying with Actions.

Step 1: Implementation of the Azure Web Application

1\. Configure the Azure account in the VS code terminal with power shell commands.

2\. Create main.tf to configure the azure provider settings.

3\. Create variable.tf file to store the variable whenever needed.

4\. Create resourcegroup.tf file to create a resource group in suitable location in azure.

5\. Create a storageAccount.tf to create a storage account with container to store the terraform state file.

6\. Now initialise the terraform script with "terraform init" and plan the resources with "terraform plan" and build the resources with "terraform apply" command.

7\. Resource group and storage account with container will be created in azure.

8\. Now update the main.tf required details with backend block to store the terraform state file in the newly created storage account container.

9\. Create appServicePlan.tf to create the azure app service plan and app service resource to build a PAAS web app.

10\. Run the terraform init -reconfigure/-migrate-state command to store the local state file into azure storage account. Then run terraform apply command to build the azure app service.

Step 2: Web Application(PAAS) – Welcome to 2023

1\. Upload a web application of any programming language (Java) in the GitHub account.

2\. Log in to Azure, choose our web app and configure the basic settings (Java configuration) 

3\. Select the type of deployment – GitHub actions and the repository to the web app.



Step 3: Build and deploy of web app

1\. Configure the azure perquisite connection – (azure web app publish profile) in the GitHub repository setting secret and variables.

2\. Choose the type of deployment in actions.


3\. Run the configured action to deploy the web application in azure web app.

4\. Once deployed go to web application URL to display the desired content.



Web App URL: <https://projectwelcome-app-service.azurewebsites.net/>

Web Application have been successfully deployed in azure web app with GitHub action.

Thank You
