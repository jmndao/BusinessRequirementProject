# Project Name: Business Requirement Document (BRD)

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

- Serigne Ahmadou Mbacke Fall:

  - 1.5 Glossary of Terms
  - 3.3 Known Business Rules
  - 5.4 Constraints

- Voluntary Contributors:
  - 5.6 Compliance
  - 5.7 System Operations
  - 5.6.2 Legal

**Version Number:** 0  
**Status:** In Progress  
**Date:** 2023-10-25

## Document Control

### 1.1 Amendment History

- Document any changes, revisions, or amendments to this document.

### 1.2 Associated Documents

- List any documents related to this project, such as reference materials or supporting documentation.

### 1.3 Review List

- Specify the individuals or teams responsible for reviewing and providing feedback on this document.

### 1.4 Additional Distribution List

- Identify the stakeholders or teams who should receive this document apart from the core team.

### 1.5 Glossary of Terms

- Transfer: The action of moving funds from one user's account to another within the mobile cash app.
- Recipient: The user who receives funds in a money transfer transaction.
- Sender: The user who initiates and sends money in a transfer transaction.
- Transaction Fee: The charge or cost associated with using the app for certain transactions.
- Two-Factor Authentication (2FA): A security method that requires users to provide two forms of identification to access their accounts, enhancing security.
- Balance: The amount of money in a user's account at any given time.
## Purpose of this Document

- Provide a brief overview of the purpose of this document and its importance in the project.

## Introduction

### 3.1 Background

- Present the background and context of the project, including the business problem or opportunity that initiated it.

### 3.2 Objectives of this Project

- Clearly state the objectives and expected outcomes of the project to set the stage for the requirements.

### 3.3 Known Business Rules

- AML/CFT Regulations: The mobile cash app must comply with Anti-Money Laundering (AML) and Countering the Financing of Terrorism (CFT) regulations, including customer identification and reporting suspicious transactions.
- Daily Transaction Limit: The app enforces a daily transaction limit for users to prevent fraudulent or excessive transactions.
- Transaction Verification: Before completing a transfer, users must verify the transaction with a secure method (e.g., PIN, fingerprint, or facial recognition).
- User Authentication: All users must complete identity verification when registering for the app to ensure the security of financial transactions.
- Fraud Detection: The app includes fraud detection algorithms to identify and block suspicious or potentially fraudulent transactions.
- Cross-Border Transfers: International money transfers are subject to currency conversion rates and may incur additional fees.
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

To support the business processes and requirements of our app. we will need various types of data. Here's a breakdown of the essential data elements:

#### 4.3.1 User Data
- **User profiles**: Name, email. username, profile picture, address
- **Authentification data**: Encrypted passwords, security questions, two-factor authentication settings.
- **Financial goals and preferences**: saving goals, investments preferences

Theses provide the data we need to display right information on the page depending on the user.

#### 4.3.2 Financial Account Data
- **Bank and financial institution account information**: account numbers, account names, financial institution names
- **Transaction data**: transaction data, transaction amount, description, category, payment method.
- **Balances**: Current account balances

Theses allows to link the financial account with the app so that the user may transfert money from his bank account to the app.

#### 4.3.3 Budget and Expense Data
- **Budget details**: budget name, start date, end date, total budget amount
- **Expense data**: Date, amount, category, payee, notes, receipts
- **Budget tracking**: Expenses allocated to budgets, remaining budget amount.

#### 4.3.4 Goal Data
- **Financial goals**: goal name, target amount, target date, category.
- **Goal tracking**: Progress towards goals, contributions made

#### 4.3.5 Security and Authentication Data
- **User authentication logs**: login and logout times, IP addresses, device information
- **Security event logs**: failed login attempts, password change history

#### 4.3.6 Notification and Communication Data:
- **Notification preferences**: user settings for receiving alerts, reminders, and notifications.
- **In-app messages**: communication history with users, including messages sent and received.

#### 4.3.7 Third-Party Data
- **Data from third-party services**: payment transaction data, credit scores, investment portfolio details

#### 4.3.8 Localization Data
- **Language preferences**: user-selected language for app interface and content
- **Regional preferences**: user-selected currency, date format, time zone.

#### 4.3.9 App Usage Data
- **User interactions**: user activity within the app, such as clicks, page views, and feature usage.
- **Analytics data**: user engagement metrics, app performance, and error logs.

Theses help to know where to place adds for instance.

#### 4.3.10 Historical Data
- **Historical transaction and account data**: transaction history, past account balances
- **Historical budget and expense data**: Past budgets, expenses, and their associated data

Theses might help the user to compare his expenses.

#### 4.3.11 Legal and Compliance Data
- **User consent records**: records of users accepting terms of use and privacy policies
- **Compliance logs**: records of actions taken to ensure compliance with financial regulations.

Knowing the records of users accepting terms of use and privacy policies help the administration of the app to know the number of active users.

#### 4.3.12 Support and Feedback Data
- **User support interactions**: records of user support requests, feedback, and resolutions
- **User feedback**: user suggestions, complaints, and feedback regarding the app's functionality

These data will help to improve the app by giving the user what he wants.

### 4.4 MI Reporting Requirements

- Describe the requirements for management information reporting and analysis.

## Non-Functional Requirements

### 5.1 Volume Model

- Address the expected volume of data, users, or transactions, with a focus on maintaining optimal performance.

#### 5.1.1 Customer Experience

- Detail the non-functional requirements related to ensuring an exceptional customer experience.

### 5.2 Shelf Life

- Define the requirements related to the lifespan or expiration of products or data.

### 5.3 Security Requirements

- Outline the security measures and requirements to protect sensitive information.

### 5.4 Constraints

- Budget Constraints: The project operates with a predefined budget for development and maintenance, limiting the allocation of resources.
- Compliance Deadlines: The app must meet regulatory compliance deadlines, and any delays can result in legal consequences.
- Third-Party Integration: The integration of external payment systems and financial institutions may be subject to their operational constraints and APIs.
- Scalability: The app's infrastructure must support scalability to accommodate increased user activity and transaction volumes.
- Security and Data Protection: Strict security measures and encryption must be implemented to protect user data and prevent data breaches.
- User Support and Response Times: The app must adhere to specific response time constraints for addressing user support requests and resolving issues.
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
