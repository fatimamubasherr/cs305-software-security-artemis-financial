# cs305-software-security-artemis-financial
Secure software practices and vulnerability mitigation project for Artemis Financial, including HTTPS configuration, SHA-256 implementation, and OWASP dependency analysis.

CS 305 – Software Security Project

Artemis Financial Secure Software Practices

This repository contains my completed Secure Software Practices Report developed for Artemis Financial as part of CS 305 at Southern New Hampshire University.

⸻

 Client Summary

Artemis Financial is a financial services company seeking to modernize and secure its web application. The company required improved security measures to protect sensitive financial data in transit and to address vulnerabilities in third-party dependencies.

The primary objectives were:
	•	Configure HTTPS using SSL/TLS
	•	Generate and deploy a secure certificate
	•	Implement SHA-256 hashing for integrity verification
	•	Perform vulnerability analysis using OWASP Dependency-Check
	•	Refactor code to comply with secure development practices

___

 What I Did Well

I successfully implemented HTTPS using a self-signed SSL certificate and configured the application to run securely over port 8443. I also implemented SHA-256 hashing to support secure checksum verification and validated its functionality through browser testing.

Additionally, I conducted a dependency vulnerability scan using OWASP Dependency-Check. I interpreted the results carefully, distinguishing between vulnerabilities introduced by legacy dependencies and those related to my refactored code. No new vulnerabilities were introduced by my secure communication implementation.

Secure coding is critical because financial institutions handle highly sensitive data. A breach can damage customer trust, result in regulatory penalties, and cause financial loss. Strong software security directly supports a company’s operational stability, legal compliance, and reputation.

___

 Challenges and Insights

One of the most challenging aspects of the vulnerability assessment was interpreting third-party dependency findings. Some scan results required contextual understanding of how dependencies were used within the application. This reinforced the importance of not blindly suppressing vulnerabilities but instead carefully evaluating their relevance.

The most helpful part of this project was learning how layered security works in practice. Encryption in transit, hashing for integrity, dependency scanning, and proper configuration management all contribute to a stronger overall security posture.

___

 Increasing Layers of Security

Security was strengthened by:
	•	Enabling HTTPS using SSL/TLS
	•	Generating and deploying a PKCS12 keystore
	•	Implementing SHA-256 hashing
	•	Running OWASP Dependency-Check
	•	Refactoring code to follow secure practices

In future projects, I would continue using:
	•	OWASP Dependency-Check
	•	Static code analysis tools
	•	Maven security plugins
	•	Updated dependency version management
	•	Automated CI/CD security scans

___

 Ensuring Functionality and Security

After refactoring the application, I verified that:
	•	The application ran securely over HTTPS
	•	The hashing endpoint functioned correctly
	•	No new vulnerabilities were introduced
	•	Dependency scans reflected accurate results

I re-ran the application and the vulnerability scan to confirm system stability after changes.

___

 Tools and Practices Used
	•	Java Spring Boot
	•	HTTPS configuration with SSL/TLS
	•	SHA-256 hashing via Java security libraries
	•	Maven
	•	OWASP Dependency-Check
	•	Secure configuration practices

These tools are highly relevant in modern enterprise development environments and will be valuable in future security-focused roles.

___

 Portfolio Value

From this assignment, I can demonstrate to employers:
	•	Practical experience implementing HTTPS
	•	Understanding of hashing and cryptographic integrity
	•	Experience conducting vulnerability assessments
	•	Ability to interpret security scan results
	•	Knowledge of layered security architecture

This project reflects both secure coding practices and proactive vulnerability mitigation, which are essential skills in modern software engineering.

⸻

 Repository Contents
	•	cs305completedproject2.docx – Secure Software Practices Report
	•	README.md – Reflection and project summary
