# Test Plan

**Project:** OrangeHRM Demo Application  
**Company:** QualiSphere Technologies  
**Version:** 1.0  
**Prepared By:** QualiSphere Technologies  
**Date:** 28 June 2026

---

# Document Information

| Version | Author | Date | Status |
|----------|--------|------|--------|
| 1.0 | QualiSphere Technologies | 28-Jun-2026 | Draft |

---

# Table of Contents

1. Introduction
2. Project Overview
3. Objectives
4. Scope
5. Test Items
6. Features to be Tested
7. Features Not to be Tested
8. Test Environment
9. Test Schedule
10. Test Deliverables
11. Test Resources
12. Entry Criteria
13. Exit Criteria
14. Defect Management
15. Risks & Mitigation
16. Approval

---

# 1. Introduction

This Test Plan defines the scope, objectives, resources, schedule, and deliverables for testing the OrangeHRM Demo Application.

It serves as the primary planning document for all testing activities performed by QualiSphere Technologies.

---

# 2. Project Overview

OrangeHRM is a Human Resource Management System (HRMS) used to manage employees, leave requests, recruitment, administration, and organizational information.

The objective of testing is to ensure the application functions correctly, meets business requirements, and is suitable for release.

---

# 3. Objectives

The objectives of this test plan are to:

- Verify application functionality.
- Validate business requirements.
- Detect and report defects.
- Improve software quality.
- Support User Acceptance Testing (UAT).
- Provide confidence for production release.

---

# 4. Scope

## In Scope

- Login
- Logout
- Dashboard
- Employee Management
- User Management
- Leave Management
- Recruitment
- Search Functionality

## Out of Scope

- Performance Testing
- Security Testing
- Accessibility Testing
- Mobile Testing
- Localization Testing

---

# 5. Test Items

The following application modules will be tested:

| Module | Description |
|---------|-------------|
| Login | User authentication |
| Dashboard | Landing page and widgets |
| PIM | Employee Information Management |
| Leave | Leave application and approval |
| Recruitment | Candidate management |
| Admin | User and role management |

---

# 6. Features to be Tested

The following functionality will be validated:

- User Login
- User Logout
- Password Validation
- Navigation
- Search
- Employee Creation
- Employee Update
- Employee Deletion
- Leave Application
- Leave Approval
- User Management
- Form Validation
- Error Messages
- Session Timeout
- Role-Based Access Control

---

# 7. Features Not to be Tested

The following areas are excluded from this testing cycle:

- Performance
- Load Testing
- Security Penetration Testing
- Accessibility Compliance
- Browser Compatibility beyond Chrome
- Mobile Responsiveness

---

# 8. Test Environment

| Component | Details |
|------------|---------|
| Application | OrangeHRM Demo |
| Browser | Google Chrome (Latest) |
| Operating System | Windows 11 |
| Database | Demo Database |
| Test Data | Demo Users |
| API Tool | Postman |
| Version Control | GitHub |

---

# 9. Test Schedule

| Activity | Duration |
|-----------|----------|
| Requirement Analysis | 1 Day |
| Test Planning | 1 Day |
| Test Scenario Preparation | 2 Days |
| Test Case Design | 3 Days |
| Test Data Preparation | 1 Day |
| Test Execution | 5 Days |
| Defect Retesting | 2 Days |
| Regression Testing | 2 Days |
| Test Closure | 1 Day |

---

# 10. Test Deliverables

The following deliverables will be produced:

- Test Strategy
- Test Plan
- Test Scenarios
- Test Cases
- Requirements Traceability Matrix (RTM)
- Test Data
- Defect Report
- Test Execution Report
- Test Summary Report
- Release Recommendation

---

# 11. Test Resources

| Role | Responsibility |
|------|----------------|
| QA Lead | Overall Test Management |
| QA Engineer | Test Design & Execution |
| Business Analyst | Requirement Clarification |
| Developer | Defect Resolution |
| Project Manager | Project Coordination |

---

# 12. Entry Criteria

Testing will commence when:

- Requirements are approved.
- Test environment is available.
- Application build is deployed.
- Test data is prepared.
- Test cases are reviewed and approved.

---

# 13. Exit Criteria

Testing will be completed when:

- 100% of planned test cases are executed.
- All Critical defects are closed.
- High-priority defects are resolved or accepted.
- Regression testing is completed.
- Test Summary Report is approved.

---

# 14. Defect Management

## Defect Lifecycle

```text
New
 ↓
Assigned
 ↓
In Progress
 ↓
Fixed
 ↓
Ready for Retest
 ↓
Closed
```

### Severity

| Severity | Description |
|----------|-------------|
| Critical | System unusable |
| High | Major functionality affected |
| Medium | Partial functionality affected |
| Low | Cosmetic issue |

### Priority

| Priority | Description |
|----------|-------------|
| High | Immediate attention |
| Medium | Fix before release |
| Low | Can be deferred |

---

# 15. Risks & Mitigation

| Risk | Impact | Mitigation |
|------|--------|------------|
| Requirement Changes | High | Frequent review meetings |
| Environment Downtime | Medium | Validate environment before execution |
| Test Data Issues | Medium | Prepare realistic test data |
| Delayed Bug Fixes | High | Daily defect triage meetings |

---

# 16. Approval

| Name | Role | Status |
|------|------|--------|
| QA Lead | QualiSphere Technologies | Pending |
| Project Manager | Client | Pending |
| Business Owner | Client | Pending |

---

# Test Execution Metrics

The following metrics will be tracked during execution:

| Metric | Description |
|--------|-------------|
| Total Test Cases |
| Executed Test Cases |
| Passed Test Cases |
| Failed Test Cases |
| Blocked Test Cases |
| Not Executed Test Cases |
| Open Defects |
| Closed Defects |
| Defect Density |
| Test Coverage (%) |

---

# Exit Report

At the completion of testing, a Test Summary Report will include:

- Test execution statistics
- Defect summary
- Outstanding issues
- Risks
- Lessons learned
- Go/No-Go recommendation

---

# About QualiSphere Technologies

**QualiSphere Technologies** provides professional:

- Software Testing
- API Testing
- Telecom OSS/BSS Testing
- Business Analysis
- QA Consulting
- QA Training
- Resume & Career Services

📧 **Email:** qualispheretech@gmail.com

**Tagline:** *Transforming Quality into Confidence.*
