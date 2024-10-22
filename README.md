# CS305

Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
The client, Artemis Financial offers individual financial plans to its customers, serving as a financial consultant focusing on savings, retirement, investments and insurance.  They contracted with Global Rain to help modernize its operations in relation to its software security.  The company is looking for security expertise to protect the organization from external threats.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
When investigating the company's software, multiple vulnerabilities were identified through static testing.  However, through further investigation, there were multiple security concerns flagged that were false positives, that we ultimately supressed in the report to not flag future concerns. In general, it is important to code securely to protect the company against external threats; given the company's focus on financial information, there is incentive for the software to be hacked for either personal information or financial details.  The company must prioritize its software security to not only protect the details of their customers, but also protect the company's brand image and trust within its consumers.

Which part of the vulnerability assessment was challenging or helpful to you?
In the vulnerability assessment, the most challenging step for me was identifying which errors caught can be supressed as false positives.  Given the system caught the error, I am individually inclined to believe it was caught for a reason, and mis-attributing it to a false negative and suppressing it in the report could lead to significant ramifications if incorrect.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
The best way to increase layers of security it by making it a standard practice within your development.  Through added factors such as secure data connections, input validation, regular trainings of your team related to security, and standardized testing through both static and dynamic means, you can ensure your code remains as secure as possible.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
Testing the application runs appropriately after making edits is the best way to ensure the application remains functional.  Once the code is updated, it is important to re-run security scans to understand if new vulnerabilities were introduced in your updates.  This ensures that the security systems you are implementing are helping more than offering new vulnerabilities.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
The standard libraries of security testing are fantastic resources to keep on hand for future development.  I had no idea there were public, standard solutions to many of the errors that static testing can throw, which can be a great resource to improve security of the application.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
From this course, the work of which I am most proud is Project One, the vulnerability assessment report.  In this report, it demonstrates not only the technical skills needed to complete an assessment, but also displays the knowledge of the importance of software security through development, and my ability to comprehend the business need.
