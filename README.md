# CS305-Portfolio
CS305-SecureSoftware

CS 305 Module 8 Journal: A Look Back

 About the Client
 Artemis Financial was my client. They make personalized financial plans that include insurance, investments, savings, and pensions.  The company hired me to make sure that its custom software was safe by, among other things, encrypting web interactions and fixing software bugs.  The main problem was showing that their web app met security standards and best practices in the business.

 What I did right
 By using the OWASP Dependency-Check tool and looking at third-party library risks, I was able to find and write down software security holes.  To protect contact between clients and servers, I also set up a self-signed certificate and turned on HTTPS.  I used best practices well when I wrote safe code and checked that encryption worked.  Software security is good for a business because it keeps private client data safe, keeps customers trusting the business, and makes sure that security rules are followed.

Problems
 The hardest part was turning the results of the risk assessment into suggestions that could be put into action.  It took a lot of work to figure out how to interpret multiple CVEs across dependencies and to know which problems were the most important.  This gave me the confidence to look for vulnerabilities myself instead of just counting on automated reports.

 Adding more layers of security
 I made it safer by using strong cipher suites, requiring TLS 1.2/1.3, and adding input validation and secret management.  I would keep using code reviews, dependency-check checks, and penetration testing to find security holes and add layers of protection in the future.

 Making sure functionality and safety
 Once I was done refactoring the code, I made sure it worked by running the app with Maven and checking the HTTPS address in a browser.  I also made sure that the cycle of encrypting and decrypting worked properly and that checksum verification kept the data safe.  This proved that adding more protection did not affect how an application worked.

 Tools That Can Help
 The most useful tools were the OWASP Top 10, the Spring Boot security setup guides, and the Maven dependency-check plugin.  These tools showed me how to use secure coding principles in real life and check the results.

 Value to Employers
 Employers can see from this task that I can follow best practices for security in my field, use automated tools to find holes in security, and write safe, useful code.  It shows that I can balance the needs for usefulness and security, which is very important in professional software development.
