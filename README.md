# SAP Cloud Platform Business Rules Sample Projects and Applications
SAP Cloud Platform Business Rules enables line of business users, application developers to automate decisions in simple human friendly rule language and integrate these decisions via APIs with their cloud applications. 
You can use these sample applications and rule projects as reference content to learn more about how-to build and consume business rules in neo and cloud foundry environments.

## Solution Diagram
This diagram shows how you can consume business rules service from workflow, cloud integration and other SAP Cloud solutions. 
![Solution Diagram](https://github.com/SAP/cloud-businessrules-samples/blob/master/images/BusinessRules_SolutionDiagram.png)

Beside these, there are many other services which can consume SAP Cloud Platform Business Rules. Below diagram shows a rich list of various consumption models:
![Consumption Models](https://github.com/SAP/cloud-businessrules-samples/blob/master/images/BusinessRules_ConsumptionPatterns.png)

## Prerequisites For Neo Environment
You need to have the following:
- SAP Cloud Platform (Neo) account with an active subscription to Business Rules service.
  - Refer [here](https://blogs.sap.com/2017/04/26/sap-cloud-platform-business-rules-try-it-yourself/) for information on accessing Business Rules in Neo trial account.
- **RuleSuperUser** role for Runtime and Repository operations.
- **Developer** role to create and deploy SAPUI5 applications in SAP Cloud Platform.
- SAP WebIDE Full-Stack service enabled in SAP Cloud Platform.

## Prerequisites For Cloud Foundry Environment
You need to have the following:
- SAP Cloud Platform Cloud Foundry account with subscription to Business Rules application. 
  - Refer [here](https://blogs.sap.com/2018/03/29/quick-start-guide-to-sap-business-rules-service-in-cloud-foundry/) for information on accessing Business Rules in Cound Foundry trial account.

## Folders Overview
The available samples are of 2 types depending upon the folder containing them. There would be different setup process for each type:
- **apps** - It contains SAPUI5 applications that need to imported from WebIDE and deployed to Neo environment. 
  - **shoppingcart** application shows how to consume rule service in custom HTML5 application
  - **rulesmanager** application shows how to embed SAPUI5 Rules Builder control in your custom application. 
- **rulesprojects** - It contains sample business rules projects that shows rules capabilities through different use cases
- **cf-apps** - It conatins **shoppingcart** SAPUI5 application that needs to be build and deployed in Cloud Foundry environment
  - Go to the [README](https://github.com/SAP/cloud-businessrules-samples/blob/master/cf-apps/README.md) to know more 

## Getting Started with Business Rules in Neo Environment
* Download and Extract the content from the [git](https://github.com/SAP/cloud-businessrules-samples)
- From content in **apps** folder:
  - Open SAP Web IDE Full-Stack and import the project zip using **File --> Import --> From File System** option.

- From content in **rulesproject** folder:
  - Open Business Rules Editor and import the project using the **Import** button on the Manage Projects screen

## Getting Started with Business Rules in Cloud Foundry Environment
* Download the content from [git](https://github.com/SAP/cloud-businessrules-samples/tree/master/cf-apps)
* Follow the instructions in [README](https://github.com/SAP/cloud-businessrules-samples/blob/master/cf-apps/README.md)

## Authors
Archana Shukla

## Copyright and License
Copyright (c) 2017 SAP SE. All rights reserved.
Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. 
You may obtain a copy of the License at > http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an 
"AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
