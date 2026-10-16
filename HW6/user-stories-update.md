# HW6 – Updated User Stories

**Project:** Smart Parking Platform  
**Date:** October 15, 2026  
**Version:** 1.2

## 1. Overview

The Smart Parking Platform follows an Agile development approach in which project requirements are organized into user stories.

Each user story describes a desired feature from the perspective of a driver, parking operator, or system administrator.

The product backlog currently contains 45 items organized into four categories:

- Login: 5 items
- User and Operator UI: 15 items
- User and Operator Backend Processes: 15 items
- User and Operator Reporting: 10 items

The following user stories represent the primary functional requirements identified in the Software Requirements Specification (SRS). They provide a requirements-level reference for maintaining the existing Trello backlog.

## 2. Driver User Stories

| ID | User Story | Priority |
|---|---|---|
| US-01 | As a driver, I want to create an account so that I can access the Smart Parking Platform. | High |
| US-02 | As a driver, I want to log in securely so that my personal information remains protected. | High |
| US-03 | As a driver, I want to reset my password so that I can recover access to my account. | High |
| US-04 | As a driver, I want to search for parking facilities so that I can find convenient parking locations. | High |
| US-05 | As a driver, I want to view real-time parking availability so that I can avoid full parking facilities. | High |
| US-06 | As a driver, I want to view parking facilities on an interactive map so that I can compare nearby options. | High |
| US-07 | As a driver, I want to view parking facility details so that I can make an informed parking decision. | High |
| US-08 | As a driver, I want navigation assistance so that I can reach my selected parking facility. | Medium |
| US-09 | As a driver, I want to save and update payment methods so that I can pay for parking conveniently. | High |
| US-10 | As a driver, I want to pay digitally so that I do not need to use cash. | High |
| US-11 | As a driver, I want to view and download receipts so that I can maintain payment records. | High |
| US-12 | As a driver, I want to receive parking notifications so that I can stay informed about my parking session. | Medium |

## 3. Parking Operator User Stories

| ID | User Story | Priority |
|---|---|---|
| US-13 | As a parking operator, I want to create and manage an account so that I can access facility management tools. | High |
| US-14 | As a parking operator, I want to add, edit, and remove parking facilities so that facility information remains accurate. | High |
| US-15 | As a parking operator, I want to update parking availability so that drivers receive accurate information. | High |
| US-16 | As a parking operator, I want to monitor occupancy so that I can manage facility capacity. | High |
| US-17 | As a parking operator, I want to manage parking prices so that rates reflect facility policies. | High |
| US-18 | As a parking operator, I want to view occupancy analytics so that I can identify parking usage trends. | Medium |
| US-19 | As a parking operator, I want to generate financial reports so that I can review facility revenue. | Medium |
| US-20 | As a parking operator, I want to export reports so that I can maintain business records. | Medium |

## 4. System Administrator User Stories

| ID | User Story | Priority |
|---|---|---|
| US-21 | As a system administrator, I want to manage user accounts so that I can maintain platform access and security. | High |
| US-22 | As a system administrator, I want to manage user permissions so that users only access authorized functionality. | High |

## 5. Sprint 1 User Stories

Sprint 1 focuses on user and operator authentication, account creation, and initial dashboard access.

The previously defined Sprint 1 backlog includes:

1. User Account Registration
2. Operator Account Registration
3. User Login
4. Operator Login
5. Forgot / Reset Password
6. User Authentication Service
7. Operator Authentication Service
8. Account Creation API
9. Password Reset Service
10. User Dashboard
11. Operator Dashboard

These activities support the authentication and account setup requirements described in the updated SRS.

### Sprint 1 Acceptance Criteria

The following criteria are proposed for evaluating Sprint 1 work:

- Users can submit valid account registration information.
- Operators can register and authenticate using their assigned account type.
- Invalid login credentials are rejected.
- Registered users can initiate password recovery.
- Authenticated drivers can access the driver dashboard.
- Authenticated operators can access the operator dashboard.
- Users cannot access protected dashboard features without authentication.

## 6. Requirements Traceability

| User Stories | Related SRS Requirements | WBS Section |
|---|---|---|
| US-01 to US-03 | FR-01 to FR-03 | 1.1 Authentication |
| US-04 to US-08 | FR-04 to FR-08 | 1.3 Dashboards |
| US-09 to US-11 | FR-09 to FR-10 | 1.2 Account Setup / 1.4 Payment Processing |
| US-12 | FR-11 | 1.3 Dashboards |
| US-13 to US-17 | FR-02, FR-12, FR-13 | 1.2 Account Setup / 1.3 Dashboards |
| US-18 to US-20 | FR-14 | 1.5 Reporting |
| US-21 to US-22 | FR-15 | Administrative Requirements |

## 7. Updates for HW6

The user story documentation has been expanded to:

- Organize user stories by stakeholder role.
- Connect user stories to the updated SRS.
- Identify high- and medium-priority requirements.
- Establish proposed Sprint 1 acceptance criteria.
- Provide traceability between user stories and WBS components.

The 22 user stories in this document summarize major system capabilities and do not replace the 45 individual Trello backlog items.

## 8. Future Maintenance

User stories and acceptance criteria should be reviewed as development progresses. Changes to requirements should also be reflected in the Trello backlog, sprint plans, and SRS.
