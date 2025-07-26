# Security Risk Assessment and Network Hardening Proposal

## Project Overview

A practical case study developed within the [Google Cybersecurity Professional Certificate](https://www.coursera.org/google-certificates/cybersecurity-certificate), focused on risk assessment following a security incident. This project's objective was to inspect the network of an organization that suffered a data breach, identify critical vulnerabilities, and propose an effective hardening plan to prevent future attacks.

---

## The Scenario

The analysis was based on an incident where a social media organization suffered a major data breach, which compromised its customers' personal information (names and addresses). Following the incident, a network inspection revealed four key vulnerabilities that required immediate remediation:

1.  **Shared Passwords:** The organization's employees were sharing access credentials with each other.
2.  **Default Credentials:** The administrator password for the main database was set to its factory default value.
3.  **Open Firewalls:** The firewalls had no rules implemented to filter incoming and outgoing network traffic.
4.  **Lack of MFA:** Multi-Factor Authentication (MFA) was not in use on any of the organization's systems.

---

## Analysis Methodology

To investigate and respond to the scenario, the following methodology was applied:

* **Network Inspection:** Analysis of the corporate network configuration to identify security flaws and weaknesses that led to the incident.
* **Vulnerability Analysis:** Assessment of the four identified vulnerabilities to determine the risk and potential impact of each one.
* **Best Practices Consultation:** Utilization of a knowledge base of hardening tools and methods to select the most effective solutions for the identified flaws.
* **Technical Documentation:** Consolidation of all findings and recommendations into a formal Security Risk Assessment Report.

---

## Security Risk Assessment Report (PDF)

The complete report, detailing the analysis and technical justifications for each recommendation, can be found at the link below.

* 📄 **[Security Risk Assessment Report - English Version (PDF)](https://github.com/cleyandson/case-study-security-risk-assessment/blob/8e753a307c668982ad9928132313212dc5cac008/Documents/%5BEN%5D%20Security%20risk%20assessment%20report.pdf)**

---

## Hardening Recommendations

Based on the root cause analysis, the following remediation actions were recommended to mitigate the identified risks:

* **Implementation of Password Policies:** Adopting NIST recommendations for using "salting" and "hashing" methods on passwords. This prevents attackers from easily guessing passwords and directly addresses the issue of default and shared credentials.
* **Firewall Maintenance:** Implementing a process for regularly checking and updating the firewall's security configurations. Rules should be updated to filter abnormal network traffic and protect against external attacks.
* **Enablement of Multi-Factor Authentication (MFA):** Implementing MFA as an additional security layer. This measure requires users to confirm their identity in two or more ways, protecting against unauthorized access even if a password is compromised.

---

## Skills Demonstrated

This project highlights the following essential cybersecurity skills:

-   ✅ **Security Risk Assessment**
-   ✅ **Vulnerability Analysis**
-   ✅ **Network Hardening**
-   ✅ **Security Policy and Control Recommendation**
-   ✅ **Technical Report Writing**
-   ✅ **Root Cause Analysis (RCA)**

---

## Contact

* **LinkedIn:** [Cleyandson Fragoso](https://www.linkedin.com/in/cleyandson-fragoso/)
* **Email:** cleyandsontech@gmail.com
