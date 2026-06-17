# GP and Secondary Care Scenario

## Care Context

A patient is discharged from hospital or referred between GP and secondary care services. The GP needs access to hospital information, while hospital clinicians may need GP-held history.

## Actor

GP, practice nurse, practice pharmacist, hospital consultant, junior doctor, discharge coordinator or specialist nurse.

## Patient Information Needed

- Hospital discharge summaries
- Medication changes
- Test results
- Referral letters
- Previous diagnoses
- GP problem list
- Care plans
- Follow-up instructions

## Clinical Justification

Accurate sharing between GP and secondary care supports continuity of care, medication reconciliation, follow-up planning and reduced duplication of investigations.

## Access Pathway

Information flows between GP systems, hospital electronic patient records and shared care record platforms. Clinicians view or import relevant record sections into their local system.

## Security Risks

- Weak system integration
- Data copied into another system without clear provenance
- Outdated discharge information reused
- Supplier or API exposure
- Inconsistent access controls across organisations

## Privacy Risks

- Over-sharing of GP-held information with hospital users
- Inappropriate visibility of unrelated history
- Poor patient understanding of how information moves between systems
- Confusion over controller or accountability responsibilities

## Existing or Expected Controls

- Role-based access control
- Audit logs
- Data-sharing agreements
- Record timestamps
- Referral and discharge workflows
- Information governance policies

## Control Gaps

- Provenance may be unclear after data is copied
- Updates may not synchronise across systems
- Users may not know whether information is current
- Accountability may be unclear when multiple providers handle the same data

## Notes for Article 1

Use this scenario to discuss data integrity, provenance, governance and cross-organisational accountability.

## Notes for Article 2

Use this scenario to explore clinician concerns about trusting data from other systems.

## Notes for Article 3

Use this scenario to test provenance metadata, update-status indicators and cross-provider audit requirements.
