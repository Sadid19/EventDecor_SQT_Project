# EventDecor - Software Quality Assurance and Testing Project

## Overview

EventDecor is a proposed web-based event decoration service marketplace designed to connect clients with professional decorators in Bangladesh. The platform provides a structured and transparent process for posting event requirements, receiving quotations, comparing decorators, communicating with service providers, and submitting reviews.

This repository focuses on the **Software Quality Assurance and Testing** activities of EventDecor, including requirements analysis, test planning, test-case design, testing strategies, quality criteria, risk analysis, and QA documentation.

> **Note:** This repository contains the project's SQA and testing documentation. It does not contain the application source code.

## Problem Statement

People looking for event decoration services often rely on Facebook pages, phone calls, personal contacts, and word-of-mouth recommendations. This creates several problems:

* Lack of transparent pricing
* Difficulty comparing decorators and quotations
* Risk of fraudulent or unverified providers
* Limited exposure for small decoration businesses
* Unstructured communication
* No reliable complaint-resolution process
* Limited access to authentic reviews and portfolios

EventDecor addresses these problems through a centralized marketplace where verified decorators can compete fairly and clients can make informed decisions.

## User Roles

| Role          | Responsibilities                                                                                                            |
| ------------- | --------------------------------------------------------------------------------------------------------------------------- |
| **Client**    | Register, log in, post event requirements, compare quotations, select decorators, communicate, and submit reviews           |
| **Decorator** | Register, complete verification, maintain a portfolio, browse requirements, submit quotations, and communicate with clients |
| **Admin**     | Verify decorators, manage users and requirements, resolve complaints, monitor activity logs, and view platform analytics    |

## Core Features

* Client and decorator registration
* Email or OTP verification
* Secure login and password recovery
* Role-based access control
* Event requirement posting
* Requirement search and filtering
* Decorator portfolio management
* Structured quotation submission
* Quotation comparison
* Decorator selection
* Client-decorator communication
* Review and rating system
* Complaint and dispute management
* Admin verification and moderation
* Platform analytics and activity monitoring

## QA Project Scope

The project includes:

* A comprehensive **70-page Software Test Plan**
* **23 formal test cases** for major platform workflows
* **131 detailed registration test scenarios**
* Functional and non-functional requirements analysis
* Positive and negative test scenarios
* UI and input-validation testing
* Authentication and authorization testing
* Security and performance testing strategies
* Pass and fail criteria
* Test deliverables and responsibilities
* Testing schedule and resource planning
* Risk identification and mitigation planning

## Testing Levels

The following testing levels were defined for the project:

* **Unit Testing:** Verification of individual components and modules
* **Integration Testing:** Validation of data flow and interaction between modules
* **System Testing:** End-to-end validation of Client, Decorator, and Admin workflows
* **Performance Testing:** Evaluation of response time, stability, and scalability
* **Security Testing:** Validation of authentication, authorization, encryption, and access control
* **User Acceptance Testing:** Confirmation that the platform satisfies its business requirements

## Testing Tools and Strategy

| Tool                | Purpose                                                              |
| ------------------- | -------------------------------------------------------------------- |
| **Manual Testing**  | Functional, UI, integration, system, and acceptance testing          |
| **Selenium**        | Automation of repetitive UI workflows such as login and registration |
| **Postman**         | REST API and backend-service testing                                 |
| **JMeter**          | Load and performance testing                                         |
| **OWASP ZAP**       | Basic security and vulnerability testing                             |
| **Jira**            | Defect reporting and tracking                                        |
| **Microsoft Excel** | Test-case preparation and execution documentation                    |
| **Git and GitHub**  | Version control and document management                              |

## Major Test Scenarios

The documented test scenarios cover:

* Valid and invalid user registration
* Duplicate email and phone-number validation
* Password-strength validation
* OTP delivery, verification, expiration, and resending
* Valid and invalid login attempts
* Empty-field and input-boundary validation
* Password reset functionality
* Requirement creation and viewing
* Requirement search and filtering
* Decorator registration and verification
* Portfolio image uploading
* Quotation submission and comparison
* Decorator selection
* Client-decorator messaging
* Review and rating submission
* Complaint management
* Platform analytics
* Administrative activity logs
* Rate limiting and CAPTCHA validation
* SQL injection and XSS prevention scenarios
* Concurrent registration and database-consistency scenarios

## Quality Acceptance Criteria

The system is considered ready when:

* At least **95% of test cases pass**
* All critical business workflows work correctly
* No critical or high-severity defects remain
* Standard API responses complete within two seconds
* Database queries complete within two seconds
* No critical security vulnerabilities remain
* All User Acceptance Testing scenarios are executed
* All critical UAT issues are resolved

## Repository Contents

* `Project/EventDecor_Final.pdf` - Complete Software Test Plan and formal test cases
* `Project/Test Cases.xlsx` - Detailed registration test scenarios
* `Mid/` - Midterm assignments, Selenium IDE exercises, and course materials
* `Final/` - Final-term assignments, project templates, research materials, and course slides

## Project Status

* Requirements analysis: **Completed**
* Test planning: **Completed**
* Test-case design: **Completed**
* Risk analysis: **Completed**
* Test-execution documentation: **In Progress**

## Academic Information

* **Course:** Software Quality and Testing
* **Institution:** American International University-Bangladesh
* **Department:** Department of Computer Science
* **Semester:** Spring 2025-2026
* **Section:** B

## Contributors

* **Md. Ibtihazzaman** - 22-49153-3
* **Md. Ahasan Habib Alif** - 22-47516-2

## Industry Review

| Information      | Details                  |
| ---------------- | ------------------------ |
| **Reviewer**     | Shokhin Mazumder         |
| **Designation**  | Lead SQA Engineer        |
| **Organization** | Mir Info Systems Limited |
nt of Computer Science**
* **American International University-Bangladesh**

  
## Course Information

| Information        | Details                                                                            |
| ------------------ | ---------------------------------------------------------------------------------- |
| **Course**         | Software Quality and Testing                                                       |
| **Course Teacher** | [Dr. Abhijit Bhowmik](https://www.aiub.edu/faculty-list/faculty-profile?q=abhijit) |
| **Designation**    | Associate Professor                                                                |
| **Department**     | Department of Computer Science                                                     |
| **Faculty**        | Faculty of Science and Technology                                                  |
| **Institution**    | American International University-Bangladesh                                       |
| **Semester**       | Spring 2025-2026                                                                   |
| **Section**        | B                                                                                  |


