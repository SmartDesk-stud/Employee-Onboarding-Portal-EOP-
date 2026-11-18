# Quality and Test Plan: EOP

## 1. Quality objectives

- All must-have user stories meet their acceptance criteria.
- No open critical or high-severity defects at release.
- Uploaded documents are visible only to authorised roles.

## 2. Test approach

| Level | Who | When |
|---|---|---|
| Unit and developer checks | Developers | During each sprint |
| Functional testing | QA (Precious) | End of each sprint |
| Regression testing | QA | Before release candidate |
| Security and access checks | QA, Dev lead | Sprint 3 and Sprint 5 |
| Usability review | Product owner, sample users | Prototype and Sprint 4 |
| User acceptance testing | Product owner, sponsor | Week 9 |

## 3. Entry and exit criteria

**Entry for UAT:** all planned stories built, regression complete, no open critical defects.

**Exit for UAT:** all must-have test cases pass, no open critical or high defects, sponsor and product owner sign off.

## 4. Defect severity

| Severity | Meaning | Target |
|---|---|---|
| Critical | System unusable or data exposed | Fix immediately |
| High | Major feature broken, no workaround | Fix before release |
| Medium | Feature broken with workaround | Fix if time allows |
| Low | Cosmetic | Backlog |

## 5. Test cases

| ID | Story | Scenario | Expected result |
|---|---|---|---|
| TC-01 | US-01 | Log in with valid credentials | Lands on role-specific home page |
| TC-02 | US-01 | Log in with wrong password | Error shown, no access |
| TC-03 | US-02 | HR creates a task with due date | Task saved and listed |
| TC-04 | US-02 | HR assigns checklist to new hire | New hire sees tasks |
| TC-05 | US-03 | New hire marks task complete | Progress percentage updates |
| TC-06 | US-04 | New hire uploads a valid document | Status shows pending |
| TC-07 | US-04 | HR approves a document | Status shows approved |
| TC-08 | US-04 | HR rejects a document without a reason | System requires a reason |
| TC-09 | US-05 | Manager opens dashboard | Shows each hire with progress and overdue count |
| TC-10 | US-06 | Task becomes overdue | New hire receives a reminder |
| TC-11 | NFR-03 | New hire tries to open another hire's document | Access denied |
| TC-12 | NFR-02 | Open portal on a phone browser | Layout usable |

## 6. Test results

Record outcomes in the execution log below. [TEAM TO CONFIRM and fill with real results.]

| Test case | Date | Tester | Result | Defect ID |
|---|---|---|---|---|
| TC-01 | | Precious | | |
| TC-02 | | Precious | | |

## 7. Defect log

| Defect ID | Description | Severity | Raised by | Status | Fixed in |
|---|---|---|---|---|---|
| | | | | | |

## 8. Reviews

Pull requests are reviewed by the development lead before merging. Documentation is reviewed by the product owner at each sprint review.
