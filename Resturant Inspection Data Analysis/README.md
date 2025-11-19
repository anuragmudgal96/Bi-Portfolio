# Restaurant Inspection Data Analysis

### Project Objective (Business Problem):
Our goal is to use Microsoft Fabric & Power BI Service (and Desktop) to build  end-to-end analytics pipeline for scalable reports & dashboards from the inspection data that can be shared across the company for collaboration.

<img width="940" height="366" alt="image" src="https://github.com/user-attachments/assets/7c24cfe0-47c6-4db6-90be-e808ef201782" />

## KPIs & Metrics:
- Total Inspections, All Inspections
- % of All Inspections, Previous Month Total Inspections
- Total Violations, All Violations, % of All Violations
- Average Sanitary Grade, Previous Month Avg Sanitary Grade
- Grade “A” Inspections, Grade “B” Inspections, Grade “C” Inspections

## Data Source & Transformation:
Dataset consist of fact table having 1 Mn records with 25 columns containing health inspection records, along with details about each restaurant, health inspector, and violations.
- Connecting data using On-premises data gateway
- Utilising Dataflow Gen2 (CI/CD) to connect it with the data gateway to access the files available in the system.
- From the Model view, created relationships to connect the fact table to all lookup tables

<img width="940" height="363" alt="image" src="https://github.com/user-attachments/assets/a1667595-d079-427a-86a1-b3be455271bf" />


## Dashboard:
<img width="940" height="490" alt="image" src="https://github.com/user-attachments/assets/e48c9109-52ee-433a-996f-da6b1ec14236" />

## Learning Outcomes:  
- Connected on-prem data using On-Premises Data Gateway
- Built interactive reports and dashboards in Power BI Service
- Automated refresh using Dataflows + Scheduled Refresh
- Published and shared reports via Workspaces & Power BI Apps
- Implemented RLS (static & dynamic) for secure data access
- Added data-driven alerts for proactive monitoring
- Designed star schema models (Fact/Dim)
- Created semantic models with DAX measures for analytics
- Ingested and transformed data using Dataflow Gen2
- Automated end-to-end workflows using Gateways, Dataflows, Pipelines
