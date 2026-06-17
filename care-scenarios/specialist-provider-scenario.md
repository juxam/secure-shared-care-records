# Specialist Provider Scenario

## Care Context

A patient is referred to a specialist service such as cardiology, oncology, dermatology, mental health, fertility, neurology or another specialist provider.

## Actor

Specialist consultant, specialist nurse, allied health professional, referral coordinator or multidisciplinary team member.

## Patient Information Needed

- Referral information
- Relevant diagnostic results
- Condition-specific history
- Current medications
- Allergies
- Previous specialist letters
- Relevant GP and hospital history

## Clinical Justification

Specialist providers need enough information to assess the patient safely and avoid duplication. However, the relevant information may be narrower than the complete patient record.

## Access Pathway

The specialist accesses referral data, shared care record content or hospital/GP information through an approved system. Access should ideally be limited to information relevant to the specialty and clinical task.

## Security Risks

- Poor role granularity
- Over-broad access to full longitudinal record
- Privileged access misuse
- Weak access segmentation
- Supplier or third-party service exposure

## Privacy Risks

- Over-disclosure of unrelated conditions
- Exposure of mental-health, reproductive-health, safeguarding or social history information
- Specialist access beyond the immediate care purpose
- Patient concern over who can view sensitive information

## Existing or Expected Controls

- Role-based access control
- Referral-based access
- Audit logging
- Data-sharing agreements
- Professional confidentiality obligations
- Information governance policies

## Control Gaps

- Role-based access may not be granular enough
- Sensitive information may not be segmented
- Referral context may not automatically restrict record visibility
- Patients may not understand what the specialist can see

## Notes for Article 1

Use this scenario to discuss data minimisation, record segmentation and sensitive-category over-disclosure.

## Notes for Article 2

Use this scenario to explore patient trust and expectations around specialist access.

## Notes for Article 3

Use this scenario to test context-aware record segmentation and specialty-specific access profiles.
