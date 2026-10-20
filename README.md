# Ransomware-Incident-Response-Plan

## About This Project

This project focuses on how an educational institution can respond to a suspected ransomware attack while protecting its systems, data and day-to-day operations.

I used a fictional scenario involving Northbridge Skills Institute, where staff reported locked files, unusual account activity, a large outbound data transfer and problems accessing learning materials and submitting assessments.

These events raised several concerns. The institute needed to understand how far the incident had spread, whether sensitive information might have been exposed and how to restore its services without bringing compromised systems back online.

My goal was to develop a practical incident response plan that addressed these concerns from a Governance, Risk and Compliance (GRC) perspective.

## What I Worked On

### 1. Assessing the Incident

I organised the available evidence into a timeline to understand what happened and when. I separated confirmed observations from possible explanations so that assumptions would not be treated as facts.

I also assessed the potential impact on confidentiality, integrity and availability (the CIA triad) and classified the incident as high severity, with clear conditions for escalating it to critical.

### 2. Planning the Incident Response

I outlined the steps the organisation should take after identifying the incident, including how to activate the response team, assign responsibilities, escalate major risks and document decisions.

I also developed a RACI matrix to clarify who would carry out each activity, who would be accountable, and which teams needed to be consulted or informed.

### 3. Containment and Evidence Preservation

One important part of this project was balancing the need to stop the attack with the need to preserve evidence.

The proposed response included isolating affected systems, reviewing suspicious account activity, restricting privileged access and preserving relevant security logs. I also outlined how investigators could document evidence collection and maintain a record of who handled each item.

The large outbound data transfer was treated as a warning sign that required further investigation, not automatic proof that information had been stolen.

### 4. Backup and Recovery Planning

I developed a recovery approach that prioritises essential services while ensuring that systems are checked before being returned to use.

This included testing backups in an isolated environment, reviewing privileged accounts, rebuilding compromised systems where necessary, validating restored data and monitoring for signs of further malicious activity.

The scenario also presented a difficult business decision: whether to proceed with an examination scheduled for 11:00 or postpone it if the learning platform could not be restored safely. The plan prioritised the security and integrity of the service over meeting the deadline at any cost.

### 5. Communication and Compliance

I prepared a communication plan for management, technical teams, learners, academic staff, service providers and legal or privacy advisers.

The aim was to ensure that people received timely and accurate updates without making unsupported claims about the incident or possible data theft.

I also considered the need to assess potential personal-data exposure against applicable privacy and legal requirements.

### 6. Tabletop Exercise and Improvements

I designed a tabletop exercise to test how the response team might handle additional challenges, including a failed backup restoration, an extortion claim, misleading social media posts and suspicious email activity.

Based on these scenarios, I proposed improvements such as maintaining offline contact lists, testing disconnected backups, improving security-log coverage, strengthening privileged-account controls and conducting regular incident response exercises.

## Key Lessons I Learned

- Incident response decisions should be based on evidence rather than assumptions.
- Restoring services quickly is important, but restoring them securely is essential.
- Clear responsibilities help teams respond more effectively during an incident.
- Backups must be tested; a successful backup report does not automatically prove that recovery will work.
- Possible data exposure requires investigation before conclusions are communicated.
- Business continuity planning should include alternative arrangements when essential services are unavailable.

## Frameworks and References

- NIST SP 800-61 Rev. 3 — Incident response guidance.
- CISA #StopRansomware Guide.
- CIA triad — Confidentiality, Integrity and Availability.
- RACI matrix — Roles and responsibilities.
- Nigeria Data Protection Act 2023 — Referenced for the assessment of potential privacy obligations.

## Project Outcome

This project helped me connect cybersecurity incident response with practical GRC activities, including risk assessment, evidence documentation, accountability, business continuity and recovery planning.

It also strengthened my understanding of how security decisions can affect an organisation's operations, reputation and responsibility to protect the people whose information it holds.

## Project Scope

This was a fictional, scenario-based academic project. I developed a proposed response plan; I did not investigate a live ransomware incident or carry out actual forensic evidence collection or system recovery.

## Areas of Interest

Cybersecurity GRC | Technology Risk | Incident Response | Risk Assessment | Business Continuity | Security Governance
