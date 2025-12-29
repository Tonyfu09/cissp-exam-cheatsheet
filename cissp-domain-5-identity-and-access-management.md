# CISSP Domain 5 — Identity and Access Management

## Description  
CISSP Domain 5, **Identity and Access Management**, focuses on controlling access to systems, data, and resources.  
It covers principles like **identification, authentication, authorization, and access control models** to:  

- **Verify user identities** through secure authentication mechanisms  
- **Enforce least privilege and separation of duties** with proper authorization  
- **Control and monitor access** using discretionary, mandatory, and role-based models  
- **Support compliance** with organizational security policies and regulatory requirements
Use Control + Shift + m to toggle the tab key moving focus. Alternatively, use esc then tab to move to the next interactive element on the page.
No file chosen
Attach files by dragging & dropping, selecting or pasting them.
Editing cissp-exam-cheatsheet/cissp-domain-5-identity-and-access-management.md at main · Tonyfu09/cissp-exam-cheatsheet
 

## 5.1 Control physical and logical access to assets
- **Physical Access Controls** – Protect facilities and hardware.
  - Guards, mantraps, turnstiles
  - Badges, smart cards
  - Biometrics (fingerprint, iris, retina)
  - CCTV and monitoring systems

- **Logical Access Controls** – Protect systems and data.
  - User accounts and credentials
  - Authentication systems
  - Network and application access controls

Access control should follow **defense in depth**, ensuring multiple layers of protection.

## 5.2 Manage identification and authentication of people, devices, and services
- **Identification** – Claiming an identity (e.g., username, device ID).
- **Authentication** – Proving the claimed identity.

- **Authentication Factors**
  - Something you know – Password, PIN
  - Something you have – Token, smart card
  - Something you are – Biometrics
  - Somewhere you are – Location
  - Something you do – Behavior

- **Biometric Authentication**
  - Retina
  - Iris
  - Fingerprints
    - Ridges
    - Bifurcations
    - Whorls

- **Authentication Methods**
  - Synchronous – Time-based (e.g., TOTP)
  - Asynchronous – Challenge–response

Authentication supports **accountability** and must generate **audit trails**.

NIST Special Publication (SP) 800-63B, "Digital Identity Guidelines:- users should not be forced to change their passwords through the use of password expiration policies.


## 5.3 Integrate Identity as a Third-Party Service

- **Federated Identity** – Shared authentication across organizations.
- **Identity as a Service (IDaaS)** – Cloud-based identity management.

- **Common Technologies**
  - SAML – XML-based federation and Single Sign-On (SSO)
  - OAuth 2.0 – Authorization framework
  - OpenID Connect (OIDC) – Authentication layer on OAuth 2.0
  - JIT

Third-party identity integration requires proper **trust management** and **privacy controls**.

## 5.4 Implement and manage authorization mechanisms

Authorization determines **what an authenticated subject is allowed to do**.

- **DAC (Discretionary Access Control)** – Object owner determines access.
- **MAC (Mandatory Access Control)** – Central authority enforces security labels.
- **RBAC (Role-Based Access Control)** – Access based on job role.
- **ABAC (Attribute-Based Access Control)** – Access based on attributes and context.

Authorization enforces **least privilege** and **separation of duties**.

## 5.5 Manage the identity and access provisioning lifecycle

- **Provisioning** – Creating accounts and assigning access.
- **Access Modification** – Updating permissions as roles change.
- **Privilege Escalation** – Temporary or permanent elevation.
- **Deprovisioning** – Removing access when no longer required.

- **Provisioning Methods**
  - Discretionary account provisioning
  - Workflow-based provisioning (approval-driven)

Poor lifecycle management leads to **privilege creep** and **orphaned accounts**.

## 5.6 Implement authentication system

- **Single Sign-On (SSO)** – One authentication for multiple systems.
- **Federated Authentication** – Shared identity across domains.
- **Multi-Factor Authentication (MFA)** – Multiple authentication factors.

Authentication systems must protect **credentials**, **sessions**, and **tokens**.

## 5.7 Manage Access Control Monitoring and Reporting

- **Authentication Logs** – Track login attempts.
- **Authorization Logs** – Record access decisions.
- **Privileged Access Monitoring** – Track administrative actions.

Monitoring and reporting support:
- Accountability
- Incident detection
- Compliance requirements

## Scenario List

### 1. IAM Core Functions  
When implementing **Identity and Access Management (IAM)**, the team should distinguish between:  

| Term | Definition | Functional Use |
|------|------------|----------------|
| **Identification** | Claiming an identity (e.g., username, ID badge) | Establishes who the user is |
| **Authentication** | Verifying the claimed identity (e.g., password, biometrics, MFA) | Confirms the identity is valid |
| **Authorization** | Granting permissions to resources (e.g., RBAC, ABAC, DAC, MAC) | Ensures least privilege and proper access |
| **Accountability** | Tracking and monitoring actions (e.g., logs, audit trails) | Provides non-repudiation and traceability |

---

### 2. Authentication Factor Types  
When selecting **authentication factors**, consider the **Type 1, Type 2, and Type 3** categories:  

| Type | Definition | Examples |
|------|------------|----------|
| **Type 1: Something you know** | Information only the user should know | Passwords, PINs, security questions |
| **Type 2: Something you have** | Physical or virtual objects possessed by the user | Smart cards, tokens, mobile OTP apps, mobile phone |
| **Type 3: Something you are** | Biometric characteristics | Fingerprints, iris scans, facial recognition, landline phone number |

---

### 3. Access Control Models  
When applying **access control models**, the organization may use different approaches:  

| Model | Definition | Functional Use |
|-------|------------|----------------|
| **DAC (Discretionary Access Control)** | Resource owner decides who can access | Flexible but less secure |
| **MAC (Mandatory Access Control)** | Access based on system-enforced labels (e.g., classification) | Strong security, used in military/government |
| **RBAC (Role-Based Access Control)** | Access based on roles assigned to users | Simplifies management for enterprises |
| **ABAC (Attribute-Based Access Control)** | Access based on attributes and policies | Granular and dynamic, useful for cloud environments |


industrial control systems (ICSs)

Hybrid environments combine both hierarchical and compartmentalized environments so that security levels have sub-compartments.

RADIUS

passphrase


fingerprint minutiae
Ridges, bifurcations, and whorls

---

> 🧩 **Tip:** For the exam, remember —

