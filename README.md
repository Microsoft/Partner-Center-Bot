# Partner Center Bot
This is a sample project that demonstrates how to leverage the Microsoft Bot framework to construct a bot that interacts with 
Partner Center. With this initial release, limited features are supported. Additional abilities will be added over time. The intent of this project is not to provide a fully functional bot, but rather to demonstrate how this technology can be utilized to support customers. 

This project is being provided with community support only. If you need help, please log an issue using the [issue tracker](https://github.com/Microsoft/Partner-Center-Bot/issues).

__Current Build Status:__ ![Build Status](https://isaiahwilliams.visualstudio.com/_apis/public/build/definitions/5a07f243-b522-4dc6-9ad8-9addc8633db6/3/badge)

## Features 
Currently, this project has the ability to list customers, select a specific customer, and list the subscriptions for that particular customer. 

![Bot Interaction](docs/Images/bot01.png)

In addition to integrating with Partner Center, the bot integrates with the [QnA Maker](docs/QnAMaker.md) cognitive service.
This makes it where the user can get answers to commonly asked questions.  

![Bot Interaction](docs/Images/bot02.png)

## Deployment
Please follow the [deployment guide](docs/Deployment.md) to obtain the necessary information for the ARM template. 
Once all the prerequisites have been fulfilled please click the *Deploy to Azure* button below to deploy the solution.

[![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FMicrosoft%2FPartner-Center-Bot%2Fmaster%2Fazuredeploy.json)
[![Visualize](http://armviz.io/visualizebutton.png)](http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FMicrosoft%2FPartner-Center-Bot%2Fmaster%2Fazuredeploy.json)

## Code of Conduct 
This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more 
information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact 
[opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## License
Copyright (c) Microsoft Corporation. All rights reserved.

Licensed under the [MIT](LICENSE) License.