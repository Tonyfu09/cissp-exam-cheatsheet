# CISSP Domain 1 — Security And Risk Management

## Description  
CISSP Domain 1, **Security and Risk Management**, forms the foundation of information security.  
It covers principles like the **CIA triad**, **security governance**, and **risk management concepts** to:  
- Protect organizational assets  
- Ensure compliance with laws and regulations  
- Maintain ethical conduct


## 1.1 Security Governance Principles
- **Asset Owner** – Responsible for the classification, control, and protection of assets.  
- **Custodian** – Implements the protection and maintenance of assets on behalf of the owner.  
- **User** – Uses assets appropriately and follows security policies.  

Risk analysis is a “point-in-time” metric, because risks constantly change, continuous review and improvement of security is required.

## Organizational Processes
- **Mission Statement** – Purpose and long-term direction.  
- **Strategic Plan (3–5 years)** – High-level security strategy (e.g., Zero Trust).  
- **Tactical Plan (1–2 years)** – Medium-term projects (MFA, SIEM).  
- **Operational Plan** – Daily tasks (patching, monitoring, IR).

## 1.3 Evaluate and apply security governance principles
### Divestiture Event Considerations
- **Sanitize assets** before disposal or transfer.  
- **Remove and destroy storage media** containing sensitive data.  
- **Debrief employees** released from duty to ensure no residual access or knowledge risks.

## 1.4 Compliance
- Laws  
- Regulations  
- Standards  
- Internal policies  

## 1.5 Legal and Regulatory Issues

### Types of Law
- **Criminal** – Harm to society (hacking, fraud)  
- **Civil** – Disputes between parties (negligence)  
- **Administrative** – Government regulations  

### Key Concepts
- **Liability** – Responsibility for damages  
- **Burden of Proof:**  
  - Criminal: *Beyond a reasonable doubt*  
  - Civil: *Preponderance of evidence*  

### Evidence Handling
- Chain of custody  
- Admissibility  
- Hearsay exceptions (business records)  

## 1.6 Understand requirements for investigation types 
- **Administrative** – Investigates internal policy violations.  
- **Criminal** – Investigates violations of criminal law.  
- **Civil** – Investigates disputes between parties in civil court.  
- **Regulatory** – Investigates compliance with industry or government regulations.  
- **Industry Standards** – Investigates deviations from best practices. 

- **Thrill Attacks** – Attacks motivated by **bragging rights** or the **pride of conquering a secure system**.  

## 1.7 Risk Management Concepts

### Risk Formulas
- **Risk** = Threat × Vulnerability × Impact  
- **Residual Risk** = Risk after controls  
- **Total Risk** = Asset Value × Threat × Vulnerability  

### Control Categories
| Category | Examples |
|----------|----------|
| **Administrative** | Policies, background checks |
| **Technical** | Firewalls, encryption |
| **Physical** | Guards, locks, CCTV |

### Control Types
| Type | Purpose |
|------|---------|
| **Preventive** | Stop incidents (MFA) |
| **Detective** | Identify incidents (IDS) |
| **Corrective** | Fix issues (patching) |
| **Deterrent** | Deter adversaries |
| **Compensating** | Alternative controls |


## 1.8 Identify, analyze, and prioritize Business Continuity (BC) requirements
- **Quantitative** – ALE, SLE, ARO  
- **Qualitative** – High/Medium/Low ratings  

## 1.9 Risk-Based Management Concepts

### Key Concepts
- **Risk Appetite** – Amount of acceptable risk  
- **Risk Tolerance** – Boundaries on risk levels  
- **Management** owns risk  
- **Security** advises on controls  

## 1.10 Security Control Assessment (SCA)

Assess whether controls:

- Are implemented correctly  
- Operate as intended  
- Meet security requirements  

### Assessment Methods
- **Examine** – Documents, policies  
- **Interview** – Personnel  
- **Test** – Technical validation

## 1.11 Threat Modeling Concepts

### Models
- **STRIDE**  
- **PASTA** – Risk-focused  
- **OCTAVE** – Organizational  
- **VAST** – Large-scale  
- **Attack Trees** – Visual attack paths  

### Process
1. Identify assets  
2. Identify threats  
3. Identify vulnerabilities  
4. Map controls  

## 1.12 Apply Supply Chain Risk Management (SCRM) concepts

Supply Chain Risk Management (SCRM) concepts
- Meet security requirements  
- Perform background checks  
- Provide secure hardware/software  
- Maintain redundancy  
- Manage third-party risks

## 1.13 Policies, Standards, Procedures, Guidelines

### Policy Components
- Purpose  
- Scope  
- Roles & responsibilities  
- Enforcement  
- Exceptions  
- Review cycles  

### Lifecycle
1. Develop  
2. Approve  
3. Publish  
4. Train  
5. Enforce  
6. Review/update  

## 1.14 Personnel Security & Risk

### Hiring
- Background checks  
- Identity & reference verification  

### During Employment
- Mandatory vacations  
- Job rotation  
- Separation of duties  
- Training & awareness  

### Termination
- Immediate access removal  
- Exit interview  
- Asset retrieval  

---

## Scenario List  

1. When conducting a **risk assessment**, the team should discuss these metrics: **ALE, SLE, ARO, EF**.  

| Term        | Definition | Functional Use |
|-------------|------------|----------------|
| **ALE** (Annualized Loss Expectancy) | Expected yearly loss from a risk | Helps quantify total financial risk |
| **SLE** (Single Loss Expectancy)     | Cost of a single incident | Measures the impact per occurrence |
| **ARO** (Annualized Rate of Occurrence) | Estimated frequency of an incident per year | Helps predict likelihood of risk |
| **EF** (Exposure Factor)             | Percentage of asset value lost due to incident | Shows proportional damage to asset |

---

2. Principle that for exercise in a particular situation to avoid causing harm to others, serving as the standard for determining negligence in legal case

| Term        | Definition | Functional Use |
|-------------|------------|----------------|
| **Due Care** | Acting responsibly to avoid causing harm to others (the “prudent person” rule) | Demonstrates that reasonable protective measures were taken |
| **Due Diligence** | Ongoing process of ensuring policies, procedures, and controls are maintained | Shows continuous monitoring and oversight of risks |

---

3. Metrics for reducing risk  

| Term | Definition | Functional Use |
|------|-------------|----------------|
| **Risk Avoidance** | Eliminate the risk source entirely | Example: Disable a vulnerable service |
| **Risk Mitigation** | Reduce the likelihood or impact | Example: Apply patches, add firewalls |
| **Risk Transfer** | Shift the risk to another party | Example: Insurance, outsourcing |
| **Risk Acceptance** | Acknowledge and accept the residual risk | Example: Low impact and low probability events |
| **Risk Sharing** | Divide responsibility among parties | Example: Joint ventures, partnerships |

---


4. Types of intellectual property protection

| Term        | Definition | Functional Use |
|-------------|------------|----------------|
| **Patents** | Protect inventions or processes | Prevent others from making, using, or selling the invention |
| **Trademarks** | Protect brand names, logos, and symbols | Helps distinguish goods/services in the marketplace |
| **Copyrights** | Protect creative works like books, music, software | Grants exclusive rights to reproduce, distribute, or display |
| **Trade Secrets** | Protect confidential business information | Prevents disclosure of proprietary methods, formulas, or processes |

---

5. Security Goal — The **CIA Triad**  

| Term | Definition | Functional Use |
|------|-------------|----------------|
| **Confidentiality (C)** | Ensures information is accessible only to authorized individuals | Protects against unauthorized disclosure |
| **Integrity (I)** | Ensures accuracy and completeness of data | Prevents unauthorized modification |
| **Availability (A)** | Ensures reliable and timely access to data and systems | Prevents downtime and denial-of-service |

---

## STRIDE Model  
Used for **threat modeling** to identify security risks:

| Category | Description | Example |
|-----------|-------------|----------|
| **S** – Spoofing | Pretending to be someone else | Fake login or identity |
| **T** – Tampering | Modifying data or code | Changing parameters in transit |
| **R** – Repudiation | Denying actions without evidence | Lack of logs or audit trails |
| **I** – Information Disclosure | Unauthorized access to data | Data leak or eavesdropping |
| **D** – Denial of Service | Disrupting system availability | Flooding or resource exhaustion |
| **E** – Elevation of Privilege | Gaining unauthorized access rights | Privilege escalation attack |

---

## RMF (Risk Management Framework) Phases  

| Phase | Description |
|-------|-------------|
| **1. Categorize** | Determine system and data sensitivity based on impact (FIPS 199) |
| **2. Select** | Choose baseline security controls (NIST SP 800-53) |
| **3. Implement** | Apply the selected security controls |
| **4. Assess** | Evaluate effectiveness through testing or audit |
| **5. Authorize** | Management accepts residual risk and grants operation approval |
| **6. Monitor** | Continuously track control performance and emerging risks |

---

## DREAD Risk Rating System  
Used to **prioritize and rate risk** by scoring each factor (1–10):

| Category | Description |
|-----------|-------------|
| **Damage Potential** | How severe would the damage be? |
| **Reproducibility** | How easily can the attack be reproduced? |
| **Exploitability** | How easy is it to exploit the vulnerability? |
| **Affected Users** | How many users would be impacted? |
| **Discoverability** | How easy is it to discover the vulnerability? |

> Total Risk = (D + R + E + A + D) / 5

---

## Security Control Assessment (SCA)
In the context of **1.10**, the SCA evaluates whether implemented security controls:  
- Are **properly implemented**,  
- **Operate as intended**, and  
- **Produce the desired security outcomes**.

---

## Key Regulations & Standards

### FERPA (Family Educational Rights and Privacy Act)
- U.S. law protecting **student education records**.
- Grants students rights over their records (access, correction, some control of disclosure).
- Applies to schools receiving funds from the U.S. Department of Education.
- **Penalties**: Can lose federal funding (no direct monetary fines to individuals).

---

### HIPAA (Health Insurance Portability and Accountability Act)
- U.S. law for **healthcare data protection**.
- Safeguards **PHI (Protected Health Information)** and **ePHI (Electronic PHI)**.
- Key rules:
  - **Privacy Rule** (use/disclosure of PHI)
  - **Security Rule** (admin, physical, technical safeguards)
  - **Breach Notification Rule** (reporting requirements)
- **Penalties**: Civil fines up to **$1.5M per year** for identical violations;  
  Criminal penalties up to **$250,000 fine and 10 years in prison**.

---

### SOX (Sarbanes–Oxley Act of 2002)
- U.S. law ensuring **accuracy and integrity of financial reporting** for public companies.
- Focus on **internal controls** and **auditing requirements**.
- Section 404: Management and auditors must report on effectiveness of internal controls.
- **Penalties**: Fines up to **$5M** and prison up to **20 years** for willful violations (fraud, destroying records).

---

### PCI DSS (Payment Card Industry Data Security Standard)
- Industry standard (not a law) for organizations handling **cardholder data**.
- Requirements:
  - Protect cardholder data (encryption, masking, storage limits).
  - Secure networks and systems (firewalls, patching).
  - Strong access control (MFA, least privilege).
  - Continuous monitoring, testing, and risk management.
- **Penalties**: Fines from **$5,000 to $100,000 per month** for non-compliance;  
  Risk of losing ability to process card payments.

---

### Children's Online Privacy Protection Act (COPPA)
- Protects **children under 13** from data collection without parental consent.  
- **Penalties**: Civil penalties up to **$50,120 per violation** (as of 2024).  

---

## Comparison Table

| Regulation | Scope / Data Protected | Applies To | Penalties |
|------------|------------------------|------------|-----------|
| **FERPA** | Student education records | Schools receiving U.S. Dept. of Ed funding | Loss of federal funding |
| **HIPAA** | PHI / ePHI (healthcare data) | Healthcare providers, insurers, business associates | Civil fines up to $1.5M/year; Criminal up to $250k + 10 yrs prison |
| **SOX** | Financial reporting & records | Publicly traded U.S. companies | Fines up to $5M; Up to 20 yrs prison |
| **PCI DSS** | Cardholder data | Merchants, service providers handling payment cards | $5k–$100k per month; Possible loss of card processing ability |
