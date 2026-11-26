# ServiceNow – Setting SLA on Incident Type

## 1. Project Overview
This project demonstrates the configuration and implementation of a Service Level Agreement (SLA) for Incident Management in ServiceNow.

## 2. Objective
To configure an SLA that tracks incident resolution time and ensures timely resolution.

## 3. Technologies Used
- ServiceNow
- Incident Management
- SLA Definitions
- Task SLA
- Business Rules

## 4. SLA Configuration
- SLA Name: Incident Resolution SLA
- Table: Incident
- Target: Resolution
- Duration: 4 Hours
- Start Condition: Active is true
- Pause Condition: State is On Hold
- Stop Condition: State is Resolved

## 5. Implementation
1. Created an SLA Definition.
2. Configured start, pause and stop conditions.
3. Created an incident.
4. Verified the SLA attachment.
5. Tested SLA In Progress.
6. Tested SLA Pause and Resume.
7. Tested SLA Completion.
8. Tested SLA Breach.

## 6. Expected Outcome
The SLA automatically tracks incident resolution time and identifies incidents that exceed the defined time limit.

## 7. Conclusion
This project demonstrates how ServiceNow SLA management improves incident handling, monitors resolution time and supports timely IT services.

## 8. Screenshots
The Screenshots folder contains the practical implementation and testing evidence.
