# CISSP Domain 2 — Asset Security

## Description  
CISSP Domain 2, **Asset Security**, focuses on identifying, classifying, handling, and protecting organizational information and assets throughout their lifecycle.  
It emphasizes understanding **data ownership, privacy, classification, and retention policies** to:  
- Ensure data is protected according to its sensitivity  
- Maintain compliance with regulatory and contractual requirements  
- Support confidentiality, integrity, and availability across all assets  

---

## 2.1 Identify and Classify Information and Assets  

Organizations must classify data to ensure appropriate levels of protection.  
Common **data classification categories** include:

| Classification | Description | Example |
|----------------|--------------|----------|
| **Public** | Freely available information, minimal impact if disclosed | Press releases, marketing materials |
| **Private** | Internal use only, limited sharing | Internal memos, business contact lists |
| **Sensitive** | Could harm organization or individuals if disclosed | HR data, internal audit findings |
| **Proprietary** | Valuable business information unique to the organization | Source code, formulas, internal designs |
| **Critical** | Vital to organizational operations | Customer databases, authentication systems |
| **Confidential** | Restricted to authorized individuals only | Financial reports, strategic plans |

single-level security environment

---

## 2.2 Determine and Maintain Ownership  
Roles related to data management:

| Role | Responsibility |
|------|----------------|
| **Data Owner** | Determines classification level and access authorization |
| **Data Custodian** | Implements and maintains security controls on behalf of the owner |
| **User** | Follows acceptable use and protection procedures |

---

## 2.3 Protect Privacy and Ensure Appropriate Retention  

| Concept | Description |
|----------|-------------|
| **Data Retention** | Defines how long data is stored and when it should be destroyed |
| **Data Remanence** | Residual data left after deletion (can be recovered if not sanitized) |
| **Data Disposal** | Methods include overwriting, degaussing, or physical destruction |
| **Data Minimization** | Collect only necessary data for a defined purpose |

---

## 2.4 Manage Data Lifecycle  

The **Data Lifecycle** includes the stages from creation to destruction:  

| Phase | Description | Example |
|-------|-------------|----------|
| **1. Creation / Collection** | Data is generated or gathered | User fills online form |
| **2. Storage** | Data is saved securely | Database, cloud storage |
| **3. Use** | Data accessed by authorized users | Reporting or analytics |
| **4. Sharing / Distribution** | Data transmitted internally or externally | Emailing encrypted files |
| **5. Archival** | Long-term storage for compliance or future reference | Legal retention storage |
| **6. Destruction** | Secure deletion or disposal | Shredding disks, degaussing |
| **7. Disintegration** | | | 
| **Note:** | Unused space in a cluster can retain residual data; proper sanitization is essential. |  |

Spare sectors, bad sectors, and space provided for wear leveling on SSDs

---

## 2.5 Apply Data Security Controls  

| Control Type | Description | Example |
|---------------|-------------|----------|
| **Access Controls** | Restrict who can view or modify data | Role-Based Access Control (RBAC) |
| **Encryption** | Protect data confidentiality in transit and at rest | AES-256 for disk encryption |
| **Masking / Tokenization** | Replace sensitive data with non-sensitive equivalents | Masking credit card numbers |
| **Hashing** | Ensure integrity of data | Storing password hashes |
| **Labeling** | Identify classification level on documents | “Confidential” watermarks |
| **Data Loss Prevention (DLP)** | Monitor and prevent unauthorized data transfers | Email DLP tools |

---

## 2.6 Determine Data Security Controls and Compliance Requirements  

Key compliance areas may include:  
- **GDPR** – EU privacy and personal data protection  
- **HIPAA** – U.S. healthcare data protection  
- **PCI DSS** – Payment data security  
- **SOX** – Financial record accuracy and retention  

| Concept | Description | Example |
|----------|-------------|----------|
| **Data Masking** | Hide sensitive elements of data for testing or analytics | Show only last 4 digits of a card number |
| **Data Encryption** | Protect data during transmission and storage | Use TLS for web traffic |
| **Anonymization** | Remove identifiers to prevent tracing back to individuals | Removing PII before analytics |
| **Pseudonymization** | Replace identifiers with pseudonyms | User_001 instead of real name |
| **Randomized masking** |

---

## Scenario List  

1. **A data custodian** is responsible for implementing encryption and backup measures, but does not decide access permissions — that’s the **data owner’s** role.  

2. **A data analyst** needs to test production data without exposing sensitive information — apply **data masking** to anonymize values.  

3. **An organization discovers residual files** in unallocated disk space after deletion — this is an issue of **data remanence**, requiring proper **sanitization** methods.  

4. **Public vs. Confidential confusion** — a staff member shares internal design documents externally, violating classification rules under **confidential data policy**.

---

> 🧩 **Tip:** For the exam, remember — **ownership defines classification**, **custodians enforce controls**, and **users comply with policies**.
