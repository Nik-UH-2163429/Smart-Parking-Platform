# HW6 – Updated Risk Register

**Project:** Smart Parking Platform  
**Date:** October 15, 2026  
**Version:** 1.2

## 1. Overview

The Smart Parking Platform Risk Register has been reviewed as part of HW6 to ensure that potential technical, schedule, financial, and organizational risks remain adequately documented.

The original register contained 12 risks. These risks have been retained, and additional proposed risks have been identified based on the updated SRS, WBS, and project management approach.

## 2. Existing Risk Register

| ID | Risk Description | Category | Probability | Impact | Owner | Response |
|---|---|---|---|---|---|---|
| R1 | Inaccurate real-time parking availability | Technical | High | Major | Development Team | Test and validate parking updates |
| R2 | Inaccurate GPS/location services | Technical | Moderate | Moderate | Development Team | Test location accuracy and provide alternatives |
| R3 | Parking sensor or data integration failure | Technical | Moderate | Major | Development Team | Test integrations early and plan backup data |
| R4 | Server downtime or performance problems | Technical | Moderate | Major | Development Team | Load testing and performance monitoring |
| R5 | Development tasks exceed estimated durations | Schedule | High | Moderate | Project Manager | Weekly progress monitoring and reprioritization |
| R6 | External parking data integration delays | Schedule | Moderate | Major | Development Team | Early integration and mock data |
| R7 | Testing and debugging exceed planned time | Schedule | Moderate | Moderate | QA / Development Team | Test continuously during development |
| R8 | Hosting and cloud costs exceed estimates | Financial | Moderate | Moderate | Project Manager | Monitor usage and control expenses |
| R9 | Parking hardware exceeds the budget | Financial | Low | Major | Project Manager | Compare alternatives and limit purchases |
| R10 | Team member becomes unavailable | People | Moderate | Major | Project Manager | Share knowledge and document work |
| R11 | Differences in technical experience slow development | People | Moderate | Moderate | Project Manager | Assign work based on skills |
| R12 | Poor communication causes missed or duplicated work | People | Moderate | Major | Entire Team | Regular meetings and GitHub updates |

The original risk owners and probability/impact classifications have been maintained.

## 3. Additional Risks Identified for HW6

| ID | Risk Description | Category | Probability | Impact | Owner | Response Strategy | Status |
|---|---|---|---|---|---|---|---|
| R13 | Unauthorized access to user or operator accounts | Security | Moderate | Major | Development Team | Implement access controls, secure authentication, and security testing | Proposed |
| R14 | Payment processing failures or duplicate transactions | Technical / Financial | Moderate | Major | Development Team | Implement transaction validation, error handling, and payment testing | Proposed |
| R15 | Third-party navigation or payment service becomes unavailable | Technical | Moderate | Moderate | Development Team | Test service failures and establish fallback procedures | Proposed |
| R16 | Transition from Trello to GitHub results in incomplete backlog tracking | Project Management | Moderate | Moderate | Project Manager | Preserve original documentation and establish consistent GitHub tracking procedures | Active – Migration underway |
| R17 | Additional WBS activities create schedule conflicts | Schedule | Moderate | Major | Project Manager | Review dependencies and adjust planned tasks where necessary | Proposed |
| R18 | Sensitive user or payment information is exposed | Security | Moderate | Major | Development Team | Protect sensitive data, restrict access, and perform security reviews | Proposed |

## 4. Risk Prioritization

The following risks warrant particular attention based on their probability, impact, or relationship to critical project requirements.

| Priority | Risk IDs | Reason |
|---|---|---|
| High | R1, R3, R4, R5, R6, R10, R12, R13, R14, R17, R18 | High probability and/or major impact |
| Medium | R2, R7, R8, R11, R15, R16 | Moderate probability and moderate impact |
| Monitor | R9 | Lower probability, but potentially major financial impact |

These priority groups are preliminary management assessments rather than the output of a numerical risk-scoring model.

## 5. Risk Monitoring Plan

The project team will review risks during weekly project updates.

The Project Manager will:

- Review risks affecting upcoming milestones.
- Track schedule and cost-related concerns.
- Confirm whether mitigation actions are being addressed.
- Update risk probability and impact when circumstances change.
- Communicate significant risks in stakeholder updates.

The Development Team will:

- Test critical technical integrations.
- Review authentication and payment security.
- Monitor issues affecting system reliability.
- Document technical risks and corrective actions.

## 6. HW6 Revision Summary

The original 12 risks were preserved and six additional proposed risks were identified.

The new risks address:
- Authentication and authorization security.
- Payment processing reliability.
- Third-party service dependencies.
- Migration of project tracking from Trello to GitHub.
- Schedule impacts from new WBS activities.
- Sensitive information protection.

The updated Risk Register now contains 18 identified risks. Existing ratings remain unchanged, while new risk ratings are preliminary assessments subject to future review.

## 7. Status

This document updates the project's risk planning baseline. It does not indicate that all mitigation activities have been completed.

Risk responses and priorities should be reviewed as the project progresses.
