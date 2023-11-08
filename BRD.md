# Project Name: Business Requirement Document (BRD) for CashBuddy

**Authors and Responsibilities:**

- Haicha NIANG:

  - 3.1 Background
  - 4.1 Business Process Overview
  - 5.1.1 Customer Experience

- Moustapha I. BA:

  - 3.4 Scope of this Project
  - 4.3 Data Requirements
  - 5.2 Shelf Life

- Rokhaya DIAGNE:

  - 1.2 Associated Documents
  - 3.2 Objectives of this Project
  - 5.3 Security Requirements

- Jonathan M. NDAO:

  - 1.1 Amendment History
  - 4.4 MI Reporting Requirements
  - 5.1 Volume Model
  - 5.6 Compliance
  - 5.7 System Operations

- Serigne Ahmadou Mbacke Fall:

  - 1.5 Glossary of Terms
  - 3.3 Known Business Rules
  - 5.4 Constraints

- Voluntary Contributors:
  - 5.6.2 Legal

**Version Number:** 0  
**Status:** In Progress  
**Date:** 2023-10-25

## Document Control

### 1.1 Amendment History

| Version | Date       | Author(s)        | Description of Change |
| ------- | ---------- | ---------------- | --------------------- |
| 0       | 2023-11-01 | Jonathan M. NDAO | Initial Draft         |
| 1       | 2023-11-08 | Jonathan M. NDAO | MI Reporting          |
| 2       | 2023-11-15 | Jonathan M. NDAO | Volume Model          |

### 1.2 Associated Documents

- List any documents related to this project, such as reference materials or supporting documentation.

### 1.3 Review List

- Specify the individuals or teams responsible for reviewing and providing feedback on this document.

### 1.4 Additional Distribution List

- Identify the stakeholders or teams who should receive this document apart from the core team.

### 1.5 Glossary of Terms

- Include a glossary defining any specialized terms or acronyms used in this document to ensure a common understanding.

## Purpose of this Document

- Provide a brief overview of the purpose of this document and its importance in the project.

## Introduction

### 3.1 Background

- Present the background and context of the project, including the business problem or opportunity that initiated it.

### 3.2 Objectives of this Project

- Clearly state the objectives and expected outcomes of the project to set the stage for the requirements.

### 3.3 Known Business Rules

- Document any existing business rules or regulations that the project must adhere to.

### 3.4 Scope of this Project

- Define the boundaries and limitations of the project to provide a clear understanding of what's included.

### 3.5 Exclusions from Scope

- Identify aspects that are deliberately excluded from the project scope.

## Business Requirements

### 4.1 Business Process Overview

- Offer a high-level overview of the key business processes within the project.

### 4.2 Detailed Business Requirements

- Elaborate on the specific business requirements, detailing what needs to be achieved.

### 4.3 Data Requirements

- Specify the data needed to support the business processes and requirements.

### 4.4 MI Reporting Requirements

The MI Reporting Requirements for CashBuddy are vital for providing users with in-depth insights into their financial activities. Key reporting requirements include:

- **Real-time Income and Expense Tracking**: Users should be able to track their income and expenses in real-time. This includes categorizing and subcategorizing expenses for detailed analysis.

- **Goal-setting and Progress Tracking**: CashBuddy will allow users to set financial goals, such as building an emergency fund or saving for a specific purchase. Users can track their progress towards these goals and receive notifications when milestones are reached.

- **Budgeting and Forecasting**: CashBuddy will provide budgeting and forecasting features to help users plan their finances. Users can set budgets for different categories and receive alerts when they exceed their budget. They can also forecast their income and expenses to plan for the future.

- **Interactive Charts and Visualizations**: To facilitate better financial decision-making, CashBuddy will provide interactive charts and visualizations. These will include pie charts, bar graphs, and line charts to present financial data. Users can customize these visuals to gain insights into their spending patterns, income sources, and savings trends.

- **Customizable Reports**: CashBuddy will allow users to create custom reports based on their financial data. These reports can be exported in various formats, including PDF, CSV, and Excel.

<table>
  <tr>
 <td><img src="./images/budgeting_and_forecasting.png" alt="Budgeting and Forecasting" width="300"height="200"></td>    
 <td><img src="./images/transactions.png" alt="Transactions"></td>
  </tr>
</table>

## Non-Functional Requirements

### 5.1 Volume Model

To ensure the optimal performance of CashBuddy, it's crucial to address the expected volume of data and user transactions. CashBuddy aims to support a large user base and handle significant financial data.

Specific volume-related considerations include:

- **Supporting Thousands of Concurrent Users**: CashBuddy is designed to accommodate a substantial user base. It should be capable of handling thousands of concurrent users without performance degradation.

- **Efficient Processing of High Transaction Volumes**: Given the financial nature of the application, it's essential to efficiently process a high volume of financial transactions, including income, expenses, and transfers. The system should provide rapid and accurate transaction processing.

- **Scalability**: CashBuddy should be designed with scalability in mind. As the user base grows, the system should seamlessly scale to handle the increased load while maintaining a responsive user experience.

- **Data Storage**: CashBuddy will store a large volume of financial data, including user information, transaction records, and financial reports. The system should be capable of storing and retrieving this data efficiently.

- **Data Backup and Recovery**: To protect user data, CashBuddy will implement robust data backup and recovery mechanisms. This will ensure that user data is not lost in case of unexpected events or data corruption.

- **Data Retention**: CashBuddy will retain user data for a specified period. This will allow users to access their financial records and reports at any time.

- **Data Archiving**: CashBuddy will archive user data after a specified period. This will ensure that the system's performance is not impacted by the volume of data stored.

**Estimations for a Volume Model**

If we assume that CashBuddy will have 100,000 users, each with an average of 100 transactions per month, the system will handle 10 million transactions per month. This translates to 120 million transactions per year.

If we assume that each transaction will generate 1 KB of data, the system will handle 120 GB of data per year. It's important to note that this estimation is based on assumptions and should be refined with more accurate data or research.

These estimations serve as a starting point for infrastructure planning. CashBuddy will require a robust infrastructure with sufficient storage, processing power, and scalability mechanisms to handle the expected data and transaction volumes.

#### 5.1.1 Customer Experience

- Detail the non-functional requirements related to ensuring an exceptional customer experience.

### 5.2 Shelf Life

- Define the requirements related to the lifespan or expiration of products or data.

### 5.3 Security Requirements

- Outline the security measures and requirements to protect sensitive information.

### 5.4 Constraints

- Specify any constraints or limitations that may impact the project's execution.

#### 5.5 Integrity

- Address the integrity and reliability of data, processes, and systems.

##### 5.5.1 Robustness

- Define the robustness requirements for the system's stability and resilience.

### 5.6 Compliance

- Ensure that the project adheres to relevant industry standards and regulations.

#### 5.6.1 Auditing

- Define auditing requirements to track and monitor compliance.

#### 5.6.2 Legal

- Specify legal requirements and considerations for the project.

#### 5.6.3 Internationalization

- Address internationalization requirements for global reach and adaptability.

### 5.7 System Operations

- Detail the requirements for system operations, including maintenance and support.

## Key Working Assumptions

- Enumerate any assumptions made during the project, which can impact the requirements or deliverables.

_Skip this page on purpose_

**Note:** The first draft must be available by Wednesday, 1st, 2023, before midnight.
