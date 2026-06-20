# Fleet Data Quality Assistant

This project is a small Copilot Studio prototype for fleet data quality management in a Siemens Energy-style fleet management context.
![alt text](<Screenshot 2026-06-20 083802-1.png>)
The goal of the prototype is to demonstrate how an AI assistant can support data processing tasks such as:

- comparing fleet data from different systems
- identifying inconsistencies
- prioritizing data quality issues
- summarizing technical notes
- creating short fleet reports for managers

## Context
"https://m365.cloud.microsoft/chat/agent/T_9060d8ce-b5be-99ee-9ab7-03718d1ee4de.a29e6a96-bf50-450b-ba28-01c2e39c9876.gpt.89f6d554-2485-4092-b165-21f17a5d8091"

The demo is inspired by a Werkstudent position in data processing for fleet management. The role includes data comparison, data quality improvement, Excel-based reporting, automation, and AI-supported analysis.

## Demo Data

The demo uses fully synthetic fleet data. No real company data is used.

The data contains two simulated system exports:

- System A: Fleet Master Data
- System B: Contract Data

The systems contain differences in:

- contract end dates
- plant names
- operational or contract status

## Prototype Limitation

The demo data was prepared in Excel. Due to licensing limitations in the private trial tenant, the agent does not directly read from SharePoint/Excel. Instead, the same synthetic Excel dataset was embedded directly into the agent instructions.

In a real enterprise environment, the same concept could be connected to Excel, SharePoint, Dataverse, Power Automate, or Alteryx.

## Main Demo Questions

1. Compare System A and System B. Which fleet data inconsistencies exist?
2. Prioritize the detected issues by business impact.
3. Create a short fleet data quality report for a manager.
4. Summarize the technical email note and tell me which fleet data should be updated.

## Project Purpose

The project demonstrates understanding of:

- fleet data management
- data reconciliation
- data quality workflows
- reporting automation
- AI-supported data analysis
- Microsoft Copilot-style workflows