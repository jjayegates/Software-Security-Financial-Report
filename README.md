# Software-Security-Financial-Report

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
  -  Artemis Financial is a financial consulting company that handles a lot of sensitive information for their clients.  Because of the nature of the information they handle, it is imperative that do so securely.  This is preceisly the issue that Artemis Financial wanted me to address.  They wanted me to imporove the security of their applications and prevent against a compromise of their system.  

What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
  -  In particular, I was very detailed and efficient at sanitizing the input strings.  Attacks such as SQL injection rely on the application accepting unsecure/compromised strings into the program and then getting manipulated by that very string. I was very careful to make sure that no string was too long as well as checking to make sure the string had no known dangerous commands in it.  It is important to code securely because if your system is not secure, your clients cannot trust you with their sensitive data.  If your clients can trust you, then not only will they be happy, but their happiness and your security will reflect well on you and this may lead to even more clients.  This is the main value that software security adds to a company's overall wellbeing.  

What about the process of working through the vulnerability assessment did you find challenging or helpful?
  -  Most certainly, the most challenging aspect of working through the vulnerability assessment was configuring, running, and interpreting the dependency check report.  It was a bit cumbersome at first, however, once I got used to it, all three of the aforementioned aspects ceased to be an issue.

How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
 -  I approached adding layers of security the same way I approach adding any kind of layers to a software system.  I first check to make sure that the foundation that I am building upon behaves as expected in all scenarios.  Then, I piece by piece start building up the new layer, testing it as each component is completed.  In the future, I will make furhter use of input validation as well as dependency checks to both make sure that my own code is secure as well as that of the 3rd-party packaghes I am utilizing in the program.  

How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
  -  Yes, this is a very important part of refactoring code.  No prgrammer is infallible, and even when attempting to fix a single error, one can inadvertently introduce several more.  For ths reason, checking over updated code is a necessary part of code refactoring.  This should be done both manually and with a dependency checker.  

What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
  -  One major rescource that was helpful was the Oracle's list and description of major encryption algorithms.  Encryption is a huge aspect of software security, so having a centralized source of information on so many different encryption methods will not only help me in the future but can be a huge help to anyone that does anything related to software security. 

Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
  -  I would be proud to showcase my skills in input validation/sanitization as well as my usage of the springboot technologies and abilites to make use of annotations to fascillitate the correct routing of webpage information.  
