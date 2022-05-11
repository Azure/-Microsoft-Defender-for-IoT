# Module 1 - Setting up the environment

#### 🎓 Level: 100 (Beginner)
#### ⌛ Estimated time to complete this lab: 20 minutes

## Objectives

This module guides you through the deployment of the Microsoft Defender for IoT Training Lab solution that will be used in all subsequent modules.

#### Prerequisites

To get started with Microsoft Sentinel, you must have a Microsoft Azure subscription. If you do not have a subscription, you can sign up for a free account [here](https://azure.microsoft.com/en/free).

Permissions to create a resource group in your Azure subscription.

### Exercise 1: Deploy The Sensor in Azure

In this exercise we will show you how to create a brand new Microsoft Defender for IoT sensor on Azure.

For the deployment, a VHD file is used, the link for the IoT sensor installation is in the email you have received, please copy it now as you will need to paste it in the next step

Please note - This link is private and will expiree in 3 days. 

To Deploy The Sensor VM, click below button to generate a template deployment installation 

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FContoso-Hotels-Security%2FDefenderForIOT%2Fmain%2FDeploySensorV22%2Fazuredeploy.json" target="_blank">
  <img src="https://aka.ms/deploytoazurebutton" scale="0">
</a>



Please update the following screen as follow:

<img src="./Images/Deployment_1.png">

1. Please select your Azure subscription to which you would like to deploy the trail service.
2. Please select an existing resource group or create a new one (Use the hyperlink below the box).
	a. We recommend creating a new one to easily identify the relevant resources of the trail service.
3. Please select the Region (Time zone) to which you are deploying the trail service to.
4. Please leave the location box with its default value, no need to change it.
5. The trail service can be available to be used with an external IP that will be accessible from the WWW should choose the public IP option set to "True", otherwise the service will use an internal IP only.
6. Please Paste the link of the VHD copied from the mail recived into this filed.
	a. Please make sure there are o omitted characters or added ones.


Once complete please click on the Review + Create button
Upon validation complition, proceed to click on the Create button to initiate the process.
<img src="./Images/Review_&_ Create button.png">


The process runs for approx. 30 to 60 minutes

<img src="./Images/Go_to_Resource_Group.png">

A message saying "Your deployment is complete" is the result of a successful deployment.

To proceed to launch the trail version, identify the IP of the service by the Go to resource group button on the bottom.
<img src="./Images/VM_Resource.png">
