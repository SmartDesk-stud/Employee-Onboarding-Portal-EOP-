# Scope Statement and Work Breakdown Structure (WBS): EOP

## 1. Scope statement

**Product description:** a web-based portal where HR assigns onboarding tasks and collects documents, new hires complete a guided checklist, and managers and HR monitor progress.

**Deliverables**

1. Requirements document and prioritised backlog
2. Google Stitch prototype
3. Working web application (new hire, HR admin and manager roles)
4. Test plan, test results and UAT sign-off
5. User guide
6. Closure report and lessons learned

**Acceptance criteria:** all must-have user stories pass UAT; no open critical or high defects; sponsor signs off.

**Exclusions:** payroll or HRIS integration, native mobile apps, multi-language, advanced analytics.

## 2. Work breakdown structure

```
1 Employee Onboarding Portal
├── 1.1 Initiation
│   ├── 1.1.1 Project charter
│   ├── 1.1.2 Business case
│   └── 1.1.3 Stakeholder register
├── 1.2 Planning
│   ├── 1.2.1 Scope statement and WBS
│   ├── 1.2.2 Requirements and backlog
│   ├── 1.2.3 Schedule and sprint plan
│   ├── 1.2.4 Resource plan and RACI
│   ├── 1.2.5 Risk register
│   ├── 1.2.6 Communication plan
│   └── 1.2.7 Quality and test plan
├── 1.3 Design
│   ├── 1.3.1 User flows
│   ├── 1.3.2 Google Stitch prototype
│   └── 1.3.3 Prototype review and approval
├── 1.4 Build
│   ├── 1.4.1 Authentication and roles
│   ├── 1.4.2 Onboarding checklist and tasks
│   ├── 1.4.3 Document upload and verification
│   ├── 1.4.4 Content and policy pages
│   ├── 1.4.5 Progress dashboard and notifications
│   └── 1.4.6 Admin reporting
├── 1.5 Test
│   ├── 1.5.1 Functional and regression testing
│   ├── 1.5.2 Defect fixing
│   └── 1.5.3 User acceptance testing
├── 1.6 Release
│   ├── 1.6.1 Deployment
│   ├── 1.6.2 User guide
│   └── 1.6.3 Handover
└── 1.7 Closure
    ├── 1.7.1 Closure report
    ├── 1.7.2 Lessons learned
    └── 1.7.3 Final sign-off
```

## 3. Scope change control

Any change to scope is logged in `docs/11-change-and-issue-log.md`, assessed for impact on schedule and quality, and approved by the sponsor before the backlog is updated.
