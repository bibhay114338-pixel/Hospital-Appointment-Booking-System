This UML diagram collection presents a Hospital Appointment Booking System.This set of UML diagrams depicts the Hospital Appointment Booking System.

## Overview

In this branch, you will find the UML system design documentation of the Hospital Appointment Booking System.

The diagrams show the structure, actors, interactions and workflow of the proposed system, according to the functional and non-functional requirements identified during the requirement analysis phase.

The UML design documents are mostly created by Neharika Wagle and then reviewed by the rest of the team before adding to the main branch.

---

## UML Diagrams Included

### 1. Use Case Diagram

Use Case Diagram is used to represent the interaction between the major users and the Hospital Appointment Booking System.

The principal characters are:

* Patient
* Doctor
* Administrator

The key roles of patients are:

* Register
* Login
* Search Doctor
Limited run by the Specialization Filter Doctor for children aged 9 to 14.
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

*File:* use-case-diagram.png

---

### 2. Class Diagram

The Class Diagram shows the primary classes, attributes, operations and relationships in the proposed system.

The major classes include:

* Patient
* Doctor
* Administrator
* Appointment
* Schedule
* Specialization

The diagram depicts relationships like:

A patient may have more than one appointment.
The doctor may have more than one appointment.
A doctor may have several entries in the schedule.
A doctor is a member of a specialty.
An administrator operates doctors, appointments and scheduling.

*File:* class-diagram.png

---

### 3. Sequence Diagram

The Sequence Diagram depicts the interaction between the components of the system in the context of making appointments.

The key players are:

* Patient
* Hospital Appointment System
* Doctor/Schedule
* Appointment

The sequence which is a part of a booking is:

Patient looks for a doctor.
2. System displays matching doctors.
3. Patient selects a doctor.
4. System fetches the available appointment slots.
5. PLAYER CHOOSES SLOT.
6. System checks availability.
If slot is free, create 7. Appointment.
8. The chosen slot gets a stamp of approval.
Booking confirmation shown to the patient.

The diagram also takes into account the other scenario in which an appointment time slot is no longer available.

*File:* sequence-diagram.png

---

### 4. Activity Diagram

The Activity Diagram model shows processes a patient undergoes in the process of making an appointment.

The main activities include:

* Login
* Search Doctor
* Select Doctor
* View Available Slots
* Select Appointment Slot
* Check Slot Availability
* Book Appointment
* Confirm Appointment

Decision points are provided to deal with cases where:

Please enter a valid login.
There are no available appointment times.
One of the selected slots is no longer available.

When necessary, the user is prompted to choose a desired option.

*File:* activity-diagram.png

---

## Diagram Files

The following UML files are part of the branch:

text
design/
├── use-case-diagram.png
├── class-diagram.png
├── sequence-diagram.png
└── activity-diagram.png


---

## Relationship With Requirements

The functional requirements of the Hospital Appointment Booking System are used to develop the UML diagrams.

Examples of requirement to design traceability include:

| Requirement                              | UML Representation                       |
| ---------------------------------------- | ---------------------------------------- |
| FR-04 – Search Doctor                    | Use Case and Sequence Diagram            |
| FR-05 – Filter Doctor by Specialization  | Use Case and Class Diagram               |
Use Case, Sequence, and Activity Diagram – FR-07
| FR-08 – Book Appointment                 | All major UML diagrams                   |
| FR-09 – Prevent Duplicate Booking        | Sequence and Activity Diagram            |
| FR-12 – Cancel Appointment               | Use Case and Class Diagram               |
| FR-13 – Reschedule Appointment           | Use Case and Class Diagram               |
| FR-14 – Doctor Schedule                  | Use Case and Class Diagram               |
| FR-16 – Manage Doctors                   | Use Case and Class Diagram               |
| FR-17 – Manage Doctor Availability       | Use Case and Class Diagram               |
| FR-18 – Manage Appointments              | Use Case and Class Diagram               |

This will help keep the system design consistent to the approved system requirements.

---

## Branch Workflow

The UML diagrams are created in a separate branch from the main Project called feature branch:

feature/uml-diagrams

The GitHub workflow is:

The team has the ability to review and approve a pull request based on the UML diagrams created in the feature branch.

Once the UML diagrams are approved, the changes in the branch are merged back into the main branch.

---

## Version Control

The changes in the UML diagrams should be captured using appropriate GitHub commits.

Here are some examples of commit messages:

Add initial use case diagram.
Add system relationships to a class diagram.
Create Sequence Diagram for the Appointment Booking sequence.Create Sequence Diagram for the Appointment Booking sequence.
Click on Add appointment booking activity diagram.Click on the Add appointment booking activity diagram option.
UML diagrams should be refined after a review by the team.

---

## Responsibility

6. Take ownership of the task: Neharika Wagle
Review: Project Team

Final UML diagrams will be added to the project report and kept in the GitHub repository as part of the System Design documentation.
