# AzureMonitoringProject

## Project Overview

The AzureMonitoringProject demonstrates setting up infrastructure monitoring for Azure resources using Azure Log Analytics and Azure DevOps. It automates the deployment of monitoring agents on Azure VMs and centralizes log and metric collection in a Log Analytics workspace.

## Key Features

- **Automated Monitoring Setup**: Deploy monitoring agents using Azure DevOps pipelines.
- **Centralized Data Collection**: Collect logs and metrics in a single Log Analytics workspace.
- **Custom Data Collection Rules**: Define and apply Data Collection Rules (DCRs) for flexible data collection.

## Technologies Used

- Azure Log Analytics
- Azure DevOps
- Data Collection Rules (DCRs)
- Virtual Machines (VMs)

## Setup Instructions

1. **Configure Azure Resources**: Set up a Resource Group, VMs, and a Log Analytics workspace in Azure.

2. **Set Up Azure DevOps Pipeline**: Create a pipeline using `pipeline.yaml` and deploy monitoring agents.

3. **Verify Monitoring**: Use Log Analytics in Azure to check the collected logs and metrics.
