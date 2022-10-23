# CS-305
Software Security

*##Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
###Artemis Financial is a financial services company that provides financial planning solutions and insurance solutions to their clients. As their hired programmer, I was to address any known issues within their code base and make sure secure storage of private data and secure communications to upload and download data was implemented.

What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
This class was probably the most challenging class for me thus far within the program. I had trouble with many of the weekly aspects moving forward. However, I was able to perservere through the class and end up making the grade. In terms of software vulnerabilities, I think the part I was able to understand/implement the most approproately has to do with understanding the history of ciphering. I could easily identify which cipher(s) would be useful in helping Artemis Financial with their algorithm based on the information we learned throughout the course. Then, diploying said cipher within the server class.

What about the process of working through the vulnerability assessment did you find challenging or helpful?
Along similar lines, I also found implementing the hash algorithm to be challenging, as well as getting my program to connect to localhost to verify security. Including the proper keystore element within the project wasn't necessarily difficult to understand, but involved in getting it to work properly (project two). I had the right hash function in the end, I was just unable to verify it through the browser!

How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
The first element of increasing the layers of security was to take the program and run dependency checks. Then, after analyzing the source code for no errors. I implemented the TLS/encryption.

How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
Unfortunetly, I had trouble with this step in verfying the localhost to confirm the correct output, plus secondary testing. I ensured that there was no error in Eclipse via the code, but running the program through Maven gave me issues. I was able to run a dependency check for vulnerabilities and make a self-signed certificate, but ultimately couldn't run another dependency check after refactoring.

What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
While I unsuccessfully double-checked my securities, creating SSL certificates, as well as utilizing dependency checks, is incredibly useful. Both processes I will work towards improving upon, and implement, in future projects.

Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
Even though I wasn't able to double-check my work, I am proud of the code I created, because I was able to properly develop a proper class for "ServerController" with a proper hash algortihm. That, and I learned a lot from the history of software security ciphering, and with study, can properly identify which cipher algorithms would be most appropriate for certain tasks.
