# CISSP Domain 6 — Security Assessment and Testing

## Description
**Domain 6** focuses on the design, implementation, and analysis of **security assessment and testing programs**.  
The goal is to ensure that systems, applications, and processes are **secure, compliant, and functioning as intended**.

This domain includes:
- Developing and validating **assessment and audit strategies**
- Conducting **security control testing**
- Collecting and analyzing **security process data**

---

## Scenario List

### Example Scenario 1
During a code review, the organization uses a **formal inspection process** to identify software defects before deployment.  
This method helps ensure consistent code quality and compliance with development standards.

### Example Scenario 2
A security team uses **synthetic transactions** to test the performance and reliability of a web application without impacting real users.

---

## 6.1 Design and Validate Assessment, Test, and Audit Strategies

### Frameworks and Methodologies
| Framework | Purpose | Description |
|------------|----------|--------------|
| **ITIL (Information Technology Infrastructure Library)** | Service management | Provides best practices for aligning IT services with business needs, including change, incident, and problem management. |
| **COBIT (Control Objectives for Information and Related Technologies)** | IT governance | Defines control objectives for aligning IT processes with business goals and risk management. |
| **ISO/IEC 27001** | Information Security Management System (ISMS) | Establishes, implements, monitors, and improves security processes. |

### Key Concepts
- **Assessment Strategy:** Defines what to assess (controls, systems, processes) and how to assess them.  
- **Audit Strategy:** Ensures compliance with policies, procedures, and regulatory requirements.  
- **Testing Strategy:** Validates security control effectiveness and identifies potential weaknesses.

SOC 1 engagements assess the organization's controls that might impact the accuracy of financial reporting. SOC 2 and 3 engagements extend into controls protecting confidentiality, integrity, and availability more generally.

---

## 6.2 Conduct Security Control Testing

### Fagan Inspection (Formal Code Review)
A **structured software inspection process** that ensures code quality and defect detection early in the SDLC.

**Six Steps:**
1. **Planning** – Define objectives, participants, and materials.  
2. **Overview** – Review purpose and scope with the team.  
3. **Preparation** – Review materials individually.  
4. **Inspection** – Conduct formal review meeting.  
5. **Rework** – Correct identified issues.  
6. **Follow-Up** – Verify that corrections were made and objectives met.

---

### Development Models and Testing Integration
| Model | Description | Security Testing Approach |
|--------|--------------|----------------------------|
| **Waterfall Model** | Sequential phases: requirements → design → implementation → testing → maintenance. | Security reviews occur at each phase gate. |
| **Agile Development** | Iterative, fast-paced cycles (sprints). | Integrate continuous security testing (DevSecOps, automated scans). |
| **Spiral Model** | Combines iterative and risk-based design. | Conduct risk assessments and testing in each iteration. |

---

### Specialized Testing Techniques
| Method | Description | Example |
|---------|--------------|----------|
| **Synthetic Transactions** | Simulated user actions with known results to test performance and availability. | Scripted login and purchase flow on an e-commerce app. |
| **Misuse Case Testing** | Focuses on how a system can be misused or attacked. | Attempting unauthorized data access to test validation. |
| **Interface Testing** | Validates communication between modules. | API fuzzing and endpoint validation. |
| **Parallel Testing** | Compare new and old systems using same input/output to confirm consistency. | Migrating legacy app to new cloud platform. |

### Security Control Tools
Metasploit

test coverage analysis technique
Branch coverage

---

## 6.3 Collect Security Process Data (Technical and Administrative)

### Purpose
Collecting security process data provides visibility into:
- Control effectiveness  
- Process efficiency  
- Risk posture over time  

### Common Data Sources
| Category | Examples |
|-----------|-----------|
| **Technical** | Vulnerability scans, IDS/IPS alerts, SIEM logs, patch status |
| **Administrative** | Policy compliance audits, awareness training completion, access review reports |

backup verification process 

---

## Business Impact Analysis (BIA) Steps
BIA is part of **risk management** and is critical in evaluating the **impact of security incidents**.

| Step | Description |
|------|--------------|
| **1. Identify Critical Functions** | Determine which business processes are essential to operations. |
| **2. Identify Dependencies** | Understand systems, personnel, and third-party dependencies. |
| **3. Determine Impact** | Assess financial, operational, and reputational consequences. |
| **4. Establish RTO/RPO** | Define **Recovery Time Objective (RTO)** and **Recovery Point Objective (RPO)**. |
| **5. Prioritize Recovery** | Develop plans to restore critical functions based on impact and risk. |

---

### Key Performance Indicators (KPIs)
KPIs are used to measure security performance and process efficiency.

| KPI | Description | Purpose |
|-----|--------------|----------|
| **Time to Remediate Vulnerabilities** | Average time between vulnerability discovery and patching. | Measures response efficiency. |
| **Number of Open Findings** | Outstanding audit or scan findings not yet remediated. | Tracks control effectiveness. |
| **Incident Response Time** | Time taken to detect and contain incidents. | Evaluates readiness and detection capabilities. |
| **Patch Compliance Rate** | Percentage of systems updated to the latest patch level. | Reflects operational hygiene. |

---

## Summary
Domain 6 emphasizes **continuous assessment and validation** of security programs to ensure that:  
- Controls are properly implemented and effective,  
- Systems comply with policies and regulations, and  
- Risks are identified, measured, and mitigated in a timely manner.  

Effective testing and data collection help organizations make **evidence-based decisions** and continuously improve their security posture.

---

> 🧩 **Tip:** For the exam, remember —
