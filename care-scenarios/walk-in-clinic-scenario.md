# Walk-in Clinic Scenario

## Care Context

A patient attends a walk-in clinic or urgent treatment centre without an appointment. The clinician may have limited prior knowledge of the patient.

## Actor

Nurse practitioner, urgent care clinician, GP out-of-hours clinician, pharmacist or temporary clinical staff member.

## Patient Information Needed

- Medication history
- Allergies
- Recent consultations
- Relevant diagnoses
- Summary care information
- Safeguarding alerts where clinically necessary
- Recent emergency or hospital encounters

## Clinical Justification

Walk-in and urgent care settings often require quick access to basic but reliable patient information. Shared records can improve safety when the patient cannot provide a complete or accurate history.

## Access Pathway

The clinician searches for the patient, confirms identity and accesses a relevant summary or shared care record through an approved system.

## Security Risks

- Temporary staff retain access beyond clinical need
- Weak role lifecycle management
- Shared workstation access
- Poor identity verification
- Access from unfamiliar or high-turnover settings

## Privacy Risks

- Excessive access for a minor complaint
- Lack of patient awareness
- Unclear boundary between urgent care and routine access
- Access to sensitive information not needed for the consultation

## Existing or Expected Controls

- Role-based access control
- Time-limited staff access
- Audit logging
- User authentication
- Staff training
- Local access policies

## Control Gaps

- Temporary workforce access may not be removed promptly
- Access may not be sufficiently limited to the care context
- Audit review may be inconsistent
- Patient-facing transparency may be weak

## Notes for Article 1

Use this scenario to show how temporary access and unscheduled care create distinct security and privacy risks.

## Notes for Article 2

Use this scenario to ask patients whether they expect walk-in clinicians to access their wider medical history.

## Notes for Article 3

Use this scenario to test time-bound permissions, context-aware access and minimum-necessary record views.
