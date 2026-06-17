\# Complete but Controlled: Security and Privacy Implications of Cross-Provider Access to Patient Medical Records in Integrated Healthcare



\## Abstract



\[Write this last after the main body is drafted.]



\## 1. Introduction



Healthcare systems increasingly depend on timely access to patient information across organisational and professional boundaries. In routine, urgent and emergency care, clinicians often need access to medication history, allergies, diagnoses, test results, discharge summaries, referrals, care plans and previous encounters to make safe and informed decisions. Fragmented records can delay treatment, increase duplication, weaken continuity of care and require patients to repeatedly provide the same information across different care settings.



The movement toward shared patient records seeks to address this fragmentation by enabling authorised professionals across GP surgeries, ambulance services, urgent and emergency care, emergency departments, walk-in clinics, secondary care providers and specialist services to access relevant patient information at the point of care. In principle, wider access to complete or near-complete records can improve clinical decision-making, medication safety, continuity of care and patient experience.



However, wider record accessibility also creates a significant security and privacy challenge. The same infrastructure that improves care coordination also expands the number of users, organisations, devices, suppliers, systems and access contexts through which sensitive health information may be viewed, transferred, misused or compromised. Patient records may include highly sensitive information relating to diagnoses, medication, mental health, safeguarding, reproductive health, social circumstances, long-term conditions and previous care encounters.



This article examines the security and privacy implications of cross-provider access to patient medical records for direct care. It focuses on the tension between clinical availability and privacy/security proportionality. The central argument is that integrated patient records should not be treated only as interoperability infrastructure. They should also be understood as socio-technical security and privacy systems that require careful attention to access justification, role clarity, data minimisation, auditability, patient transparency, supplier assurance and clinical context.



\## 2. Background: Shared Patient Records and Direct Care



This section will explain why shared patient records are being pursued and why they matter for direct care.



Key points to develop:



\* Fragmented patient records can affect continuity of care.

\* GP, urgent care, emergency care, ambulance, secondary care and specialist providers often hold different parts of the patient story.

\* Shared records aim to make relevant information available to authorised professionals at the point of care.

\* The clinical benefit is strongest where time, safety and care coordination are important.

\* Direct-care access should be distinguished from secondary uses such as research, commercial analytics, population health management or AI model training.



Sources to use from the evidence matrix:



\* NHS Shared Care Records

\* GP Connect Access Record

\* Summary Care Record

\* Single Patient Record / Health Bill documents

\* Academic literature on electronic health records and health information exchange



\## 3. Policy, Governance and Legal Context



This section will explain the governance environment surrounding shared medical-record access.



Key points to develop:



\* Health information is sensitive and requires strong protection.

\* UK GDPR and data protection principles are relevant to lawful, fair and transparent processing.

\* Special category health data requires additional protection.

\* Data Protection Impact Assessments are important where processing may create high risk.

\* Caldicott Principles are relevant to confidential patient information and professional responsibility.

\* NHS data security and information governance expectations shape how organisations should handle patient data.

\* Clinical safety standards are relevant because record-sharing systems can affect patient care and safety.



Sources to use from the evidence matrix:



\* UK GDPR special category data guidance

\* ICO DPIA guidance

\* Caldicott Principles

\* NHS Data Security and Protection Toolkit

\* DCB0129

\* DCB0160



\## 4. Security and Privacy Problem Framing



This section will frame the problem clearly.



Wider access to patient records creates a broader security and privacy risk landscape. The risks do not arise only from external cyberattacks. They also arise from everyday access decisions, weak role definitions, poor audit practices, unclear information governance, excessive record visibility, temporary staff access, supplier involvement and emergency access pathways.



The key problem is not whether patient information should be shared for care. The key problem is how shared access can be made necessary, proportionate, secure, accountable and clinically useful.



Security concerns may include:



\* unauthorised access;

\* insider curiosity access;

\* weak identity and access management;

\* compromised credentials;

\* mobile-device exposure;

\* supplier-side compromise;

\* poor audit monitoring;

\* inaccurate or outdated data being reused;

\* weak system integration;

\* emergency access misuse.



Privacy concerns may include:



\* over-disclosure;

\* access to unrelated sensitive history;

\* weak data minimisation;

\* lack of patient transparency;

\* unclear respect for patient objections;

\* inability to see who has accessed a record;

\* sharing beyond the immediate care context;

\* exposure of sensitive mental-health, safeguarding or reproductive-health information.



\## 5. Method



This article uses a structured policy and literature analysis supported by care-context mapping, data-flow modelling and preliminary security/privacy threat modelling.



The method has four stages.



First, relevant policy, governance, legal, technical and academic sources are identified and organised in an evidence matrix. The evidence matrix records each source, its relevance to the project, its main security and privacy implications, and its expected use in the article.



Second, a care-setting access matrix is developed to compare different care contexts, users, record-access needs, clinical justifications and associated security and privacy risks.



Third, a Level 0 data-flow model is created to identify major actors, systems, data stores, data flows and trust boundaries involved in cross-provider patient-record access.



Fourth, an initial security and privacy risk register is created. The risk register is used to group threats into an emerging taxonomy that can inform future stakeholder research and framework development.



\## 6. Care-Setting Access Matrix



This section will discuss the care-setting access matrix.



The matrix should compare at least the following settings:



\* GP surgery

\* ambulance service

\* emergency department

\* urgent treatment centre

\* walk-in clinic

\* secondary care

\* specialist provider

\* community care



For each setting, discuss:



\* who may need access;

\* what patient information may be needed;

\* why access may be clinically justified;

\* what security risks may arise;

\* what privacy risks may arise;

\* what controls may be needed.



Insert or summarise the table from:



care-scenarios/care-setting-access-matrix.md



\## 7. Data-Flow Model



This section will describe the Level 0 data-flow model.



The system under study is cross-provider access to patient medical records for direct care.



The main actors include:



\* patient;

\* GP surgery;

\* ambulance service;

\* emergency department;

\* urgent treatment centre;

\* walk-in clinic;

\* secondary care provider;

\* specialist provider;

\* community care provider;

\* shared record platform or interoperability service;

\* identity and access management service;

\* audit and monitoring service.



The main data stores include:



\* GP record;

\* hospital electronic patient record;

\* shared care record;

\* medication record;

\* diagnostic results;

\* referral and discharge summaries;

\* care plans;

\* audit logs;

\* access-control records.



The main data flows include clinician search, identity verification, role checking, access justification, record retrieval, clinical viewing, audit logging and governance review.



This section should also identify trust boundaries, especially between organisations, between mobile and central systems, between supplier-managed platforms and NHS-controlled systems, and between routine access and emergency access.



\## 8. Security and Privacy Risk Taxonomy



This section will transform the risk register into a clear taxonomy.



Possible risk categories include:



\### 8.1 Access Control Risks



Examples:



\* unauthorised access;

\* excessive access;

\* weak role definitions;

\* temporary staff access;

\* emergency break-glass misuse.



\### 8.2 Insider Threat and Misuse Risks



Examples:



\* curiosity access;

\* access without care relationship;

\* privileged account misuse;

\* weak sanctions or monitoring.



\### 8.3 Data Minimisation and Over-Disclosure Risks



Examples:



\* specialist users seeing unrelated history;

\* sensitive information being visible outside the immediate care context;

\* complete record access where summary access would be sufficient.



\### 8.4 Identity, Matching and Context Risks



Examples:



\* wrong-patient lookup;

\* identity matching error;

\* access without clear clinical context;

\* lack of care-relationship verification.



\### 8.5 Data Integrity and Provenance Risks



Examples:



\* outdated information being reused;

\* data copied without provenance;

\* inaccurate imported data;

\* unclear source or update status.



\### 8.6 Auditability and Accountability Risks



Examples:



\* audit logs not actively reviewed;

\* patients unable to see who accessed their record;

\* weak post-access review;

\* unclear organisational responsibility.



\### 8.7 Supplier and Infrastructure Risks



Examples:



\* supplier-side compromise;

\* API exposure;

\* platform misconfiguration;

\* privileged technical access.



\## 9. Discussion



This section should discuss the wider meaning of the findings.



The central discussion point is that shared patient records create a dual requirement. They must support information availability for safe and timely care, but they must also protect confidentiality, privacy, autonomy, trust and accountability.



A one-size-fits-all access model is unlikely to be sufficient because care contexts differ. A paramedic responding to an emergency, an emergency department doctor managing acute deterioration, a GP reviewing a hospital discharge summary and a specialist clinician assessing a referral may each have legitimate information needs, but the depth and sensitivity of required access may differ.



Therefore, shared-record governance should consider role, context, urgency, sensitivity, patient expectation, access justification, auditability and organisational accountability.



\## 10. Implications



\### 10.1 Implications for Healthcare Organisations



Healthcare organisations need clear policies for role-based access, emergency access, staff training, audit review, incident response, supplier assurance and patient communication.



\### 10.2 Implications for System Designers



System designers should consider context-aware access, segmented record views, provenance metadata, audit-by-design, patient-facing transparency and usable access controls.



\### 10.3 Implications for Information Governance Teams



Information governance teams should ensure that shared-record access is supported by DPIAs, clear accountability, documented access purposes, regular audit review and appropriate management of patient objections or preferences.



\### 10.4 Implications for Patients



Patients need confidence that their information is used appropriately, accessed only when justified, protected from misuse and subject to meaningful accountability.



\## 11. Limitations



This article is a conceptual and policy-based analysis. It does not yet include empirical stakeholder data, technical system testing or live implementation evaluation. These limitations will be addressed in later phases of the research programme through stakeholder engagement and framework validation.



\## 12. Conclusion



Cross-provider access to patient medical records can support safer, faster and more coordinated care, particularly across GP, ambulance, urgent care, emergency care, secondary care and specialist settings. However, wider accessibility also creates a broader security and privacy risk landscape.



The main challenge is not simply to make records available, but to make access necessary, proportionate, secure, auditable, transparent and clinically meaningful. This article provides the foundation for a broader research programme by developing an initial care-context map, data-flow model and security/privacy risk taxonomy for shared patient-record access.



\## References



\[Add references from the evidence matrix here.]



