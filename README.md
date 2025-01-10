# A Comprehensive Approach to Container Security: Attacks and Defenses

This project explores container security by implementing and analyzing attacks on Docker containers and devising tailored defense mechanisms. Through hands-on experiments, it addresses vulnerabilities such as CVE-2024-21626 (runC), CVE-2022-0847 (Dirty Pipe), and volume mount attacks. Advanced tools like Snyk, Trivy, and Grype are used for vulnerability scanning, emphasizing practical solutions to enhance Docker security.

## Key Features
- **Implementation of Attacks**:
  - **CVE-2024-21626**: Exploitation of runC vulnerabilities for container escape.
  - **CVE-2022-0847**: Dirty Pipe attack for privilege escalation.
  - **Volume Mount Attack**: Escalation using Docker volumes and setUID binaries.
- **Security Measures**:
  - Mitigation strategies for each attack.
  - Use of namespaces, access controls, and UID remapping for defense.
- **Vulnerability Scanning**:
  - Scanning with **Snyk**, **Trivy**, and **Grype** to detect and prioritize issues.

## Deliverables
1. Comprehensive implementation of Docker attacks and defenses.
2. Insights into vulnerability scanning tools and their effectiveness.
3. Documentation of challenges and solutions for containerized environments.

## Learning Objectives
- Understand container vulnerabilities and their exploitation.
- Implement robust security measures to safeguard Docker environments.
- Evaluate the performance and reliability of vulnerability scanning tools.
