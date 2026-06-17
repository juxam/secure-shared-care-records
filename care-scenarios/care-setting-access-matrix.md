# Care-Setting Access Matrix

| Care setting | Likely user | Record access need | Clinical justification | Security risk | Privacy risk |
|---|---|---|---|---|---|
| GP surgery | GP, practice nurse, pharmacist | Hospital letters, discharge summaries, medication changes, test results | Continuity of care | Incorrect imported data, weak system integration | Over-reliance on external notes |
| Ambulance service | Paramedic, emergency clinician, call handler | Allergies, current medication, long-term conditions, care plans, DNACPR where applicable | Safe emergency treatment | Mobile-device compromise, wrong-patient lookup | Excessive access during emergency |
| Emergency department | Triage nurse, emergency doctor, pharmacist | GP record, previous admissions, medications, allergies, investigations | Rapid diagnosis and treatment | Break-glass misuse, insider snooping | Access to sensitive unrelated history |
| Urgent treatment centre | Urgent care clinician | Summary history, allergies, medications, recent encounters | Safe unscheduled care | Temporary workforce access | Poor patient transparency |
| Walk-in clinic | Nurse practitioner, GP out-of-hours clinician | Basic summary, medications, allergies, safeguarding flags where appropriate | Immediate care without registered GP context | Identity verification weakness | Unclear access boundary |
| Secondary care | Consultant, junior doctor, ward nurse | Referrals, GP history, prior diagnostics, medications | Treatment planning | Supplier/API exposure | Broad access beyond immediate need |
| Specialist provider | Specialist clinician | Referral data, diagnostics, relevant history | Condition-specific care | Poor role granularity | Over-disclosure of unrelated conditions |
| Community care | Community nurse, allied health professional | Care plan, medications, discharge summaries | Home-based and long-term care | Shared-device risk | Family/carer visibility issues |
