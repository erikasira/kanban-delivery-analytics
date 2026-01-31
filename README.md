# **Kanban Delivery Analytics Dashboard**

_Excel | Data Modeling | Flow Metrics_

## **Project Overview**

This dashboard is inspired by a real-world Kanban reporting solution I designed while supporting a DevOps team. For this project, I recreated the structure using synthetic data to focus on metric design, data modeling, and visualization best practices.

The dashboard highlights workflow trends, delivery performance, and operational insights intended to support continuous improvement and effective stakeholder communication.

## **Business Problem**

Kanban teams often struggle to maintain visibility into work in progress, delivery predictability, and overall flow efficiency. At the same time, leadership requires clear and concise metrics to understand progress without disrupting team workflows.

## **Project Objectives**

- Track work status and flow using Kanban metrics

- Analyze cycle time trends across sprints

- Compare planned versus unplanned work

- Provide clear, executive-friendly visualizations

## **Data Description**

The dataset consists of 99 synthetic Kanban tickets modeled after a DevOps team workflow. Each ticket includes key attributes used to analyze flow and delivery performance.

_Key fields include:_

- Status (New, WIP, Closed, On Hold, Cancelled)

- Priority (P1–P4)

- Sprint (Sprint 1–6)

- Start Date, ETA, Close Date

- Calculated Cycle Time

## Metrics & Calculations

Key metrics were calculated using Excel formulas and include cycle time, throughput, forecast accuracy, and planned versus unplanned work distribution.

## Dashboard & Insights

The dashboard visualizes delivery performance through charts and summary metrics. Analytical insights derived from these visuals are documented in a dedicated Insights & Observations tab to support data-driven decision making.

## Assumptions & Limitations

- Data is synthetic and intended for demonstration purposes

- Sprint length is assumed to be two weeks, except for Sprint 6, which is three weeks

- Metrics are intended to illustrate trends rather than evaluate real team performance

## Tools Used

- Microsoft Excel

- Tables and Charts

- Excel formulas (e.g., AVERAGEIFS, COUNTIFS)
