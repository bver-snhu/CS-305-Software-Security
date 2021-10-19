# Ben Verrill
# CS-305-Software-Security

  The Artemis Financial Practices for Secure Software Report was a security project we completed for our client, Artemis Financial. Artemis Financial is a small consulting firm that provides custom financial programs for their customers. They acheive this through a web application that allows their clients to view, upload, and download data. As this information is sensitive in nature, Artemis Financial hired us to help them implement the most up to date security practices to ensure the safety and integrity of their clients' data.
  For this report, I needed to first refactor given code to allow for ssl connections to a browser which would then display both given data and a checksum of that data within the browser. This involved creating self-signed certificates and importing them to a keystore. I think one thing I did especially well was work through the many problems that arouse during development. I had challenges getting the browser to accept the certificate. I had issues with Spring Boot that wouldn't allow me to start up a Tomcat server. I had issues with the implementation of MessageDigest. I was able to efficiently work through all of these by utilizing targeted web searches for my challenges as well as reading through technical documents.
  Once the code was refactored and working, I ran the dependency check to look for vulnerabilities. I think the biggest challenge I had here was identifying false positives. This was because I didn't think they were well explained as to how to determine if a vulnerability was real or not. After a lot of internet searching I was able to become more comfortable with what I was seeing. After I ran the check on the refactored code, I compared it against a check I ran before refactoring to ensure I didn't introduce any new vulnerabilities. 
  Working through this project, I relied on a Vulnerability Assessment Process Flow Diagram that allowed me to identify key areas of security that would be applicable. This included areas like secure APIs and cyptography. This allowed me to create a layered approach to securing the application. I think this, along with a prebuilt security checklist, would be useful for future projects to ensure I'm doing my best to reduce as much risk as possible.
  I think using internet search skills was by far the most useful tool utilized during this project. Being able to run targeted searches even for unique challenges is a must for completing any project. I also think that my use of comments was well used and would be good for future project, as it allows others to understand why I chose to code in the specific ways that I did. I think if there was one thing that I'd want future employers to to take away from what they've seen here, it's that not only am I able to implement secure coding practices but I'm also able to do so in an organized fashion that's easy to follow.
