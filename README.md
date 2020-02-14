Deploying project using Azure Maven Plugin

https://docs.microsoft.com/en-us/java/api/overview/azure/maven/docs/web-app-samples?view=azure-java-stable

1. Clone the project
2. Edit the resource group and app names in pom.xml
3. In cmd, navigate to the directory of the project. 
   Enter the following commands:
   
   mvn clean package
   
   mvn azure-webapp:deploy
  
   