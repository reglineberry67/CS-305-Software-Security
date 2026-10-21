# CS-305-Software-Security



## CS 305: Software Security

### Portfolio Artifact: Artemis Financial Practices for Secure Software Report

This repository contains my completed Practices for Secure Software Report for Artemis Financial. The project demonstrates my experience identifying software vulnerabilities, implementing security improvements, and testing an application to evaluate its functionality and security.

### Reflection

**1. Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?**

Artemis Financial was a financial consulting company that wanted to improve the security of its software application. The company needed stronger protection for sensitive financial information and secure communication between its application and users. My responsibility was to identify potential security vulnerabilities and implement improvements to help protect the application and its data.

**2. What did you do well when you found your client's software security vulnerabilities? Why is it important to code securely? What value does software security add to a company's overall well-being?**

I did well identifying potential vulnerabilities by reviewing the application's dependencies and using the OWASP Dependency-Check tool. This helped me understand how outdated or vulnerable software components can create security risks. Secure coding is important because it helps prevent unauthorized access, protects sensitive information, and reduces the possibility of security breaches. Strong software security also helps companies maintain customer trust and avoid financial losses.

**3. Which part of the vulnerability assessment was challenging or helpful to you?**

One of the most challenging parts was configuring Maven and running the dependency-check tool successfully. I encountered build errors and compatibility issues that required troubleshooting. Although this was frustrating at times, it helped me become more comfortable reading error messages, adjusting project configurations, and understanding how different software components work together.

**4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?**

I increased security by implementing HTTPS using a self-signed certificate and adding SHA-256 hashing to the application. I also configured the application to read its keystore password from an environment variable instead of storing the password directly in the source code. In future projects, I would use vulnerability-scanning tools, review dependency reports, and follow established secure coding practices to determine which security risks need attention.

**5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?**

I tested the application by running it in Eclipse and verifying that the HTTPS endpoint displayed the expected SHA-256 checksum. I also ran Maven builds to check that the project compiled and its tests passed. After making changes, I ran OWASP Dependency-Check to examine the application's dependencies for known vulnerabilities. The scan identified vulnerabilities that would require additional remediation, so I learned that successful functional testing does not automatically mean an application is completely secure.

**6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?**

The tools I used included Eclipse, Java, Maven, OWASP Dependency-Check, Java keytool, and GitHub. I also practiced using SHA-256 hashing, configuring HTTPS, managing security certificates, and protecting passwords through environment variables. These tools and practices will be useful in future software development projects because they help identify security weaknesses and support safer application design.

**7. What might you show future employers from this assignment?**

I would show employers my completed Artemis Financial Practices for Secure Software Report because it demonstrates my ability to work with an existing Java application, implement security improvements, troubleshoot build errors, and document testing results. The report also shows my experience with vulnerability assessment and my understanding of the importance of protecting sensitive information. This project represents both the technical skills and problem-solving abilities I developed during CS 305.
