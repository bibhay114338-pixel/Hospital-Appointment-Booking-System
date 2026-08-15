# Requirement Gathering Techniques

## 1. Introduction

Requirements gathering enables the identification of requirements of the stakeholders, problems that exist in the current system, and the desired features that the new system is expected to provide before the system is designed. Interviews and questionnaires are the key requirements-gathering techniques for the team in the Hospital Appointment Booking System. Where appropriate supporting techniques include observation, document analysis, and brainstorming.

The results of these activities are analysed and then translated into functional and non-functional requirements.

## 2. Interview

The aim of a semi-structured interview is to get detailed information from someone who knows the appointment management processes in a hospital or clinic, such as administrative staff, reception staff, or a healthcare professional.

The interview is on topics related to:

* Current appointment-booking procedures
Addressing the needs of clients for appointments.Meeting client needs for appointments.
* Doctor availability management
* Common scheduling problems
How to cancel or reschedule appointments.How to cancel and reschedule appointments.
* Scheduling conflicts
The doctor and administrator requirements are included.
Concerns of security and privacy
These are the improvements anticipated from a computerised system.

A semi-structured format enables the team to follow a prepared list of questions, but also to pose further questions if clarification is needed.

### Evidence

* [Interview Questions](../evidence/requirements/interview-questions.md)
* [Interview Summary](../evidence/requirements/interview-summary.md)

## 3. Questionnaire

Requirements are gathered from potential user, mainly from patients, by a questionnaire. Google Forms is used because they offer an effective way of gathering and consolidating feedback.

The questionnaire investigates:

Students will use current methods of appointment booking.Students will learn to use current booking of appointments.
Appointment bookings: difficulty scheduling appointments (P35)
Patients require an online doctor search functionality.Patients need online doctor search.
* Doctor filtering by specialization
The significance of looking at the available appointment slots
* Appointment cancellation and rescheduling
* Booking confirmation
* Preferred system features
* General usability expectations

The questionnaire includes multiple choice, yes/no options, check box, rating scale and short answer type questions.

### Evidence

* [Questionnaire Questions](../evidence/requirements/questionnaire-questions.md)
* [Questionnaire Summary](../evidence/requirements/questionnaire-summary.md)

There are also screenshots of Google Form and the summarized results saved in the evidence/requirements/ folder. Previously, personal information would be deleted from evidence before entering it into the repository.

## 4. Observation

Observation can be used to gain knowledge of the actual implementation of activities related to appointments. It focuses on:

The way patients book appointments.The process of booking appointments.
How doctors are checked available
* How appointment dates and times are assigned
How is it resolved if there are scheduling conflicts?
How to reschedule and cancel events.
How a successful appointment is notified.The way of confirming the successful appointment.

Using observation can help identify issues with workflow that might not be explicitly stated in interviews or questionnaires.

### Evidence

* [Observation Checklist](../evidence/requirements/observation-checklist.md)

If observation is not actually done, it will be recorded as a **proposed technique** and not as completed research.

## 5. Document Analysis

The relevant documents related to appointments may be consulted to determine what information needs have to be addressed by the proposed system.

Examples include:

* Patient registration forms
* Appointment forms
* Doctor schedules
* Appointment registers
* Appointment procedures

Patient information, doctor information, appointment date, time, specialization, and appointment status are some of the information that can be obtained from document analysis.

The repository will not contain patient or hospital information, which will be kept confidential.
## 6. Brainstorming

All three project team members brainstorm to share information they gather and decide on the required system requirements.

Brainstorming supports:

* Identifying system features
* Defining system actors
* Resolving unclear requirements
* Prioritizing requirements
* Defining project scope
Ensuring consistency between requirements, user stories, UML diagrams and test cases
## 7. Analysis of Findings

The system requirements are derived from the information gathered during requirement-gathering activities.

| Finding                                           | Derived Requirement                         |
| ------------------------------------------------- | ------------------------------------------- |
| Patients need to find suitable doctors.           | **FR-04:** Search Doctor                    |
| Patients want doctors grouped by specialization.  | **FR-05:** Filter Doctor by Specialization  |
| Patients need to know when doctors are available. | **FR-07:** View Available Appointment Slots |
| Patients need online appointment booking.         | **FR-08:** Book Appointment                 |
| Scheduling conflicts need to be prevented.        | **FR-09:** Prevent Duplicate Booking        |
| Patients need confirmation after booking.         | **FR-10:** Appointment Confirmation         |
| Patients need to cancel appointments.             | **FR-12:** Cancel Appointment               |
| Patients need to change appointment times.        | **FR-13:** Reschedule Appointment           |
| Doctors need access to their schedules.           | **FR-14:** Doctor Schedule                  |
| Administrators need to maintain availability.     | **FR-17:** Manage Doctor Availability       |

The results are also applied to uncover non-functional requirements such as security, usability, performance, reliability, and integrity of the data.

## 8. Requirement Validation

The project team reviews the identified requirements to make sure that they are:

* Clear and understandable
Appropriate for the project project scope
* Consistent
* Feasible
* Testable
- Appropriate for UML modeling

Requirements are also aligned with the product backlog, UML diagrams, and test cases in order to have consistency throughout the project.
## 9. Supporting Evidence

Evidence for gathering requirements is stored separately from the requirements that have been finalized.

```text
evidence/
└── requirements/
    ├── interview-questions.md
    ├── interview-summary.md
    ├── questionnaire-questions.md
    ├── questionnaire-summary.md
    ├── observation-checklist.md
    ├── google-form.png
    └── google-form-results.png
```
## 10. Conclusion

Using multiple requirement-gathering techniques provides a better understanding of stakeholder expectations and appointment-management problems. Interviews are used to gather detailed information from stakeholders and questionnaires gather feedback from prospective users. The team uses observation and document analysis to gain further understanding of the processes and brainstorm the results, which helps them examine and make sense of the findings.

The gathered results are used to draw the functional and non-functional requirements and eventually in the creation of user stories, UML diagrams, and software test cases.
