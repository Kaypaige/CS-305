# CS-305
**1. Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?**
Artemis Financial is a consulting firm that creates personalized financial plans for clients, including savings, retirement, investments, and insurance. They wanted Global Rain to modernize their systems while improving security for their RESTful web application. The main issue was identifying and mitigating vulnerabilities to protect sensitive financial and personal data.

**2. What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?**
I did well at identifying key vulnerabilities through both manual review and dependency checks, such as missing encryption and outdated libraries. Secure coding is critical because it prevents data breaches, protects client trust, and ensures regulatory compliance. Strong security directly supports a company’s reputation and long-term stability.

**3. Which part of the vulnerability assessment was challenging or helpful to you?**
The static testing with the Maven dependency-check tool was helpful because it highlighted outdated or vulnerable libraries that might otherwise be overlooked. The manual review was more challenging, since it required carefully tracing through code to find issues like missing input validation and insecure data handling.

**4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?**
I increased security by recommending encryption for data at rest and in transit, adding server-side input validation, implementing secure APIs, and updating dependencies. In the future, I would use a combination of automated tools like dependency-check along with manual code reviews and security best practice frameworks (such as OWASP).

**5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?**
I ensured functionality and security by running dependency checks after refactoring, verifying encryption through checksum validation, and testing HTTPS communications. I confirmed that no new vulnerabilities were introduced by performing secondary static tests on the updated code.

**6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?**
Helpful tools included the Maven dependency-check plugin for static testing and Java Keytool for generating certificates. Secure coding practices such as input validation, error handling, and using updated libraries will also be valuable for future assignments.

**7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?**
I could show my vulnerability assessment report as an example of identifying and documenting risks, along with the refactored code demonstrating secure communication with HTTPS and encryption. This highlights my ability to follow industry best practices and strengthen the security of real-world applications.
