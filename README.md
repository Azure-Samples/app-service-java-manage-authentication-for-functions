---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Appservice
  platforms: java
---

# Getting Started with Appservice - Manage Function App With Authentication - in Java #


  Azure App Service basic sample for managing function apps.
   - Create 3 function apps under the same new app service plan and with the same storage account
     - Deploy 1 &amp; 2 via Git a function that calculates the square of a number
     - Deploy 3 via Web Deploy
     - Enable app level authentication for the 1st function app
     - Verify the 1st function app can be accessed with the admin key
     - Enable function level authentication for the 2nd function app
     - Verify the 2nd function app can be accessed with the function key
     - Enable function level authentication for the 3rd function app
     - Verify the 3rd function app can be accessed with the function key
 

## Running this Sample ##

To run this sample:

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/main/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/main/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/app-service-java-manage-authentication-for-functions.git

    cd app-service-java-manage-authentication-for-functions

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.