# CS-305

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
**Artemis Financial is a financial consulting company.  They develop individualized financial plans for savings, retirement, investments, and insurance.  They have employed us to implement and apply the most current and effective software security.  More specifically Artemis Financial wants to add a file verification step to their web application to ensure secure communication.  It is my job to create this verification step in the form of a checksum.**

What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
**I performed many actions in identifying their software security vulnerabilities. What I did particularly well in was performing a dependency check and reviewing my vulnerabilities.  After reviewing them I suppressed the false positives and update what dependencies I could. Coding securely is one of the most important practices.  When a company such as Artemis Financial is working with customers financial information or personal information you must protect it from potential hackers. The wellbeing of the company relies on this security.  Customers are trusting that the company is protecting their personal information.  If this information is taken due to malicious activity, that trust is broken. Without trust customers take their business somewhere else.  It can take a long time for a company to earn their client’s trust back.**

What about the process of working through the vulnerability assessment did you find challenging or helpful?
**The most challenging part with the vulnerabilities was understanding false positives.  I had to do some extra research to find what dependencies had updates to fix the issues.  I then updated all my dependencies that I could.  I then suppressed those that had no fixes or that did not affect my program.**

How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
**I increased the layers of security in my program by creating a SHA256 algorithm to run my data through.  I also generated a certificate using the keytool. Finally, I ran the dependency check and updated the known vulnerabilities.  In the future I would run the dependency check.  I would also check for dependency update and update them to mitigate many vulnerabilities.**

How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
**I ensured that the code was functional and secure by performing a checksum validation.  I then ensured my browser was detecting my certificate that I made using my keytool.  After refactoring I ran a vulnerability check to ensure I did not introduce new vulnerabilities.**

What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
**When developing my program, I was struggling on generating my certificate with the keytool and having my program recognize it.  I went through many online sources to find what I was doing incorrectly.  Eventually I solved the issue. As for tools, the dependency check helped tremendously.  I will ensure I use this in future assignments to look for vulnerabilities.  The coding practice I used most often was compiling my code whenever I changed it.  This ensures that I can find errors as soon as they happen.**

Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
**There were many parts of this assignment I did well and a few I struggled with. I would show a future employer that I successfully generated a self-signed certificate. This shows that I created one and that my browser has accepted it under my name.**
