# List of projects
Jan-2023 - Till now

Simcorp, Ukraine

Project: Performance as a Service

Position: Software Engineer/Developer

Team Size: 5 Developers + 1 Solution Architect + 1 Scrum Master
***
Feb-2022 - Dec-2022

EPAM Systems, Ukraine

Project: Content onboarding into Snowflake platform 

Position: Software Engineer/Developer

Team Size: 10 Developers + 5 QA + 3 DevOps + 1 Solution Architect + 1 Business Analysts + 1 Scrum Master

Tasks performed: 

Tactical solution (Was started as a proof of concept and then evolved as a Tactical solution, 3 developers team)

• Was in active discussions of solution architecture

• Investigated internal services where the data is retrieved from

• Investigated Snowflake capabilities and available tools

• Wrote key components of retrieving data from internal services

• Made adjustments to schema flattener and Kafka client components

• Investigated the cost of the application in a high-load scenario

• Substituted a Team Lead when he was on vacation or sick

• Implemented part of components related to application scaling

• Loaded content from internal services to Snowflake on Content team demand

• Tested and debugged the full flow of ingestion on cloud and locally

• Wrote terraform and adjust GitLab ci/cd template to written services

Shared all knowledge to other team members outside the Tactical solution team

Strategic solution (Redesign of old Ingestion solution after successful implementation of Tactical solution)

• Refactored a 'Main Entitlements flow' to make it faster and readable

• Wrote a Change Tracking view based on uni/bi-temporal data in Snowflake

• Investigated Snowpipe and Copy Into mechanism via S3 stages in Snowflake

• Implemented swapping mechanism for entitlements

• Implemented Snowflake Housekeeping service

• Investigated a Big Panda alarm service and initiated integration

• Implemented Manifest Processing step function and related services

• Implemented Customer Manager step function and related services

• Mentored and shared my knowledge with other developers

• Set up Event Bridge rules for step functions

• Implemented validation of lambdas input

• Proposed improvements on the ci/cd pipeline that were implemented by Dev Ops

• Fixed numerous bugs, cleaned code smells

Environment  & Tools: 

Databases: Snowflake + DynamoDB + S3 + MariaDB

IDE: Visual Studio 2021/Visual Studio 2022 + Visual Studio Code (Terraform, JavaScript)

AWS Tools: AWS Portal (Pages Described in Technologies) + AWS CLI 

Snowflake: Snowflake UI

API Testing: Postman

Command Line: Power shell + Bash

CI/CD: Terraform + GitLab CI/CD

Code Quality: Sonar Cube

Git: GitLab + GitKraken/Fork

C#: .Net 6 (AWS Lambda, Console app for ECS)

JavaScript: Node.js 16 (AWS Lambda, Step Function helper scripts)

AWS: AWS Lambda + ECS/Fargate + Elastic Container Registry + Step Function + Parameter/Secret Store + SQS/Managed Apache Kafka + SNS + CloudWatch + EventBridge

Kafka & Snowflake related: Schema Registry + Snowflake Connector for Kafka

ORM: Dapper

Logger: Serilog

Unit Tests: xUnit
***
Jul-2021 - Feb-2022

EPAM Systems, Ukraine

Project: Content onboarding into Snowflake platform 

Position: Junior Software Engineer/Developer

Team Size: 6 Developers + 3 QA + 2 DevOps + 1 Solution Architect + 3 Business Analysts + 1 Scrum Master

Tasks performed: 

• Implemented and supported Notification Service that aggregates messages from other services and pushes them to 'Compass Service'

• Proposed and implemented Dead Request Searcher Service that identifies unfinished/timeout requests and creates an alarm message

• Proposed and implemented a simplification of shared CosmosDB entities. As a result clean, readable messages and commodious message log interfaces

• Supported/continuous refactoring/implementing additional features for 'Entitlement Main Flow' Services

• Wrote sequel queries for Snowflake and DynamoDB

• Was in daily touch with other developers, especially DevOps and QA teams to identify and resolve upcoming tasks/problems

• Implemented part of phyton scripts for ci/cd

• Fixed numerous bugs, cleaned code smells

• Wrote Unit tests

• Participated and performed in knowledge transfer meetings for a production support team

• Prepared documentation pages for a production support team

• Created diagrams that describe Services in a Lucid Chart

As a result, our team delivered a project from concept to production. That fits all requirements, is flexible, could be extended by other developers, is covered by Unit and Smoke Tests, and deployment is simplified to one button via Terraform and Concourse

Environment & Tools: 

Databases: Snowflake + CosmosDB

IDE: Visual Studio 2021 + Visual Studio Code (Phyton scripts)

Azure Tools: Azure Portal + Azure Cosmos DB Emulator + Microsoft Azure Storage Explorer + Azure CLI 

Snowflake: Snowflake UI 

API Testing: Postman + Swagger 

Command Line: Power shell + Bash 

CI/CD: Concourse UI 

Code Quality: Sonar Cube Git: + GitLab + GitKraken 

Diagrams: Lucid Chart

C#: .Net Core 3.1/.Net 5 (REST API) 

Python: Python 3.9 

Azure: Azure Functions (Durable Functions) + Azure Key Vault + Azure Storage

Logger: NLog

Unit Tests: nUnit
***
May-2021 - Jun-2022

Internal Lab EPAM Systems, Ukraine

Project: Knowledge accounting system application

Position: Trainee/Developer

Team Size: Solo project

Tasks performed: 

• Created 3-layer (DAL, BLL, PL) low-coupled application architecture

• Used patterns: repository and unit of work

• Created database schema using EntityFramework Core via code first approach

• Used Identity Core and JWT for authorization with multiple roles (guest, user, administrator)

• Used Swagger for testing Web Api

• Created SPA using Angular and TypeScript

• Created UI design using HTML, CSS, Bootstrap, and Font Awesome

This is a ASP.NET Core web-application and allows you find your future employee or employer and evaluate their work. Anonymous can: + Register and login + Find and view users (without any personal data)User can: + What anonymous can + Edit personal data (only personal page) + Set status (only personal page) + Add descriptions about yourself and delete after (only personal page) + Guest other personal pages, leave comments and edit/delete after Admin can: + What user can + Edit personal data (for every user) + Set status (for every user) + Add descriptions about yourself and delete after (for every user) Link to the project on GitLab: https://gitlab.com/ProkopchukMaksym/knowledge-accounting-system



Environment & Tools: 

Databases: MS SQL via Entity Framework code first approach

IDE:  Visual Studio 2019 (Backend) + Visual Studio Code (Frontend)

API Testing: Telerik fiddler‍ + Swagger

Command line: Power shell

Frontend development: Chrome DevTools‍

Database ORM: EntityFramework Core Authorization: + Identity Core 

Web api: ASP.NET Core Web Api 

Web interface: Angular 8 + Bootstrap 4 + Font awesome 

Mapping: Automapper 

Version control system: Git (GitLab)