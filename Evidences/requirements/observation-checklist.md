# Observation Checklist

### Observation Information

| Item             | Details                                                         |
| ---------------- | --------------------------------------------------------------- |
| Observer         | Bibhay Aryal                                                    |
| Process          | Hospital Appointment Booking Process                            |
| Observation Type | Simulated workflow observation                                  |
Task Objectives | Locate workflow activities, issues and system needs |
| Data Type        | Simulated academic data                                         |

> Note: This checklist is for illustrative purposes in a typical hospital context for academic requirement analysis.
## Observation Checklist

| No. | Activity / Condition                                | Observed | Finding                                                    |
| --: | --------------------------------------------------- | :------: | ---------------------------------------------------------- |
|   1 | Patient contacts reception for an appointment       |     ✓    | Patients depend heavily on reception staff.                |
|   2 | Patient provides basic information                  |     ✓    | Patient details are required during booking.               |
|3|Receptionist recognizes the requested doctor/department   | ✓   | Doctor and specialization information is required.   |
|   4 | Receptionist checks doctor availability             |     ✓    | Availability checking is a major booking step.             |
|   5 | Available date and time are communicated to patient |     ✓    | Patients need access to available slots.                   |
|   6 | Patient selects a suitable appointment time         |     ✓    | The system should allow slot selection.                    |
|   7 | Appointment is recorded                             |     ✓    | Appointment records must be created and maintained.        |
|   8 | Scheduling conflict is checked                      |     ✓    | Duplicate booking must be prevented.                       |
|   9 | Patient receives appointment information            |     ✓    | Booking confirmation is required.                          |
|  10 | Cancellation request is processed                   |     ✓    | Cancellation functionality is required.                    |
|11|If a slot is cancelled it is again available to schedule an appointment. |     ✓    |      Must be able to have appointment records be synchronised. |
|  12 | Rescheduling request is processed                   |     ✓    | Rescheduling functionality is required.                    |
|  13 | Doctor schedule is updated                          |     ✓    | Doctors need accurate schedules.                           |
14 | Updating doctor availability by admin staff     |     ✓    | Doctor availability management by admin staff is required.         |
|  15 | Patient information requires controlled access      |     ✓    | Security and authorization are required.                   |


## Problems Identified

The simulated workflow observation revealed that there are a number of potential issues:

Insufficient ability to communicate with others by speaking and listening.
* Lack of ability to quickly identify the availability of teachers and doctors
Potential scheduling problems.
This indicates the manual effort that is needed for cancellations.
They will also have to use manual effort to reschedule.
* Not adhering to doctor's appointments
The following are examples of delays in communicating appointment information:
Some risk of inconsistent appointment records.Some risk of inconsistent appointment records.


## Requirements Derived from Observation

| Observation                                             | Requirement                              |
| ------------------------------------------------------- | ---------------------------------------- |
| Patients depend on reception for doctor information.    | FR-04 — Search Doctor                    |
| Specialization information is required.                 | FR-05 — Filter Doctor by Specialization  |
|Availability will need to be validated before booking, Appointment Slots.| FR-07 — View|
| Appointments need to be created electronically.         | FR-08 — Book Appointment                 |
| Scheduling conflicts must be prevented.                 | FR-09 — Prevent Duplicate Booking        
Information about appointments should be confirmed.| FR-10 - Appointment|
| Cancellation changes availability.                      | FR-12 — Cancel Appointment               |
| Appointment times may need to be changed.               | FR-13 — Reschedule Appointment           |
| Doctors need updated schedules.                         | FR-14 — Doctor Schedule                  |
|Manage Doctor Availability — Administrators maintain doctor availability.| FR-17 - Manage Doctor Availability|
|All information about an appointment should be consistent.| NFR-09 - Data Integrity|

## Observation Conclusion

The simulated observation illustrates that appointments involves multiple associated activities such as: doctor selection, checking availability, selecting an appointment slot, booking an appointment, confirming, and cancelling and rescheduling.

The results have indicated the necessity of a comprehensive appointment management system to decrease the manual efforts and ensure proper scheduling of doctors and appointments.
