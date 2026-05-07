# com682-cw2
Cloud Native Multimedia Platform – CW2 (Azure, Logic Apps)

## Project Overview
This project implements a cloud-native multimedia sharing platform as part of the COM682 Cloud Native Development module.

The solution is designed and deployed on Microsoft Azure and focuses on scalability, serverless architecture, and cloud-native integration.

## Technologies Used
- Azure App Service (WordPress frontend)
- Azure Blob Storage (multimedia file storage)
- Azure Logic Apps (REST API and workflow orchestration)
- Azure Cosmos DB (NoSQL metadata storage)
- Azure Monitor & Application Insights (monitoring)
- GitHub (version control)

## Functionality
- Users upload multimedia files via WordPress
- Files are stored in Azure Blob Storage
- Metadata is managed through REST APIs implemented using Logic Apps
- Metadata is persisted in Azure Cosmos DB
- Application performance and activity are monitored using Azure services

## Notes
This repository is used for version control and documentation purposes for coursework submission.

## DevOps / CI-CD Note
GitHub is used for version control. In a full production setup, this repository could be extended with CI/CD pipelines (e.g. GitHub Actions) to automate testing and deployment to Azure.

``
