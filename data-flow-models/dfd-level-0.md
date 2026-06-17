# Level 0 Data-Flow Model

## System Under Study

Cross-provider access to patient medical records for direct care.

## External Actors

- Patient
- GP surgery
- Ambulance service
- Emergency department
- Urgent treatment centre
- Walk-in clinic
- Secondary care provider
- Specialist provider
- Community care provider
- Shared record platform or interoperability service
- Identity and access management service
- Audit and monitoring service

## Main Data Stores

- GP record
- Hospital EPR
- Shared care record
- Medication record
- Diagnostic results
- Referral and discharge summaries
- Care plans
- Audit logs
- Access-control records

## Main Data Flows

1. Clinician searches for patient.
2. System verifies identity and role.
3. System checks care relationship or access justification.
4. System retrieves relevant patient record sections.
5. Clinician views or imports patient information.
6. System records access event in audit log.
7. Patient may later view access history, depending on system capability.
8. Governance team may review unusual access patterns.

## Initial Trust Boundaries

- Between GP systems and shared record infrastructure.
- Between ambulance/mobile systems and central services.
- Between NHS and supplier-managed platforms.
- Between direct-care access and wider organisational analytics.
- Between routine access and emergency break-glass access.
