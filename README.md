# CS-305
*CS-305-10471-M01 Software Security 2026 C-1 (Jan - Mar)*

## Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
The organization is called Artemis Financial. They are a company that offers financial services to their customer base worldwide. As such, they required a database capable of hosting all the confidential information of their clientele. Their focus was on strengthening security, so the assignments relating to this were focused on adding security measures to an existing codebase.

## What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
I think I did well by adhering to specific industry standards for secure coding. One thing I did was run OWASP dependency checks, then I also made sure it was all up to date and no errors were found. Furthermore I also generated a certificate for the localhost application used in Project Two, to ensure the connection was secure via a https url. I also created a SHA-256 hash checksum to use with it. Secure coding is essential because when confidential information is involved, it is imperative to make sure it cannot be accessed by attackers due to weak security measures.

## Which part of the vulnerability assessment was challenging or helpful to you?
The most challenging part in my opinion was figuring out how to successfully launch the app in localhost. I encountered multiple errors trying to configure the key and certificate in application.properties, but I was eventually able to launch it. I noticed that even though the localhost url (https://localhost:8443/hash) was https, it had a strikethrough in the https part that I could not figure out how to remove, but I was still able to meet other project two requirements.

## How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
Several things I did were 1) create a checksum with a 256-bit algorithm hash, 2) run an OWASP dependency check, 3) update all dependencies, and 4) generate a certificate and keystore file. I would always make sure dependencies are up to date in the future because it is the quickest and easiest way to improve an application's security.

## How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
I made certain the application was functional by going down the rubric and confirming if the requested elements were present and functioning as intended. I also checked the console for any errors and submitted by assignment once I confirmed there were no critical errors. I ran an OWASP dependency check as well to assess vulnerabilities and see if I missed anything.

## What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
I did a lot of researching on my own by looking at YouTube videos for Eclipse, and then I also joined a discord server for SNHU to see how other students were able to resolve errors with the same assignments I did. That was how I was able to figure out how to deal with critical errors and making sure the Java version was the correct one to use (I previously struggled because it was stuck on version 1.8 no matter what I did in my pom file in a module 2 assignment, but then I figured out it was as simple to fix as right clicking the project folder to auto switch to a different version of Java). I would definitely refer to feedback from peers for future assignments and YouTube guides again because it makes it easier to follow along with instructions, since the original resources involved older versions of Java and such.

## Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
In the future, I would simply show more in depth screenshots upon request, and I would provide more files of previous work. For the assignment I only submitted one artifact, but I could also add work from Project One and before to show progress as I learn.
