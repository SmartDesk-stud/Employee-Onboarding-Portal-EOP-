# Requirements and Product Backlog: EOP

Priorities use MoSCoW (Must, Should, Could, Won't). Story points are planning estimates agreed in sprint planning.

## 1. Functional requirements

| ID | Requirement | Priority |
|---|---|---|
| FR-01 | Users log in securely with role-based access (new hire, HR admin, manager) | Must |
| FR-02 | HR admin creates onboarding checklists from templates | Must |
| FR-03 | HR admin assigns tasks to new hires with due dates | Must |
| FR-04 | New hire sees a personal checklist and marks tasks complete | Must |
| FR-05 | New hire uploads required documents | Must |
| FR-06 | HR admin reviews, approves or rejects uploaded documents | Must |
| FR-07 | Progress dashboard for HR and managers | Must |
| FR-08 | Email or in-app notifications for new and overdue tasks | Should |
| FR-09 | Welcome page and company policy content | Should |
| FR-10 | Admin reports (completion rates, overdue tasks) | Should |
| FR-11 | Manager checklist items (e.g. set up equipment) | Could |
| FR-12 | HRIS or payroll integration | Won't (v1) |

## 2. Non-functional requirements

| ID | Requirement |
|---|---|
| NFR-01 | Works on current versions of Chrome, Edge, Firefox and Safari |
| NFR-02 | Responsive layout usable on a phone browser |
| NFR-03 | Uploaded documents stored securely and visible only to authorised roles |
| NFR-04 | Passwords never stored in plain text |
| NFR-05 | Core pages load within a few seconds on a normal connection |

## 3. User stories and acceptance criteria

**US-01 (FR-01) Log in.** As a user I want to log in so that I see only what my role allows.
- Given valid credentials, I reach my role's home page.
- Given invalid credentials, I see an error and no data.

**US-02 (FR-02, FR-03) Assign tasks.** As an HR admin I want to create a checklist and assign it to a new hire so that they know what to do.
- I can create a task with title, description and due date.
- The new hire sees the task on their dashboard after assignment.

**US-03 (FR-04) Complete tasks.** As a new hire I want to tick off tasks so that HR can see my progress.
- Marking a task complete updates my progress percentage.

**US-04 (FR-05, FR-06) Documents.** As a new hire I want to upload my documents so that I avoid paper forms; as HR I want to approve them.
- Uploads accept common file types and show status (pending, approved, rejected).
- A rejection requires a reason shown to the new hire.

**US-05 (FR-07) Progress view.** As a manager or HR admin I want a progress dashboard so that I can spot who is stuck.
- Dashboard lists each new hire with percent complete and overdue count.

**US-06 (FR-08) Notifications.** As a new hire I want reminders so that I do not miss deadlines.


## 4. Sprint allocation

| Sprint | Focus | Stories |
|---|---|---|
| Sprint 1 | Foundation | US-01 |
| Sprint 2 | Core tasks | US-02, US-03 |
| Sprint 3 | Documents | US-04 |
| Sprint 4 | Visibility | US-05, US-06 |
| Sprint 5 | Hardening | Bug fixes, content pages, reporting |

## 5. Requirements traceability

| Requirement | Story | Test cases (see `docs/08-quality-and-test-plan.md`) |
|---|---|---|
| FR-01 | US-01 | TC-01, TC-02 |
| FR-02, FR-03 | US-02 | TC-03, TC-04 |
| FR-04 | US-03 | TC-05 |
| FR-05, FR-06 | US-04 | TC-06, TC-07, TC-08 |
| FR-07 | US-05 | TC-09 |
| FR-08 | US-06 | TC-10 |
