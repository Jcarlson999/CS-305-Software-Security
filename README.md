# CS-305-Software-Security
Portfolio artifacts from CS 305 Software Security

# CS-305-Software-Security

## Artemis Financial – Practices for Secure Software

### Client and Software Requirements
Artemis Financial is a financial consulting company that wanted to improve the security of its web-based software application. The company needed its application updated to protect sensitive information during communication and verify that data had not been modified. My task was to identify security vulnerabilities and refactor the application using secure coding practices.

### Software Security Assessment
I successfully used dependency scanning and manual review to identify potential security vulnerabilities within the application. Secure coding is important because vulnerabilities can expose sensitive customer and company information. Improving software security helps protect data, maintain customer trust, and reduce the risk of security breaches.

### Challenges and Helpful Areas
One of the more challenging parts of the vulnerability assessment was working with the OWASP Dependency-Check tool and reviewing the vulnerabilities it identified. This was also helpful because it showed me how third-party dependencies can introduce security risks even when the application's own code works correctly.

### Increasing Layers of Security
I increased the application's security by implementing HTTPS, configuring an SSL certificate, using SHA-256 hashing to create a checksum, and performing dependency vulnerability scanning. In the future, I would continue using tools such as OWASP Dependency-Check along with vulnerability databases and secure coding standards to determine which vulnerabilities need to be addressed.

### Testing Functionality and Security
After refactoring the application, I tested it to make sure it still functioned correctly. I successfully ran the application using HTTPS on port 8443 and verified the checksum functionality in the browser. I also ran OWASP Dependency-Check after the changes to identify vulnerabilities in the project's dependencies and confirm that the security assessment could complete successfully.

### Resources, Tools, and Practices
Some of the resources and tools I used included Java, Spring Boot, Maven, Eclipse, OWASP Dependency-Check, SSL/TLS certificates, SHA-256 hashing, and the NIST National Vulnerability Database. These tools and secure coding practices will be useful when developing and testing secure applications in future projects.

### Portfolio Value
For future employers, this project demonstrates my ability to analyze an existing software application, identify security concerns, implement secure communication and hashing, perform dependency vulnerability scanning, and verify that an application remains functional after security improvements. The completed Artemis Financial secure software report included in this repository provides additional documentation of the work completed.
