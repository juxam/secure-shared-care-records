# Ambulance Access Scenario

## Care Context

An ambulance crew responds to a patient in the community who may be unconscious, confused, distressed or unable to provide a reliable medical history.

## Actor

Paramedic, ambulance clinician, call handler or emergency operations clinician.

## Patient Information Needed

- Allergies
- Current medications
- Long-term conditions
- Recent hospital admissions
- Relevant care plans
- Frailty status where applicable
- DNACPR or advance care planning information where applicable
- Safeguarding alerts where clinically necessary

## Clinical Justification

Ambulance clinicians often make urgent decisions with limited information. Access to relevant patient records can support safer treatment, reduce medication errors, improve triage decisions and help crews decide whether hospital conveyance is necessary.

## Access Pathway

The ambulance clinician searches for the patient using demographic details or NHS number. The system verifies identity, role and access context before retrieving relevant record sections from GP, shared care record or hospital systems.

## Security Risks

- Mobile-device loss or compromise
- Weak authentication in urgent situations
- Wrong-patient lookup
- Excessive access during emergency response
- Use of shared devices
- Poor network security in mobile environments

## Privacy Risks

- Access to more information than required
- Exposure of sensitive conditions in non-private environments
- Inadequate patient awareness of emergency access
- Potential misuse of emergency access justification

## Existing or Expected Controls

- Role-based access control
- Device authentication
- Audit logging
- Emergency access justification
- Mobile device management
- Session timeout

## Control Gaps

- Emergency access may be difficult to monitor in real time
- Mobile working increases device and network exposure
- Patient identity may be uncertain during emergency incidents
- Audit may be reactive rather than proactive

## Notes for Article 1

Use this scenario to demonstrate the tension between urgent clinical availability and privacy/security proportionality.

## Notes for Article 2

Use this as an interview prompt for paramedics, emergency clinicians and patients.

## Notes for Article 3

Use this scenario to test context-aware emergency access, break-glass controls, audit review and mobile-device safeguards.
