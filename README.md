# Patient Empowered Wound Care

## Project Summary

This repository provides a professional summary of my contributions to imitoWound. An App focused on **patient-centered wound care**. The project was developed in collaboration with [imito AG](https://imito.io/de) as part of a university-led initiative at **Berner FH**.

The application empowers patients and healthcare professionals to document, manage, and track wound assessments using mobile devices. Special attention was given to usability for patients and clinical staff, structured data exchange using imitoWeb API which allows integration into EHR and PACS services and accessibility enhancements.

**Note**: The source code cannot be published publicly due to confidentiality agreements. However, access may be granted upon request and subject to approval from imito AG.

---

## Objectives

- Enable structured and accessible wound assessment documentation
- Enhance communication between patients and providers using imitoWound
- Improve usability and data transparency for non-technical users
- Prototype a scalable and compliant solution aligned with real clinical workflows

---

## Methodology

### 1. Scientific & Clinical Foundations

- A **literature review** was conducted to define evidence-based wound care requirements, usability criteria, and digital health adoption barriers.
- Emphasis was placed on patient empowerment, continuity of care, and mobile-first strategies.

### 2. Business Process Modeling

- **BPMN diagrams** were used to map clinical workflows and identify areas for digitization and automation.
- This modeling approach informed the **feature development roadmap**, ensuring alignment with actual care pathways.


### 3. Threat Modeling

- A threat model based on STRIDE and OWASP principles was created to identify key risks and inform security design.
- All communication is TLS-encrypted; no sensitive data is stored in unencrypted DBs.
-  Mitigations include strong authentication (2FA), least-privilege access, rate limiting, and logging. The model guided security considerations ahead of deployment.


### 4. Technical Implementation

Key contributions included:

- Implementation of **secure login** and session management (token-based auth)
- Asynchronous data upload: patient metadata, image files.
- Architectural improvements using **MVVM**, Kotlin coroutines, and repository pattern
- UX enhancements such as dynamic field visibility, localized input constraints, and streamlined error handling

---

## Results

- A **fully functional prototype** was developed and demonstrated to stakeholders.
- Users can perform end-to-end wound documentation: capture media, attach clinical metadata, and persist data securely.

---

## Collaboration

This project was conducted as part of my Bachelor's studies at Berner FH and in cooperation with imito AG.
---

## Access and Contact

For further information please contact: 

**Renner C.**  
BSc Student in eHealth
