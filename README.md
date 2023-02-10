## Deploying a Next.js Application to Azure Using PM2

This guide will provide instructions for deploying a Next.js application to Azure using the Deploy Code feature and PM2 process manager without using Docker containers.

### Prerequisites
- A Next.js application that is ready for deployment
- An Azure account
- An Azure DevOps account

### Creating an Azure App Service
- Log in to the Azure portal and create a new App Service.
- Once the App Service is created, navigate to the "Configurations" section and make any necessary adjustments.

### Deploying to Azure
- Log in to your Azure DevOps account and create a new pipeline.
- In the pipeline, utilize the provided azure-pipelines.yml file, and fill in any missing details.
- Choose the branch you wish to deploy and initiate the deployment process.

### Local Development
First, run the development server:

```bash
    yarn install
    yarn dev
```
Open [http://localhost:3002](http://localhost:3002) with your browser to see the result.