# ITSM Incident Analysis Dashboard

## Project Overview

This project analyzes ITSM incident data to understand workload
patterns, measure resolution efficiency, and evaluate current incident
status using Power BI.

## Objectives

-   Analyze incident volume and workload trends
-   Measure incident resolution efficiency using MTTR
-   Understand incident state distribution
-   Identify operational bottlenecks and workload concentration

## Tools Used

-   Power BI
-   Power Query
-   DAX

## Concepts

-   Data Understanding
-   Data Cleaning
-   Data Validation
-   KPI Design
-   DAX
-   Visualization
-   Business Analysis

## Dashboard Pages

1.  Incident Trend & Workload Analysis
2.  Resolution Efficiency Analysis
3.  Incident State Analysis

-   ![Page 1](images/page1_incident_trend_and_workload.png)
-   ![Page 2](images/page2_resolution_efficiency.png)
-   ![Page 3](images/page3_incident_state.png)

## Data Validation Decisions

-   Used latest incident snapshot (24,918 unique incidents)
-   Validated missing values before KPI creation
-   Validated incident counts before creating insights
-   Skipped unsupported business problems instead of forcing conclusions
-   Excluded SLA, Reassignment, Reopen, and Aging analyses due to
    dataset limitations

## Key Insights

-   Incident volume dropped after May-2016 due to reduced incident
    recording periods rather than operational improvement
-   Moderate priority incidents contributed 95% of total incident volume
-   Most incidents were resolved within 1 day
-   Group 9 showed the highest average resolution time
-   Category 34 showed the highest average resolution duration
-   Nearly 92% of incidents remained in New or Active status

## Business Impact

Enabled visibility into incident workload, resolution performance, and
operational status to support better monitoring and prioritization
decisions.

## GitHub Repo Structure

-   datasets/
-   docs/
-   images/
-   powerbi/
-   README.md

