Artemis Financial Vulnerability Assessment Report README File
----------------------------------------------------------------
Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
  -Artemis Financial is a financial company working to modernize its operations by securing its RESTful web API. They needed protection against external threats like unauthorized access, outdated dependencies, and insecure communications. The goal was to ensure secure handling of sensitive financial data, meet international regulations, and strengthen defenses against evolving web threats.

  
What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
  -I successfully identified vulnerabilities through manual code review and static testing.
This included outdated libraries, input validation issues, potential data leaks, missing exception handling, and insecure API design. Coding securely is critical because it protects sensitive data, maintains trust, ensures regulatory compliance, and prevents costly breaches that could damage Artemis Financial’s reputation.

  
Which part of the vulnerability assessment was challenging or helpful to you?
  -The most challenging thing for me was the manual code review which was detailed and required careful inspection to catch subtle issues like improper authorization. What was  most helpful was running the dependency check tool was efficient to identify vulnerabilities in third-party libraries quickly.

  
How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
  -I increased security layers by Encrypting data (AES-256), securing password storage with hashing, securing API endpoints and improving input validation. In the future, I would, use more advanced static and dynamic analysis tools and implement automated CI/CD pipeline security scans.

  
How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
  -After refactoring the code, I re-tested API endpoints for functionality and I re-ran static analysis and manually reviewed sensitive areas to make sure no new vulnerabilities were introduced.

  
What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
  -Using the OWASP Dependency-Check, manual code review and upgrading outdated libraries, using secure coding standards and exception handling for stability will be critical for future projects in maintaining secure, and reliable software. 

  
Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
  -From this assignment, I would show future employers my full security assessment and mitigation plan for Artemis Financial’s software application.
