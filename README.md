# My Internship Projects

Welcome to the repository for my internship projects completed during my cybersecurity internship at Extion Infotech. This repository contains two major tasks showcasing vulnerability assessment and data breach investigation skills.

## Table of Contents
- [Overview](#overview)
- [Folder Structure](#folder-structure)
- [Tasks](#tasks)
  - [Task 1: Network Vulnerability Assessment](#task-1-network-vulnerability-assessment)
  - [Task 2: Data Breach Investigation](#task-2-data-breach-investigation)
- [License](#license)

## Overview
This repository is a collection of projects demonstrating practical applications of cybersecurity techniques and tools. Each task focuses on identifying, analyzing, and mitigating security risks in different scenarios.

## Folder Structure
```
MyInternshipProjects-main/
├── LICENSE
├── README.md
├── Task 1 Network Vulnerability Assessment/
│   ├── Report.pdf
│   ├── Nessus Scan Results
├── Task 2 Data Breach Investigation/
│   ├── Report.pdf
│   ├── Forensic Evidence Logs
```

## Tasks

### Task 1: Network Vulnerability Assessment
**Objective**: To identify and analyze critical vulnerabilities in a network using Nessus and propose effective mitigation strategies.

**Key Highlights:**
- **Tools Used**: Nessus vulnerability scanner
- **Vulnerabilities Identified**: 118 total vulnerabilities, including:
  - 8 Critical (e.g., Ghostcat, Bind Shell Backdoor Detection)
  - 6 High (e.g., SSL Protocol Detection, Tomcat End-of-Life Issues)
  - 20 Medium
- **Mitigation Strategies**:
  - Upgrading outdated software (e.g., Apache Tomcat)
  - Disabling deprecated protocols (e.g., SSL v2/v3)
  - Implementing firewalls and robust access controls
- **Deliverables**:
  - Detailed Nessus scan report
  - Actionable recommendations to improve the network's security posture

### Task 2: Data Breach Investigation
**Objective**: To investigate a simulated data breach, identify its source, assess the scope, and propose remediation strategies.

**Key Highlights:**
- **Scenario**: A breach at ABC Secure Bank, affecting millions of customer records.
- **Analysis Steps**:
  1. Incident Analysis: SQL injection exploited through unpatched API endpoints.
  2. Forensic Analysis: Evidence collection, timeline reconstruction, and log analysis.
  3. Data Recovery: Identified exposed data (PII, transaction histories) and mitigated further exploitation.
  4. Compliance: Ensured GDPR and CCPA adherence.
  5. Communication: Notified stakeholders and customers, provided fraud monitoring.
- **Challenges**:
  - Delayed detection due to insufficient monitoring
  - Regulatory pressures for timely reporting
  - Regaining customer trust
- **Deliverables**:
  - Incident report and post-incident recommendations
  - Long-term mitigation plan, including automated patch management and employee training

## License
This repository is licensed under the terms of the [LICENSE](./LICENSE) file. Please review it for details on usage and distribution.

---

Feel free to explore the tasks and reach out for any queries or collaboration opportunities!
