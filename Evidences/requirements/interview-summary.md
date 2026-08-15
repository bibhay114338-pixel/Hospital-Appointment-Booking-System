# Interview Summary
## Hospital Appointment Booking System
### Interview Information

| Item | Details |
|---|---|
| Interviewer | Bibhay Aryal |
| Participant | Participant A |
Participant's role | Reception staff of the hospital |
| Method | Semi-structured interview |
| Duration | 15 minutes |
Objective | To find out the requirement of Hospital Appointment Booking System |
Data Type | Simulated for academic project |

This interview is a mock-up of a stakeholder interview that was developed for the academic Hospital Appointment Booking System project.

### Q1. What is the process for patients to schedule appointments?

**Response:**  
The majority of patients call the reception or head to the hospital in person. Reception staff must check the doctor's availability and manually book in a time for them.

### Q2. What details do you need to include when making an appointment?

**Response:**  
Typically, we need the patient's name, phone number, preferred doctor or department, appointment date and a few key details regarding the reason for the appointment.

### Q3. What are the common issues that occur in the existing appointment process?

**Response:**  
The main issues are telephone congestion, patients not knowing when the doctors are available, scheduling difficulties, and the time receptionists spend on checking schedules.

### Q4. How does a patient find out which dotor is available?

**Response:**  
Typically a person would need to call the reception. Patients would be helped if they could look up the doctors and view their availability.

### Q5. What is the current situation with doctors' availability?

**Response:**  
Doctor schedules are established by staff in the Reception to match the working days and hours of the doctor. If a doctor changes his/her schedule, then the appointments available should be updated as well.

### Q6. What should be done if two patients are requesting the same appointment time?

**Response:**  
The first person to be diagnosed with the disease gets the appointment. The second patient has to select another time. An online system should not allow double confirmations of the same slot.

### Q7. What happens if an appointment is cancelled?

**Response:**  
Typically patients call reception and request to cancel. Once cancelled, this appointment time is freed up for another patient.

### Q8. How do appointments get reschedueled?

**Response:**  
Yes. If another appointment time is available, then it is okay if the patient reschedules, this will alleviate the workload of the reception staff.

### What should be visible to doctors with regard to their appointments?

**Response:**  
The doctor should be able to see the list of the appointments, their time and information about the patients and the state of the appointment.

### Q10. What should be provided to patients on completing an appointment?

**Response:**  
They should be provided with a clear confirmation that displays the doctor's name, date, time and booking.

### Q11. What should be the roles of administrators in hospitals?

**Response:**  
Doctors should be managed, available and their appointment records, managed by administrator. They should also be able to change information when schedules change.

### Q12. What are the security/privacy issues that need to be addressed?

**Response:**  
Each user is required to have an account. Doctors and administrators should only see information relevant to their duties, whereas patients should only see information relevant to their appointments.

### Q13. What makes the system easy to use by the patients?

**Response:**  
The system should have simple navigation. Patients should be able to locate the doctor, choose the field of specialization, view the availability of the doctor and easily book or manage their appointments with minimal steps.

### Q14. What would be helpful to patients for an online appointment system?

**Response:**  
The key benefit would be a decrease in manual appointment work. The patient would be able to schedule their own appointments, and the hospital could keep the appointments more organized and find fewer duplicate bookings.

# Key Findings

Based on the simulated interview, the following significant findings were obtained:

1. For patients, online access to appointment services are needed.
2. Patients should have access to Doctors' search.
3. Physicians' names should be searchable by specialty.
4. Available appointment dates and times should be displayed.
5. The system should not allow double bookings of appointments.
6. Patients should be able to cancel appointments.
7. Patients should have the ability to reschedule appointments.
8. Confirmation should be provided upon booking.
9. Doctors must have their schedules.
10. Doctor management is required for administrators, as well as doctor availability and appointments.
11. Information about patient and appointments should be limited.
12. The system must be easy to use and have an intuitive interface.

Requirements that are derived from interviews.

| Finding | Derived Requirement |
|---|---|
| Patients need accounts to use appointment services. | FR-01 — Patient Registration |
| Users require secure system access. | FR-02 — User Login |
| Patients need to locate doctors. | FR-04 — Search Doctor |
| Patients want specialization-based searching. | FR-05 — Filter Doctor by Specialization |
| Patients need to know when doctors are available. | FR-07 — View Available Appointment Slots |
| Patients need online appointment booking. | FR-08 — Book Appointment |
| A slot should not be assigned to two patients. | FR-09 — Prevent Duplicate Booking |
| Patients require confirmation after booking. | FR-10 — Appointment Confirmation |
| Patients need to cancel appointments. | FR-12 — Cancel Appointment |
| Patients need to change appointment times. | FR-13 — Reschedule Appointment |
| Doctors need access to their schedules. | FR-14 — Doctor Schedule |
| Administrators need to maintain doctor records. | FR-16 — Manage Doctors |
| Administrators need to maintain doctor schedules. | FR-17 — Manage Doctor Availability |
| Administrators need to manage appointments. | FR-18 — Manage Appointments |
| Access to information should be protected. | NFR-01 — Security |
| The system should be easy to understand and operate. | NFR-03 — Usability |
| Appointment information should remain accurate. | NFR-09 — Data Integrity |

# Conclusion

The simulated stakeholder interview allowed the most prominent needs of the suggested Hospital Appointment Booking System to be identified. The results show that patients need to have access to doctor information, availability, appointment booking, appointment cancelation and rescheduling. Physicians need to be able to access their schedules, administrators need to have functionality to add, remove and manage doctors along with their availability and appointments.

The findings are then used with the questionnaire and the other requirement analysis activities to draw the final conclusions of the functional and non-functional requirements of the proposed system.
