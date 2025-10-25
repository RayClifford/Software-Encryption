# Software-Encryption
A report for a financial group showcasing my encryption methods.

Summary of Client
Artemis Financial is a financial services company that develops and maintains web-based solutions to help clients manage investments, insurance policies, and financial portfolios securely. 
Because they handle sensitive client information, data protection and secure communication are critical to their business operations. Artemis Financial requested a review and enhancement of
their exisiting web application's security. Specifically they wanted to make sure that it met industry standards for secure coding and protected customer data during transmission. The company's
main concerns were, 
1. Identifying and mitigating potential vulnerabilties through static code analysis.
2. Implemting encryption algorithms for secure data handling.
3. Generating and managing digital certificates for secure HTTPS communication.
4. Ensuring Industry compliance with best practices.

 To address these needs, the project involved performing static testing with OWASP Dependency-Check implementing cryptographic hash algorithms (SHA-256), configuring SSL/TLS certificates,
 and verifying HTTPS communication through the application.
 
What I did Well and why Secure coding practices are important
 When reviewing Artemis Financial’s software for vulnerabilities, I successfully performed static testing using the OWASP Dependency-Check tool to identify insecure or outdated dependencies. I also analyzed the results to distinguish between real vulnerabilities and false positives, 
 then implemented suppression rules and updated dependencies to resolve legitimate issues. Additionally, I refactored the application to use secure HTTPS communication through a self-signed SSL certificate, ensuring that all data transmitted between the client and server was encrypted. 
 These actions helped strengthen the application’s overall security posture while maintaining functionality and performance.

 It is essential to code securely because security flaws in software can expose systems to attacks such as data breaches, malware injections, or unauthorized access. Writing secure code reduces these risks by ensuring that vulnerabilities are identified early in the development process 
 and addressed before deployment. Secure coding practices protect both the organization and its customers by safeguarding sensitive information.

 Strong software security adds significant value to a company’s overall well-being. It builds customer trust, protects financial assets, and ensures regulatory compliance with data protection laws. A secure application also helps maintain the company’s reputation and prevents costly 
 downtime or loss from cyber incidents. In the case of Artemis Financial, secure software reinforces their credibility as a trusted financial institution that prioritizes the confidentiality and integrity of client data.

Challenging Assessment
 The vulnerability assessment was challenging because it required careful analysis and problem-solving to interpret the results correctly. However, the prior work I completed throughout earlier modules taught me how to proceed with confidence. Understanding how to use the OWASP 
 Dependency-Check tool, identify false positives, and refactor code securely helped me approach the process more effectively, even when the findings were complex or technical.

 I increased layers of security in the Artemis Financial application by implementing multiple protective measures. First, I performed static testing with the OWASP Dependency-Check tool to detect and address vulnerable dependencies. Next, I refactored the code to use secure HTTPS 
 communication with a self-signed SSL certificate, ensuring data transmitted between the server and client was encrypted. I also incorporated cryptographic hashing (SHA-256) to verify data integrity and authenticity. Together, these layers helped strengthen the application’s defenses 
 against potential threats.

 Future
 In the future, I would continue using tools like OWASP Dependency-Check, SonarQube, and Burp Suite to assess vulnerabilities in both code and application behavior. I would also apply risk assessment frameworks such as OWASP Top Ten and NIST guidelines to prioritize vulnerabilities 
 based on severity and impact. By combining automated tools with manual code review and industry best practices, I could make more informed decisions about which mitigation techniques—such as patching, encryption, or access control—are most effective for maintaining secure software.

Functional and Secure
 To ensure the code and software application were both functional and secure, I thoroughly tested the program after each change. I verified that the application ran correctly by compiling and executing the refactored code without errors, confirming that the HTTPS connection and checksum 
 verification worked as intended. To confirm that no new vulnerabilities were introduced, I performed a secondary static test using the OWASP Dependency-Check tool. This follow-up scan allowed me to review and compare results with the initial report, ensuring that the refactoring enhanced 
 security without creating additional risks or dependency issues.

Tools and Practices
 Throughout this project, I used several valuable resources, tools, and coding practices that will be helpful in future assignments. The OWASP Dependency-Check tool was essential for identifying and managing software vulnerabilities, while the Java Keytool allowed me to generate and manage 
 SSL certificates for secure communication. I also applied secure coding practices such as using encryption and hashing algorithms (SHA-256), validating data, and refactoring code to support HTTPS. These tools and techniques not only strengthened the application’s security but also improved 
 my understanding of industry-standard security testing and best practices that I can apply to future development projects.

Examples of Skills
 From this assignment, I could show future employers several examples that demonstrate my technical skills and understanding of software security. Specifically, I can present my refactored Java code that implements cryptographic hashing (SHA-256) and secure HTTPS communication using a 
 self-signed SSL certificate. I can also share my OWASP Dependency-Check reports that document how I identified and mitigated vulnerabilities, along with my Practices for Secure Software Report, which explains the testing process, results, and applied best practices. Together, 
 these deliverables highlight my ability to develop secure applications, perform vulnerability assessments, and follow professional security standards—skills that are highly valuable in the software development and cybersecurity fields.
