CS  Portfolio Reflection
Artifact:
Artemis Financial Practices for Secure Software Report (Project Two)

Reflection:
Who was the client and what did they want?
Artemis Financial is a consulting company focused on financial planning. They wanted to modernize their web application and improve security. Specifically, they needed secure communication using HTTPS and data verification through checksums.

What did I do well and why is secure coding important?
I was able to identify and mitigate several vulnerabilities, especially in outdated libraries. Secure coding is critical to protect sensitive client data and maintain trust. It prevents attacks that could damage the company’s reputation or finances.

What was challenging or helpful?
The OWASP Dependency-Check tool was challenging at first, but very helpful in identifying risky dependencies.

How did I increase security layers?
I added SSL certificates for HTTPS, implemented SHA-256 for checksums, and validated dependencies. In the future, I would use automated scanners like SonarQube.

How did I ensure functionality and security?
I tested the application after refactoring, checked for new vulnerabilities using Dependency-Check, and verified that HTTPS worked properly.

Tools or practices for the future?
I used Maven, OWASP Dependency-Check, and Java Keytool. These are valuable tools for future security projects.

What can I show future employers?
I can show how I implemented encryption, identified vulnerabilities, and followed secure coding practices. This demonstrates hands-on security knowledge and practical development skills.
