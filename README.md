# Azure Resource Graph Queries for Estate Inventory

## Project Overview
This project uses Azure Resource Graph and Kusto Query Language (KQL)
to inspect Azure resources and review resource group and tag information.

## Objectives
- Display Azure resource inventory
- List resource groups
- Count resources by type
- Review resource group tag compliance
- Identify resources missing required tags

## Technologies
- Microsoft Azure
- Azure Resource Graph Explorer
- Kusto Query Language (KQL)
- CSV

## Queries
1. Complete Resource Inventory
2. Estate Resource Groups
3. Resource Count by Type
4. Resource Group Tag Compliance
5. Missing Tags Audit

## How to Run
1. Sign in to the Azure portal.
2. Open Resource Graph Explorer.
3. Select the appropriate subscription scope.
4. Open a query from the queries folder.
5. Paste the KQL query and click Run.
6. Review the results.

## Project Limitation
The queries identify and report resource information.
They do not automatically repair missing tags.