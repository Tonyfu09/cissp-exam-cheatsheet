# CISSP Domain 3 — Security Architecture and Engineering

## Description  
CISSP Domain 3, **Security Architecture and Engineering**, forms the foundation for designing and implementing secure systems.  
It covers principles like **security models, architecture frameworks, cryptography, and physical security** to:  

- **Protect assets and information** by enforcing confidentiality, integrity, and availability  
- **Ensure systems are resilient** against attacks and vulnerabilities  
- **Support compliance** with organizational policies, laws, and regulations

---

## 3.1 Research, implement, and manage engineering processes using secure design principles
- **Security by Design** – Embed security from the start of system development  
- **Privacy by Design (PbD)** – Incorporate privacy and data protection proactively  
- **Zero Trust Model** – Assume all devices, users, and networks are untrusted by default  
- **Segregation of Duties / Two-Person Control** – Require at least two authorized individuals to perform critical operations to reduce risk of fraud or error

Threat modeling forcus on attackers, assets and software.

---

## 3.2 Understand the fundamental concepts of security models
Biba - Simple security property
Star Model
Bell-LaPadula
Brewer-Nash

---

## 3.3 Select controls based upon systems security requirements
Primary distinction of the current Common Criteria (CC)

---

## 3.5 Assess and mitigate the vulnerabilities of security architectures, designs, and solution elements
Polyinstantiation
Aggregation
Provisioning
Referential integrity

---

## 3.6 Select and determine cryptographic solutions
- **Encryption algorithm modes**:
  - **ECB (Electronic Codebook)** – Simple but vulnerable to pattern analysis  
  - **CBC (Cipher Block Chaining)** – Stronger; each block depends on the previous block  
  - **GCM (Galois/Counter Mode)** – Provides confidentiality and integrity
- **Digital Signature Standard (DSS)** – Approves three encryption algorithms for digital signatures:
  1. **DSA (Digital Signature Algorithm)**  
  2. **RSA**  
  3. **ECDSA (Elliptic Curve Digital Signature Algorithm)**  

- **key escrow system**:

---

## 3.7 Understand methods of cryptanalytic attacks
- **Side-Channel Attack** – Exploits physical implementation (timing, power consumption, EM leaks)  
- **Brute-Force Attack** – Exhaustively tries all possible keys  
- **Timing Attack** – Measures execution time to infer secrets  
- **Fault Injection Attack** – Intentionally induces errors to reveal information  

Ciphertext only
Chosen plaintext
Known plaintext
Fault injection

---

## 3.9 Design site and facility security controls
TEMPEST,  Aviod Attack
Preaction

---

## Scenario List

Q1 Data Sovereignty
A global organization wants to migrate HR data to a cloud provider. The data includes employee personal information from the EU. Which factor must the security architect consider first to ensure compliance with data sovereignty requirements?

Q2 VM Escape Protection 
A security architect is designing a virtualized environment for a financial institution. To reduce the risk of VM escape attacks, which control is MOST appropriate to implement?


Q3 Guest OS Malware Scanning
A company needs to detect malware within virtual machines without relying solely on agents installed inside the guest OS. Which security approach BEST meets this requirement?



Q4 Containerization
A development team is transitioning from traditional VMs to containers. What is the PRIMARY security advantage of using containerization in this scenario?



Q5 Two-Person Control / Two-Person Integrity
A critical operation in a nuclear facility must never be performed by a single administrator. Which control BEST enforces this requirement?



Q6 Encryption Algorithm Modes
A security engineer must choose an encryption mode for protecting large blocks of data. Which mode should be avoided due to pattern leakage when encrypting repetitive plaintext?



Q7 Privacy by Design (PbD)
A company is planning a new health-tracking mobile application. To incorporate Privacy by Design, which action should the security team take FIRST?



Q8 Methods of Cryptanalytic Attacks
An attacker collects multiple plaintext–ciphertext pairs of the same message encrypted with different keys. Which type of cryptanalytic attack is being performed?


Q9 Side-Channel Attack

A threat actor measures CPU power fluctuations to infer encryption key material. What type of attack does this represent?



Q10 Brute-Force Attack
Which attack method attempts every possible key or password combination without leveraging prior knowledge of the system?



Q11 Timing Attack
An attacker observes slight differences in system response time during cryptographic operations to guess secret keys. What type of attack is this?



Q12 Fault Injection Attack
A hardware researcher manipulates voltage levels on a microcontroller to cause errors and extract sensitive information. Which attack method is being used?



Q13 Zero Trust & Endpoint Proliferation
An enterprise has rapidly expanding numbers of BYOD and IoT endpoints. According to Zero Trust principles, what is the MOST important security control to implement?



Q14 Digital Signature Standard (DSS)
According to the U.S. Digital Signature Standard (DSS), which set of algorithms is approved for creating digital signatures?
Data sovereignty



---

> 🧩 **Tip:** For the exam, remember —
