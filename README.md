# Cybersecurity Prompt Guide

This guide provides various prompt examples for using WhiteRabbitNeo in different cybersecurity scenarios. Each table focuses on a specific objective and contains prompts that help maximize the tool's effectiveness for learning, testing, and applying cybersecurity techniques.

---

## Use Case Prompts

| **Use Case**                       | **Prompt Example**                                                       | **Description**                                                                                                       |
|------------------------------------|--------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| **Identifying Common Vulnerabilities**    | "List common vulnerabilities in web applications related to OWASP Top 10." | Useful for bug bounty hunters looking to explore vulnerabilities aligned with industry standards like OWASP.         |
| **Detecting Misconfigurations**           | "Identify typical SSH misconfigurations that attackers exploit."         | Helps you find weak configurations in protocols like SSH, which can expose systems to unauthorized access.           |
| **Simulating Attack Techniques**          | "How would an attacker exploit an SQL injection vulnerability on a login page?" | Provides insights into how an exploit might unfold, helping to understand attack vectors and test for similar issues. |
| **Testing APIs for Vulnerabilities**      | "What are common security weaknesses in REST APIs, and how can they be detected?" | Focuses on potential vulnerabilities in API endpoints, useful for testing API security.                                |
| **Exploit Payload Generation**            | "Generate example payloads for testing cross-site scripting (XSS) vulnerabilities in forms." | Ideal for creating safe test payloads in environments like bug bounties, simulating what an attacker might use in a real XSS attack. |
| **Remediation Advice**                    | "What are the best practices for securing open ports in a Linux server?" | Offers defensive strategies and security hardening tips to secure Linux environments and prevent unauthorized access.  |
| **Learning Vulnerability Analysis**       | "Explain how to analyze a CVE for potential impact and exploitability." | Great for learning how to evaluate vulnerabilities (e.g., from CVE reports) and understand their potential risks in a specific environment. |
| **Simulating DDoS Attack Impact**        | "Describe how a DDoS attack would impact a typical web application and suggest mitigation strategies." | Helps you learn about the mechanics of a DDoS attack and strategies for mitigation, relevant for both offensive and defensive learning in cybersecurity. |
| **Assessing Cloud Security Risks**        | "What security risks are common in cloud environments, especially around identity and access management?" | Useful for identifying potential risks unique to cloud setups and understanding protective measures.                  |
| **Evaluating Network Security**           | "List the common vulnerabilities in network setups for small businesses and how to test for them." | Helps identify weaknesses in network configurations, which are often exploited in smaller setups.                     |
| **Learning Vulnerability Remediation**    | "Provide a step-by-step guide to remediate an insecure deserialization vulnerability." | Educates on how to address specific vulnerabilities, which is useful when working on resolving issues in code or systems. |
| **Exploring Penetration Testing Tools**   | "Explain how Metasploit could be used to simulate an attack on an outdated web server." | Offers guidance on using tools like Metasploit for controlled penetration testing and understanding vulnerabilities.     |

---

## Overview of Prompt Categories

| **Category**                    | **Description**                                                                                                             |
|---------------------------------|-----------------------------------------------------------------------------------------------------------------------------|
| **Identifying Common Vulnerabilities**  | Prompts focused on uncovering standard vulnerabilities, especially in frequently targeted systems like web and IoT.        |
| **Detecting Misconfigurations**         | Prompts that assist in finding potential weaknesses in system and application configurations.                               |
| **Simulating Attack Techniques**        | Prompts for understanding or recreating various attack types, aiding in defensive strategy development.                    |
| **Testing APIs for Vulnerabilities**    | API-specific prompts to help uncover security risks unique to web and mobile API environments.                             |
| **Exploit Payload Generation**          | Prompts for generating payloads to test known vulnerabilities safely and in controlled conditions.                         |
| **Remediation Advice**                  | Prompts designed to provide mitigation strategies and secure configurations for specific risks.                            |
| **Learning Vulnerability Analysis**     | Prompts aimed at guiding users through identifying and analyzing vulnerabilities, including CVEs and impact assessments.    |

---

## 1. Identifying Common Vulnerabilities

| **Objective**                     | **Prompt Example**                                                       | **Purpose**                                                                                                           |
|-----------------------------------|--------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| **Web Application Vulnerabilities** | "List vulnerabilities common in web applications that are in OWASP Top 10 2023." | Identify the latest web security weaknesses for bug bounty or pen testing.                                           |
| **Server Security Issues**        | "Describe vulnerabilities found in Apache and Nginx web servers."        | Provides insights into common server issues to focus efforts on specific server types.                                 |
| **Database Vulnerabilities**      | "Explain vulnerabilities associated with SQL databases in production."   | Understand risks associated with SQL databases, commonly targeted in exploits.                                       |
| **Mobile App Security Risks**     | "What are the typical vulnerabilities in mobile applications?"           | Explore common vulnerabilities in Android and iOS apps.                                                              |
| **IoT Device Vulnerabilities**    | "Identify common vulnerabilities in IoT devices and their risks."        | Understand weaknesses in IoT, often exploited due to limited security controls.                                       |

---

## 2. Detecting Misconfigurations

| **Objective**                     | **Prompt Example**                                                       | **Purpose**                                                                                                           |
|-----------------------------------|--------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| **SSH Misconfigurations**         | "List common SSH misconfigurations that can be exploited."               | Identify setup issues that can lead to unauthorized SSH access.                                                       |
| **Web Server Configurations**     | "What web server misconfigurations are often overlooked and risky?"      | Focuses on risky web server setups, particularly useful for securing Apache, Nginx, etc.                              |
| **Database Security Configurations** | "Explain typical MySQL and PostgreSQL misconfigurations."              | Understand database configuration issues, relevant for audits and pen testing.                                        |
| **Cloud Service Misconfigurations** | "Identify risky misconfigurations in AWS S3 and IAM."                   | Explore cloud-specific misconfigurations, especially in AWS environments.                                             |
| **Firewall Rule Weaknesses**      | "What common misconfigurations in firewall rules can create vulnerabilities?" | Learn how firewall configurations may inadvertently expose systems to risks.                                      |

---

## 3. Simulating Attack Techniques

| **Objective**                     | **Prompt Example**                                                       | **Purpose**                                                                                                           |
|-----------------------------------|--------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| **SQL Injection Simulation**      | "How would an attacker exploit SQL injection on a login form?"           | Gain insight into SQL injection attacks, useful for learning preventive methods.                                      |
| **Cross-Site Scripting (XSS)**    | "Describe how a cross-site scripting attack might be carried out on a comment section." | Simulate a common XSS attack, valuable for web security testing.                            |
| **Remote Code Execution**         | "Explain how an attacker might exploit a remote code execution vulnerability." | Learn how RCE vulnerabilities are exploited, essential for defensive measures.                              |
| **Privilege Escalation Techniques** | "How might an attacker escalate privileges on a Linux server?"          | Understand privilege escalation methods, particularly for red team exercises.                                         |
| **Command Injection Simulation**  | "Describe a scenario where command injection could be exploited."        | Learn about command injection and effective defenses.                                                                |

---

## 4. Testing APIs for Vulnerabilities

| **Objective**                     | **Prompt Example**                                                       | **Purpose**                                                                                                           |
|-----------------------------------|--------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| **API Authentication Weaknesses** | "What are the common weaknesses in API authentication?"                  | Explore authentication vulnerabilities in API endpoints.                                                              |
| **Broken Access Control**         | "Explain how broken access control can affect APIs."                     | Learn how insufficient access control can expose APIs.                                                                |
| **Input Validation Issues**       | "Describe potential input validation issues in REST APIs."               | Identify input handling flaws in APIs, a common vulnerability.                                                        |
| **Rate Limiting Weaknesses**      | "What vulnerabilities can result from insufficient rate limiting in APIs?" | Understand the importance of rate limiting in APIs for preventing abuse.                                     |
| **Error Handling Vulnerabilities**| "How can improper error handling in APIs lead to security risks?"        | Understand error handling risks that may expose sensitive information.                                                |

---

## 5. Exploit Payload Generation

| **Objective**                     | **Prompt Example**                                                       | **Purpose**                                                                                                           |
|-----------------------------------|--------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| **XSS Payloads**                  | "Generate example XSS payloads for testing a comment section."           | Useful for testing XSS vulnerabilities in web app forms.                                                              |
| **SQL Injection Payloads**        | "Provide SQL injection payloads for login forms in testing environments." | Safe testing of SQL vulnerabilities in controlled settings.                                                          |
| **Command Injection Payloads**    | "Give example payloads for testing command injection in PHP."            | Useful for understanding and testing command injection vulnerabilities.                                               |
| **CSRF Payloads**                 | "Create CSRF payloads for testing form submissions."                     | For testing CSRF vulnerabilities in web applications.                                                                |
| **LDAP Injection Payloads**       | "What are some example payloads to test for LDAP injection vulnerabilities?" | Evaluating LDAP injection risks in applications using directory services.                               |

---

## 6. Remediation Advice

| **Objective**                     | **Prompt Example**                                                       | **Purpose**                                                                                                           |
|-----------------------------------|--------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| **Securing SSH**                  | "What are the best practices for securing SSH access?"                  | Provides actionable steps to enhance SSH security.                                                                   |
| **Web Application Security**      | "List security measures for securing a web application."                | Offers comprehensive security recommendations for web applications.                                                  |
| **Database Hardening**            | "What are key steps to harden a MySQL database?"                        | Learn how to secure databases against common attacks.                                                                |
| **Network Security Measures**     | "What practices can strengthen network security for small businesses?"  | Tailored advice for enhancing network security in smaller organizations.                                             |
| **Cloud Security Best Practices** | "Describe best practices for securing cloud environments."              | Provides essential strategies for cloud security, particularly for IaaS and PaaS setups.                          |

---

## 7. Learning Vulnerability Analysis

| **Objective**                     | **Prompt Example**                                                       | **Purpose**                                                                                                           |
|-----------------------------------|--------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| **CVE Analysis**                  | "How do I analyze a CVE for potential risks?"                          | Guides on assessing the impact of CVEs and prioritizing vulnerabilities for remediation.                             |
| **Risk Assessment Techniques**    | "What methods are used in vulnerability risk assessment?"                | Understanding risk assessment methodologies in vulnerability management.                                            |
| **Exploitability Evaluation**     | "Explain how to determine if a vulnerability is exploitable."           | Educates on evaluating the exploitability of identified vulnerabilities.                                            |
| **Impact Analysis**               | "What factors influence the impact of a vulnerability?"                 | Understanding the variables that affect vulnerability impact in various contexts.                                    |
| **Vulnerability Scoring**         | "How is CVSS used to score vulnerabilities?"                            | Learn about the Common Vulnerability Scoring System (CVSS) and its application in vulnerability management.          |

---

## 8. Simulating DDoS Attack Impact

| **Objective**                     | **Prompt Example**                                                       | **Purpose**                                                                                                           |
|-----------------------------------|--------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| **DDoS Impact Analysis**          | "Describe the impact of a DDoS attack on a typical e-commerce site."   | Understand the consequences of DDoS attacks on business operations.                                                |
| **Mitigation Strategies**         | "What are effective strategies for mitigating DDoS attacks?"            | Explore defensive measures that can minimize DDoS attack impacts.                                                  |
| **Incident Response Planning**    | "How should organizations prepare for potential DDoS attacks?"          | Learn about preparing and planning for DDoS incidents to minimize disruption.                                      |
| **Traffic Analysis**              | "What methods are used to analyze traffic patterns during DDoS attacks?" | Understand how to analyze network traffic for signs of DDoS activity.                                               |
| **Legal Considerations**          | "What legal implications should organizations consider regarding DDoS attacks?" | Learn about the legal landscape related to DDoS attacks and responses.                                               |

---

## 9. Assessing Cloud Security Risks

| **Objective**                     | **Prompt Example**                                                       | **Purpose**                                                                                                           |
|-----------------------------------|--------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| **IAM Risks**                     | "What IAM risks are common in cloud environments?"                       | Explore identity and access management vulnerabilities specific to cloud platforms.                                   |
| **Data Protection Strategies**    | "How should data be protected in cloud storage?"                         | Learn strategies for securing data in cloud storage environments.                                                    |
| **Shared Responsibility Model**   | "Explain the shared responsibility model in cloud security."            | Understand the division of security responsibilities between cloud providers and clients.                             |
| **Compliance Challenges**         | "What compliance challenges do organizations face in the cloud?"         | Identify compliance issues and requirements for businesses operating in cloud environments.                          |
| **Threat Modeling**               | "How can threat modeling be applied to cloud architecture?"              | Learn how to assess potential threats in cloud-based systems using threat modeling techniques.                       |

---

## 10. Evaluating Network Security

| **Objective**                     | **Prompt Example**                                                       | **Purpose**                                                                                                           |
|-----------------------------------|--------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| **Network Vulnerabilities**        | "What are common vulnerabilities in small business networks?"           | Identify weaknesses in network setups that small businesses typically overlook.                                     |
| **Testing Network Security**      | "How can I test the security of a local network?"                       | Explore methods for conducting network security assessments and audits.                                            |
| **Wi-Fi Security Risks**          | "What are the risks associated with poorly secured Wi-Fi networks?"     | Learn about common Wi-Fi vulnerabilities and how to mitigate them.                                                  |
| **Firewall Testing**              | "How can I evaluate the effectiveness of firewall rules?"               | Understand techniques for testing firewall configurations and identifying weaknesses.                                |
| **Incident Response in Networks** | "What should be included in a network incident response plan?"          | Learn how to create a comprehensive incident response plan tailored for network security incidents.                  |

---

## 11. Learning Vulnerability Remediation

| **Objective**                     | **Prompt Example**                                                       | **Purpose**                                                                                                           |
|-----------------------------------|--------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| **Remediating XSS**              | "What steps should be taken to remediate an XSS vulnerability?"         | Detailed steps to secure applications against XSS vulnerabilities.                                                  |
| **Fixing SQL Injection**          | "How can I prevent SQL injection attacks on my application?"            | Guides on securing applications against SQL injection risks.                                                          |
| **Addressing CSRF**               | "What measures should be implemented to mitigate CSRF vulnerabilities?" | Comprehensive strategies for preventing Cross-Site Request Forgery (CSRF) attacks.                                    |
| **Secure Coding Practices**       | "List secure coding practices to follow during development."            | Promotes coding practices that help prevent vulnerabilities during application development.                           |
| **Patch Management**              | "How can organizations manage and implement software patches effectively?" | Strategies for maintaining software security through timely patching and updates.                                   |

---

## 12. Exploring Penetration Testing Tools

| **Objective**                     | **Prompt Example**                                                       | **Purpose**                                                                                                           |
|-----------------------------------|--------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| **Using Metasploit**              | "How can Metasploit be used to test web applications?"                  | Provides insight into using Metasploit for web application security testing.                                         |
| **Burp Suite Functionality**      | "Explain the features of Burp Suite for penetration testing."           | Understand the capabilities of Burp Suite and how to leverage it for security testing.                              |
| **Nmap Usage**                    | "How can Nmap be used for network mapping and vulnerability scanning?"   | Insight into using Nmap for reconnaissance and vulnerability assessment.                                             |
| **Wireshark Applications**        | "Describe how Wireshark can be utilized for network analysis."           | Learn how to use Wireshark for monitoring and analyzing network traffic.                                            |
| **Kali Linux Tools**              | "What are essential tools included in Kali Linux for pentesters?"       | Overview of key penetration testing tools available in Kali Linux.                                                  |

---

