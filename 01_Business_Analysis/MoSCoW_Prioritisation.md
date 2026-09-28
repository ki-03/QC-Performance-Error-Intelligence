# MoSCoW Prioritisation

## Overview

The identified requirements were prioritised using the MoSCoW framework to define the scope of the initial solution and distinguish essential functionality from potential future enhancements.

MoSCoW categorises requirements into four priority levels:

- **Must Have** – Essential requirements for the solution to achieve its core objectives.
- **Should Have** – Important requirements that provide significant value but are not essential for the initial solution.
- **Could Have** – Desirable features that can be considered if time and resources allow.
- **Won't Have** – Features deliberately excluded from Version 1 but potentially considered in future development.

---

## Must Have

| ID | Requirement | Reason for Priority |
|---|---|---|
| M01 | Centralised QC dataset | Removes the need for separate reporting structures for each LA and provides a single source of truth. |
| M02 | Standardised QC data | Ensures QC information can be analysed consistently across different LAs. |
| M03 | Automated user-name standardisation | Prevents the same user from appearing as multiple users due to inconsistent formatting. |
| M04 | Automated quality and error calculations | Reduces repetitive manual calculations and improves reporting efficiency. |
| M05 | LA/batch-level performance analysis | Allows management to review overall batch quality and performance. |
| M06 | User-level performance analysis | Allows team leaders and users to understand individual performance. |
| M07 | Error-type analysis | Allows recurring and frequent error categories to be identified. |
| M08 | Historical trend analysis | Allows performance to be compared across different time periods. |
| M09 | Filtering by LA, batch, team, user, error type and date | Allows stakeholders to access the information relevant to their responsibilities. |
| M10 | Management visibility | Provides management with an overview of overall LA and batch performance. |
| M11 | Team-leader visibility | Allows team leaders to review the performance of their assigned users. |
| M12 | Individual user visibility | Allows users to review their own errors and performance. |

---

## Should Have

| ID | Requirement | Reason for Priority |
|---|---|---|
| S01 | Recurring error detection | Makes it easier to automatically identify repeated error patterns. |
| S02 | Improvement/deterioration analysis | Helps identify changes in user performance over time. |
| S03 | Automated error summaries | Can reduce the manual effort required to prepare individual feedback. |
| S04 | Automated error documentation | Can reduce the manual effort involved in preparing screenshots and error examples for reporting. |

---

## Could Have

| ID | Requirement | Reason for Priority |
|---|---|---|
| C01 | Automated individual reports | Could generate dedicated performance reports for individual users. |
| C02 | Automated email delivery | Could distribute performance summaries to relevant stakeholders automatically. |
| C03 | Threshold alerts | Could automatically flag users, teams or LAs exceeding defined error thresholds. |
| C04 | Training recommendations | Could suggest areas for improvement based on recurring error patterns. |

---

## Won't Have in Version 1

| ID | Requirement | Reason for Exclusion |
|---|---|---|
| W01 | Machine learning prediction of future errors | Not required to solve the current reporting and analysis problems and would increase project complexity. |
| W02 | AI-generated training plans | Outside the scope of the initial QC reporting and analysis solution. |
| W03 | Real-time production system integration | Would require access to external production systems and infrastructure outside the scope of this portfolio project. |
| W04 | Automated QC decisions | The project is intended to support the existing human QC process rather than replace human QC judgement. |

---

## MVP Scope

Based on the prioritisation above, the Minimum Viable Product (MVP) will focus on the core capabilities required to address the identified business problems.

The MVP will include:

1. **Centralised QC data**
2. **Data cleaning and standardisation**
3. **Automated user-name standardisation**
4. **Automated quality and error calculations**
5. **LA, team and user-level performance analysis**
6. **Error-type analysis**
7. **Historical performance trends**
8. **Filtering and stakeholder-specific visibility**
9. **Interactive QC performance dashboard**

The initial solution will focus on reducing manual reporting effort, improving data consistency, providing better visibility into QC performance and making error patterns easier to identify.

Advanced capabilities such as automated email reporting, threshold alerts, training recommendations and predictive analytics will be considered as potential future enhancements rather than part of Version 1.

## Prioritisation Summary

The prioritisation ensures that the initial solution remains focused on solving the core problems identified during the As-Is analysis while leaving more advanced automation and AI capabilities for potential future development.

The MVP therefore follows the principle:

**Centralise → Standardise → Automate → Analyse → Visualise → Improve**
