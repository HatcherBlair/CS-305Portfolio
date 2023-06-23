# CS-305Portfolio

# Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artermis Financial is a financial institution that develops financial plans for their customers.  These plans include savings, retirement, investments, and insurance.  Their software requirements are very standard across the financial industry as it is government regulated and very closely examined and audited.  The primary issue that Artemis wanted addressed was their software security. They had an existing code base and needed it to be checked for vulnerabilities and to have any vulnerabilities addressed.

# What did you do very well when you found your client's software security vulnerabilities? Why is it important to code securely? What value does software security add to a company's overall wellbeing?
One thing that I did well was documenting vulnerabilities that were found and finding a proper path to address these vulnerabilities.  Coding securely is important because it makes it more difficult for security breaches to occur, which is becoming more and more common every day.  Software security helps a companies wellbeing by increasing their trust in the eye of the public.  If a company is found to not have proper security in place, the public loses trust and they stop growing or begin shrinking.

# What part of the vulnerability assesment was challenging or helpful to you?
One thing that was challenging was determining false positives in the dependency check report.

# How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I increased layers of security by adding multiple checks at different stages of communication, this means that a bad actor would have to bypass multiple security checks in order to cause harm to the company.  In the future, I would start with a dependency check and then determine which of the dependencies needed to be removed or addressed.  I will use multiple mitigation techniques in the future, primarily encryption and writing secure code to prevent injection attacks.

# How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
To make sure that the application was functional and secure I tested the features, and tried to access the software through insecure methods.  To check if I introduced new vulnerabilities I ran another dependency check and made sure to address any issues that came up in the new dependency check.

# What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Maven is one tool that I used that will be extremely helpful in the future.

# Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
One thing that I would show an employer is my mitigation techniques that were implemented.
