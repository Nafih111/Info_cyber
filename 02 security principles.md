# Security Principles

## Learning Objectives:
- Understand the CIA Triad and its importance.
- Explain Risk, Privacy, and Accountability.
- Relate security principles to real-world cyber incidents.

## CIA Triad
- The CIA Triad forms the foundation of information security.
- Each element ensures that information remains safe and trustworthy.

| Element | Description | Example |
|----------|--------------|----------|
| Confidentiality | Ensures data is accessible only to authorized users. | Encrypting files, using passwords, access control lists. |
| Integrity | Ensures data is accurate, consistent, and not tampered with. | Using hashing, digital signatures, checksums. |
| Availability | Ensures systems and data are available when needed. | Redundant servers, backups, DDoS protection. |

![OIP](https://github.com/user-attachments/assets/2b828cc1-5e3e-4380-be7f-3ddccecdc608)

## Key Concepts
- Data breaches often occur when one or more CIA principles are compromised.
- Balance is key — too much focus on one (e.g., availability) can weaken another (e.g., confidentiality).
- # Examples
- *Confidentiality Violation:* Unauthorized access to customer data (e.g., Facebook-Cambridge Analytica case).
- *Integrity Violation:* Tampered medical data in hospitals leading to misdiagnosis.
- *Availability Violation:* DDoS attack on banking websites preventing service access.


- # Risk, Privacy, and Accountability
# Risk

## Components:
- *Threat* -> something that can cause damage.
- *Vulnerability* -> weakness that can be exploited.
- *Impact* -> damage if threat is realized

- 
![download](https://github.com/user-attachments/assets/ccfc5bb8-cdce-4554-bed2-369424dd2f9b)

## Formula:
- *Risk = Threat x Vulnerability x Impact*
## example
- threat : phishing
- vulnerability : employee lack of awareness
- impact : creadential theft , financial loss


## privacy 
- Protecting personal and sensitive information of individuals.
- Governed by laws like GDPR,DRDP Act(india),HIPAA.
- freedom from unauthorized intrusion : state of being let alone and able to keep certain especially personal matters to oneself see
- ![OIP](https://github.com/user-attachments/assets/2233d232-f5e1-40bb-98e5-8586606de6a6)

## KEY PRACTICES
- data minimization
- informed consent
- data anonymization
Example : A healthcare app must not share user health data without consent.

## Accountability
  ensuring every action in an iyt system can be traced to an individual

  Achievement though :
  - logging s auditing
  - user acess tracking
  - non-repudiation mechanism
     example; audit logs in firewalls to trace malicious usEr actions


    ## Real-world Case Studies:

| CASE | Description | VIOLATED PRINCIPLE |
|------|-------------|---------------|
| Wanna cry (2017) | Ransomware disabled hospital systems worldwide| Availability |
| Equifax Breach (2017) | Personal data of 143M users leaked | Confidentiality and integrity |
| Twitter Hack (2020) | Insider access to admin tools | Confidentiality and accountability |
