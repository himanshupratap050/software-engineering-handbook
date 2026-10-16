# Semester Project: MediSlot

**Full name:** MediSlot — Hospital Appointment and Records Management System
**Course:** Software Engineering (SET/CS/BT/C503), HNBGU, 5th semester
**Author:** Himanshu Pratap

---

## 1. Problem Statement

Many hospitals and clinics still manage appointments through phone calls and paper registers. Patients wait in long queues, doctors face double bookings, and patient records are scattered and easy to lose. **MediSlot** is a web-based system that lets patients book, reschedule and cancel appointments online, lets doctors manage their schedules and visit records, and gives the hospital administration control over doctors, departments, fees and reports.

## 2. Why This Project (for Software Engineering)

It is close to a real industry system and naturally exercises every unit of the syllabus:

| Syllabus area | Where MediSlot uses it |
|---|---|
| Process models | Incremental delivery in 3 increments |
| Requirements and SRS | Multiple user roles, functional and non-functional requirements |
| DFD and ERD | Booking flow, patient records, billing data |
| Decision tables | Cancellation and refund rules, consultation fee rules |
| Design and coupling/cohesion | Modules: appointment, doctor, patient, billing, notification |
| Metrics and COCOMO | Size estimate from function points, effort and schedule |
| Cyclomatic complexity | Slot allocation / conflict check module |
| Testing | Boundary value analysis on slot times and age, path testing on booking logic |
| Maintenance and SCM | Change requests (new department, new payment mode), Git version control |

## 3. Users (Actors)

| Actor | Main goals |
|---|---|
| Patient | Register, search doctors, book/reschedule/cancel, view history and bills |
| Doctor | Set availability, view daily schedule, add consultation notes and prescriptions |
| Receptionist | Book walk-in appointments, handle check-in |
| Admin | Manage doctors, departments, fees, users; view reports |

## 4. Scope

**In scope**
- User registration, login and role-based access control
- Doctor search by department and availability
- Appointment booking with slot conflict prevention
- Reschedule and cancel with refund rules
- Patient visit history and prescription notes
- Billing and payment status (online payment through a mock gateway)
- Email/SMS-style notifications (simulated)
- Admin dashboard and basic reports
- Audit log of important actions

**Out of scope (for this semester)**
- Real payment gateway integration
- Insurance claim processing
- Video consultation
- Mobile native apps

## 5. Key Functional Requirements (preview, full list goes in the SRS)

1. A patient can create an account and log in securely.
2. A patient can view available slots of a doctor for a chosen date.
3. The system must not allow two appointments for the same doctor and slot.
4. A patient can cancel an appointment; the refund depends on how early the cancellation is made.
5. A doctor can mark a visit as completed and add notes.
6. An admin can add, edit or deactivate doctors and departments.
7. The system sends a confirmation and a reminder for every appointment.

## 6. Key Non-Functional Requirements (preview)

| Quality | Target (example, refine later) |
|---|---|
| Usability | A new patient books an appointment in under 3 minutes |
| Reliability | Availability of at least 99 % during hospital hours |
| Security | Role-based access, hashed passwords, patient data visible only to authorised users |
| Performance | Slot search response within 2 seconds for normal load |
| Maintainability | Modular design so a new department or payment mode needs minimal change |
| Portability | Works on current versions of Chrome, Edge and Firefox |

## 7. Planned Increments (Incremental Model)

| Increment | Features |
|---|---|
| 1 (Core) | Registration, login, doctor listing, slot-based booking |
| 2 (Extended) | Cancel/reschedule with refund rules, doctor notes, billing |
| 3 (Final) | Notifications, admin reports, audit log, hardening and testing |

## 8. Deliverables Tracker

| # | Deliverable | When | Status |
|---|---|---|---|
| 1 | [Process model selection](01-process-model-selection.md) | After Unit 1 | ⬜ |
| 2 | [Feasibility study and SRS](02-feasibility-and-srs.md) | After Unit 2 (requirements) | ⬜ |
| 3 | [DFD, ERD and decision tables](03-dfd-erd-decision-tables.md) | After Unit 2 (modeling) | ⬜ |
| 4 | [Design document](04-design-document.md) | After Unit 2 (design) | ⬜ |
| 5 | [Metrics and estimation](05-metrics-and-estimation.md) | After Unit 3 | ⬜ |
| 6 | [Test plan and test cases](06-test-plan-and-test-cases.md) | After Unit 4 | ⬜ |
| 7 | [Maintenance and SCM plan](07-maintenance-and-scm-plan.md) | After Unit 5 | ⬜ |

## 9. Notes

- This is a software engineering project: marks come mainly from the **documents and models**, not from the amount of code. A working prototype of the core booking flow is enough to demonstrate the design.
- Technology stack is decided later; the SE deliverables do not depend on it.