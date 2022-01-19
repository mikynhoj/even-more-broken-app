### Conceptual Exercise

Answer the following questions below:

- What is a JWT?
JSON Web Token - an open standard used to share security information between two parties, specifically with a client and a server.

- What is the signature portion of the JWT?  What does it do?
It is used to verify that the sender of the JWT is who it says it is and to ensure the message sent was not change along the way. 

- If a JWT is intercepted, can the attacker see what's inside the payload?
Yes, the attacker can see what is inside the payload since the JWT is essentially the token based authentication.

- How can you implement authentication with a JWT?  Describe how it works at a high level.
The server generates a token that certifies the user identify and sends it to the client. The client will send the token back to the server for every subsequent request, so the server knows the request comes from a particular identity.

- Compare and contrast unit, integration and end-to-end tests.
Integration testing aims to test how external systems work with internal modules, one by one. End-to-end testing aims to test the user experience from start to finish.

- What is a mock? What are some things you would mock?
Mock creating a fake version of an external or internal service that can stand in for the real one,

- What is continuous integration?

- What is an environment variable and what are they used for?

- What is TDD? What are some benefits and drawbacks?

- What is the value of using JSONSchema for validation?

- What are some ways to decide which code to test?

- What does `RETURNING` do in SQL? When would you use it?

- What are some differences between Web Sockets and HTTP?

- Did you prefer using Flask over Express? Why or why not (there is no right
  answer here --- we want to see how you think about technology)?
