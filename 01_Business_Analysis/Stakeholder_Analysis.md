# Stakeholder Analysis

## Overview

The QC process involves several stakeholders who use QC information for different purposes. Understanding these different needs is important when designing the proposed QC reporting and analysis solution.

The solution should provide relevant information to each stakeholder rather than presenting the same level of detail to everyone.

## Stakeholder Identification

| Stakeholder | Primary Purpose | Key Information Required |
|---|---|---|
| **Manager** | Review overall LA/batch performance and assess whether the batch meets the required quality standard | Overall LA quality, error rate, total errors, error types and batch-level performance |
| **Team Leader** | Monitor the performance of the users assigned to their team | Quality and error rates of assigned users, individual error types and team-level trends |
| **Individual User** | Understand their own mistakes and improve future performance | Personal quality, errors made, error types, recurring mistakes and performance trends |
| **QC Analyst** | Improve the efficiency, consistency and usefulness of the QC process | Automated data processing, standardisation, reduced manual work, efficient reporting and actionable insights |

---

## Stakeholder Needs

### 1. Manager

The manager requires a high-level overview of QC performance for each Local Authority (LA) or batch.

The main purpose is to review the overall quality of the batch and understand whether it is meeting the required quality standards.

The manager needs visibility into:

- Overall LA/batch quality percentage
- Overall error rate
- Total number of errors
- Error types and their frequency
- Overall QC performance against the required quality threshold
- Performance information that can support the review of whether a batch meets the required quality standard

The information should be presented at an appropriate summary level so that the manager can quickly assess the overall performance of a batch without needing to manually search through detailed QC records.

---

### 2. Team Leader

Each team leader is responsible for a specific group of users within their team. Therefore, team leaders require visibility specifically into the performance of the users assigned to them.

The system should allow team leaders to view and analyse only the relevant members of their team.

The team leader needs visibility into:

- Quality percentage for each assigned user
- Error rate for each assigned user
- Number of errors made
- Error types made by each user
- Recurring error patterns
- Changes in user performance over time
- Overall team performance

This would allow team leaders to identify areas where individual team members may require additional feedback or support.

---

### 3. Individual User

Individual users are primarily interested in understanding their own QC performance and the mistakes identified during the QC process.

The system should provide users with visibility into their own performance rather than requiring them to search through wider team or LA-level information.

Users need visibility into:

- Their own quality percentage
- Their own error rate
- Errors identified during QC
- Types of errors they are making
- Recurring error patterns
- Changes in their performance over time
- Examples or explanations of their errors where available

This information can help users understand their recurring mistakes and identify areas for improvement.

---

### 4. QC Analyst

The QC analyst is responsible for carrying out QC and maintaining the information generated through the process. From the QC analyst's perspective, an important objective is to make the overall process more efficient, consistent and useful to the organisation.

The QC analyst needs the solution to:

- Reduce repetitive manual activities
- Reduce the need to create and configure separate workbooks
- Standardise QC data
- Automatically clean and validate data where possible
- Automate quality and error calculations
- Make historical information easier to access
- Reduce manual reporting and consolidation
- Make error patterns easier to identify
- Improve the usefulness of QC information for other stakeholders
- Provide a scalable process that can support additional LAs without requiring the same manual setup each time

The aim is to use automation and centralised data to reduce administrative effort while increasing the value of the information produced through the QC process.

---

## Stakeholder Information Flow

The different stakeholder needs can be summarised as:

**QC Analyst**
→ Ensures data is captured, standardised and processed efficiently

**Processed QC Data**
→ Provides a central source of QC information

**Manager**
→ Reviews overall LA/batch performance

**Team Leader**
→ Reviews performance of assigned team members

**Individual User**
→ Reviews personal errors and areas for improvement

This separation of information needs will be used to inform the requirements and design of the proposed solution.
