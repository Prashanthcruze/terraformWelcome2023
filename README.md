Creating a Azure Web App

Step 1 : Main.tf contains the providers and backend configuration of the terraform
Step 2 : Create a azure resource group(resourcegroup.tf).
Step 3 : Create a storage account in the resource group to store the terraform state file(storageaccount.tf).

Step 4 : Create a azure app service plan and azure app service to deploy the web application(appServicePlan.tf).
Step 5 : Variable.tf file contains the variables used in the terraform.

