# The Gaming Room – Software Design Portfolio

## Brief Summary of the Client and Software Requirements
The Gaming Room is a company that created 'Draw It or Lose It', a multiplayer guessing game originally built for Android. They wanted to expand it into a web-based system that would work on Windows, macOS, Linux, and mobile devices. They needed a solution that could handle many users at once, protect user data, enforce unique naming for games and teams, and maintain high performance across platforms. The software design needed to apply patterns like Singleton and Iterator, and follow good security and scalability practices.

## What I Did Particularly Well
I broke down the client’s needs into a working design and focused on making the system easy to scale, secure, and run across different platforms. I also made sure to explain how object-oriented programming principles and design patterns would be used to meet their requirements. I believe I explained the real-world tradeoffs between different operating platforms well, which made the design decisions easier to follow.

## What I Found Helpful About Working Through the Design Document
Building the full design document before starting code helped keep everything organized. It made it easier to think ahead about system problems, like how to avoid duplicate names or how to manage memory when lots of images load at once. Laying out the system early also made it clear what tradeoffs and constraints would have to be managed when the software was built.

## What I Would Revise If I Could
If I could improve something, it would be planning for server memory use earlier. I originally underestimated how big the impact of high-definition images would be on system performance. In the future, I would plan from the start to include caching, compression, and smarter preloading techniques to keep things running smoothly.

## How I Interpreted and Implemented the User’s Needs
I broke down the client’s core needs into technical goals and matched them to practical design choices. For example, they needed stability and broad access, so I recommended a Linux-based server environment with REST APIs for flexibility. Making sure the design fits the user’s real needs matters because if the system doesn’t match how they work or grow, it fails, no matter how good the code is.

## How I Approached Software Design and Future Strategies
I started by focusing on the system as a whole, what users and devices needed to connect, how data needed to move, and where performance would matter most. After that, I mapped the main classes, patterns, and user interactions. In the future, I would continue starting with diagrams and real-world examples early, so problems get caught before building starts. I would also bring in newer tools like Docker for easier deployment and scaling.

## Notes on Project Environment
I researched Dropwizard and Maven for the backend build, but wasn't able to complete a full working Maven server due to environment limitations. Even without full deployment, I worked through how REST APIs, security layers, and client-server communication should be handled. The next steps would be completing the full server build and testing live connections.

## Future Learning Goals
- Complete a full Maven and Dropwizard server deployment.
- Implement OAuth2 authentication for RESTful APIs.
- Use Docker for scalable Java microservice hosting.