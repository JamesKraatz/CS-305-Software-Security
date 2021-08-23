# CS-305-Software-Security
## •	Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
The client, Artemis Financial, is a financial consulting company that develops individualized financial plans for savings, retirement, investments, and insurance for their patrons. They want to implement and apply the most current and effective software security as an important step in modernizing their operations and as a crucial component of their custom software’s success. As a part of the team, I was asked to add secure communication mechanisms.
## •	What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I identified a minimum required level of protection needed for a financial application and a maximum allowed level of protection of international usage. Securing the software helps prevent both tangible and non-tangible losses due to data loss through identity, integrity, or secrecy deficiencies.
## •	What about the process of working through the vulnerability assessment did you find challenging or helpful?
Identifying and verifying false positives seem to be difficult. Fortunately, there are provisions to create a suppression xml file to mask the reporting of these issues. However, care should be taken before masking reported vulnerabilities to ensure that actual existing vulnerabilities are not masked during process. 
## •	How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
Attempt to identify the application and client’s needs. Limit focus to the identified need while trying to realize its full scope.
## •	How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
Spring-boot mapping in the web browser, Chrome, and confirming my connection was secure. I also used Chrome developer tools to get more confirmation that the communication channel was encrypted, and confirmed encryption cipher deployed.
## •	What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
I used OpenSSL to create a Certificate Authority to sign the  Certificate Sign Requests I generated using Keytool. My OpenSSL runs on Ubuntu which I have installed as a Microsoft WSL2 installation. Additionally, I made have use of the internet to find ways to address the incapability of self-signing a certificate and using it to open a secure web connection with Chrome.
## •	Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
Implementing the secure connection was a very strong achievement. I was able to serve and receive the secure web page and use the Certificate I generated by signing it from a Certificate Authority I also created. I think this is a very strong accomplishment and I am very proud of it. I have also learned more about keep software secure and the complexities in entails. This responsibility, in my perspective, has grown quite a bit along with my awareness.
