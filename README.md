# CS305
SoftwareSecurity SNHU


Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

The client Artemis Financial wanted their software to be encrypted by an encryption cipher of our choosing. They wanted the encryption to be symmetric
so that their clients could download the key and have access to their information. They wanted the most secure software we could make by following the 
Vulnerability Assessment Process flow. We are able to follow the path of the data, and make sure it is secure from the clien to the customer. 


What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

I was able to get the encryption to work very well. It produced the hashed value that it needed to. Also I was able to build the dependency check completely, and 
verify all the vulnerabilites that it found. This allows for us to fix all potential vulnerabilites that are widely known.

What part of the vulnerability assessment was challenging or helpful to you?

Everything from the APIs to the Client/server I am the least experienced in this field. There were parts of the last project I didn't fully understand how to complete
which ended up with me just guessing. Code error through encapsultion I have much experience in and it was easier for me to fix those issues. 

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

We inceased a layer of security by adding SHA encryption to the input that the user could have potentially given. In the project the string is just a static value.
But it gets encrypted never the less. We also added a certificate allowing the website to have HTPPS and be secure. 

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

Running the vulnerability check again would be the best way to see if you added any different vulnerabilites. Which was a problem I ran into. 


What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

There were many usefull resources I found during this class. I used oracle frequently for the vulnerabilites/ciphers. I used stack exchange at times to when I wasn't sure how to implement the encryption, or when I needed a better explanation of something. I would show how we were able to implement a client/server program using spring/tomcat, and also maven for dependency checks. 
