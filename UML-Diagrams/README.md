# UML Diagrams – Hospital Appointment Booking System

## Overview

This branch is used for the system design documentation of the Hospital Appointment Booking System for UML.

The diagrams show the structure of the proposed system, the actors, interactions, and workflow of the system, as identified from the functional and non-functional requirements in the requirement analysis phase.

The UML design is mostly created by **Neharika Wagle** and reviewed by other members of the team before being pushed back into the `main` branch.

## UML Diagrams Included

### 1. Use Case Diagram

The Use Case Diagram shows the relations between the major actors and the Hospital Appointment Booking System.

The main actors are:

* Patient
* Doctor
* Administrator

The following are the main functions for a patient:

* Register
* Login
* Search Doctor
Filter Doctor / Specialization
* View Doctor Availability
* Book Appointment
* View Appointments
* Cancel Appointment
* Reschedule Appointment
* Logout

Doctor functions include:

* Login
* View Appointment Schedule
* View Appointment Details
* Logout

Administrator functions include:

* Login
* Manage Doctors
* Manage Doctor Availability
* Manage Appointments
* Logout

**File:** `Design/Usecase.png`

### 2. Class Diagram

Class Diagram is the main classes, attributes, operations and relationships of the proposed system.

The major classes include:

* Patient
* Doctor
* Administrator
* Appointment
* Schedule
* Specialization

The diagram illustrates relationships like:

A patient may have more than one appointment.
A physician may have more than one appointment.
A doctor may have more than one schedule entry.
A specialization is composed of a doctor.
* The administrator is responsible for doctors, scheduling and appointments.

**File:** Design/ClassDiagram-Final.png


### 3. Sequence Diagram

The Sequence Diagram shows the interaction among the components of the system in the process of booking an appointment.

The main participants include:

* Patient
* Hospital Appointment System
* Doctor/Schedule
* Appointment

The booking process consists of the following:

1. Patient searches for a doctor.
When you click the "Show Matching Doctors" button, the system will show you matching doctors.
3. Doctor is elected.
The system will fetch the available appointment slots.
5. Patient chooses a slot.
6. System checks availability.
If the slot is available, create an appointment.
8. Selected slot gets marked as booked.
9. Booking confirmation is displayed to the patient.

The diagram also takes into account the other scenario if the selected time window becomes unavailable.

**File:** Design/SequenceDiagram-Final.png

### 4. Activity Diagram

The Activity Diagram is a representation of the workflow followed by a patient to book an appointment.

The main activities include:

* Login
* Search Doctor
* Select Doctor
* View Available Slots
* Select Appointment Slot
* Check Slot Availability
* Book Appointment
* Confirm Appointment

To deal with situations where:

User name and password are incorrect.
* No appointment slots are available.
Selected slot becomes unavailable.

When necessary, the user is directed to choose another option available.

**File:** Design/Activity-Final.png

## Diagram Files

The following UML files are in the branch:

```text
design/
├── use-case-diagram.png
├── class-diagram.png
├── sequence-diagram.png
└── activity-diagram.png
```

## Relationship With Requirements

The functional requirements of the Hospital Appointment Booking System are used to create the UML diagrams.

The requirement-to-design traceability can be implemented through examples such as:

| Requirement                              | UML Representation                       |
| ---------------------------------------- | ---------------------------------------- |
| FR-04 – Search Doctor                    | Use Case and Sequence Diagram            |
| FR-05 – Filter Doctor by Specialization  | Use Case and Class Diagram               |
| FR-07 - View Available Appointment Slots | Use Case, Sequence and Activity Diagram|
| FR-08 – Book Appointment                 | All major UML diagrams                   |
| FR-09 – Prevent Duplicate Booking        | Sequence and Activity Diagram            |
| FR-12 – Cancel Appointment               | Use Case and Class Diagram               |
| FR-13 – Reschedule Appointment           | Use Case and Class Diagram               |
| FR-14 – Doctor Schedule                  | Use Case and Class Diagram               |
| FR-16 – Manage Doctors                   | Use Case and Class Diagram               |
| FR-17 – Manage Doctor Availability       | Use Case and Class Diagram               |
| FR-18 – Manage Appointments              | Use Case and Class Diagram               |

This will help in maintaining consistency of the system design with the approved system requirements.


## Branch Workflow

The UML diagrams are created independently of the project, in the feature branch:

`feature/uml-diagrams`

The GitHub workflow is:

The feature is moved from `feature/uml-diagrams` to **Pull Request** and then to **Team Review** and then to **Approval** and finally to `main`.

Once the UML diagrams are approved, the changes made in the branch are merged into the `main` branch.

## Version Control

Meaningful commits should be made in the GitHub to document changes to the UML diagrams.

Some examples of messages for commits are:

* Click on `Add initial use case diagram`:
* Click on `Add initial use case diagram`:
* `Add system relationships to class diagram`.
* Note: `Add the Appointments Book Sequence Diagram`.
* Select `Add appointment booking activity diagram`.
* Click on `Add appointment booking activity diagram`.
* Ater having a team discussion, update the UML diagrams: `Refine UML diagrams after team review`


## Responsibility

Targeted final support has been provided for this by Neharika Wagle.

**Review:** Project Team

The final UML diagrams will be part of the project report and will be stored in the GitHub repository as part of the System Design documentations.

