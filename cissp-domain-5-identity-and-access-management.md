## Description  
CISSP Domain 5, **Identity and Access Management**, focuses on controlling access to systems, data, and resources.  
It covers principles like **identification, authentication, authorization, and access control models** to:  

- **Verify user identities** through secure authentication mechanisms  
- **Enforce least privilege and separation of duties** with proper authorization  
- **Control and monitor access** using discretionary, mandatory, and role-based models  
- **Support compliance** with organizational security policies and regulatory requirements

---

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
| **Type 2: Something you have** | Physical or virtual objects possessed by the user | Smart cards, tokens, mobile OTP apps |
| **Type 3: Something you are** | Biometric characteristics | Fingerprints, iris scans, facial recognition |

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

