# Hospital Appointment Booking System - Test Summary

| Test Type | Planned Cases | Positive | Negative | Passed | Failed | Notes |
|---|---:|---:|---:|---:|---:|---|
| Unit Testing | 8 | 5 | 3 | 7 | 1 | 1 failure: duplicate booking validation |
| Integration Testing | 6 | 4 | 2 | 5 | 1 | 1 failure: cancelled slot not released |
| System Testing | 6 | 4 | 2 | 5 | 1 | 1 failure: old slot remains occupied after reschedule |
| User Acceptance Testing | 5 | 5 | 0 | 4 | 1 | 1 failure: reschedule confirmation unclear |

### Execution Note

> Results are simulated/design-walkthrough outcomes for an academic non-coding project. Failures are intentionally retained to demonstrate realistic defect identification and follow-up.

## Defect Summary

| Defect ID | Related Test | Severity | Issue | Recommended Fix | Retest Required | Current State |
|---|---|---|---|---|---|---|
| DEF-01 | UT-07 | **High** | System accepted a duplicate booking for an already-reserved slot. | Re-check availability immediately before appointment creation and enforce uniqueness for doctor/date/time. | **Yes** | Open |
| DEF-02 | IT-03 | **Medium** | Cancelled appointment did not release the slot in the doctor schedule. | Synchronize the cancellation with the schedule availability update. | **Yes** | Open |
| DEF-03 | ST-04 | **High** | Rescheduling reserved the new slot but did not release the old slot. | Use one transaction/workflow to release the old slot and reserve the new slot together. | **Yes** | Open |
| DEF-04 | UAT-03 | **Medium** | Reschedule confirmation did not clearly show the updated appointment date/time. | Refresh confirmation data after rescheduling and display the new date/time prominently. | **Yes** | Open |
