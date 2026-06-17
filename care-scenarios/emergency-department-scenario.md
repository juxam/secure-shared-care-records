# Emergency Department Scenario

## Care Context

A patient arrives at an emergency department through self-presentation, ambulance conveyance or referral from another service. The patient may require rapid assessment, diagnosis and treatment.

## Actor

Emergency doctor, triage nurse, emergency nurse practitioner, pharmacist or hospital clinician.

## Patient Information Needed

- GP summary record
- Current medications
- Allergies
- Previous admissions
- Recent investigations
- Diagnostic results
- Existing care plans
- Relevant mental-health or safeguarding information where clinically necessary

## Clinical Justification

Emergency care requires rapid access to reliable information. Shared patient records can support diagnosis, reduce duplication, identify risks and improve medication safety.

## Access Pathway

The clinician searches for the patient through the emergency department system or shared care record platform. The system confirms user role, organisational access and care context before granting access to relevant record sections.

## Security Risks

- Break-glass access used without proper justification
- Insider curiosity access
- Excessive access to full record
- Weak monitoring of urgent access
- Shared workstation risk
- Credential misuse in busy clinical areas

## Privacy Risks

- Access to unrelated sensitive history
- Limited patient awareness during emergency treatment
- Exposure of mental-health, safeguarding or reproductive-health information
- Over-disclosure where summary access may be sufficient

## Existing or Expected Controls

- Role-based access control
- Emergency access reason codes
- Audit logging
- Staff training
- Smartcard or identity-based access
- Organisational access policies

## Control Gaps

- Audit logs may not be reviewed consistently
- Emergency access may become normalised
- Staff may not always understand minimum-necessary access
- System design may not separate highly sensitive information clearly

## Notes for Article 1

Use this scenario to discuss break-glass access, insider threat and minimum-necessary access.

## Notes for Article 2

Use this scenario to ask clinicians and patients what level of emergency access is acceptable.

## Notes for Article 3

Use this scenario to test emergency access justification, post-access review and segmented record visibility.
