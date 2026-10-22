# CS230
CS230 materials
# CS 230 Portfolio Reflection

### Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?

The Gaming Room was a client that wanted to expand its existing Android game, *Draw It or Lose It*, into a web-based application that could run on multiple platforms. The game involves teams competing to guess images within a certain amount of time. The client needed a system that could support multiple games, teams, and players while making sure names and IDs remained unique. They also wanted the application to be secure, scalable, and accessible across different operating systems without having to develop a separate version for each one.

### What did you do particularly well in developing this documentation?

I think one of the things I did particularly well was comparing the different operating systems and explaining why Linux would be the best choice for hosting the application. Instead of just choosing an operating system, I looked at the advantages and disadvantages of Windows, macOS, Linux, and mobile platforms. I also think I did a good job connecting the technical recommendations back to what the client actually needed. For example, I explained how using Java, a centralized server, and a relational database could help keep the application organized and support future growth.

### What about the process of working through a design document did you find helpful when developing the code?

Working through the design document helped me understand how important it is to plan the structure of an application before getting too far into coding. The UML class diagram was especially useful because it showed how the Game, Team, Player, and GameService classes were connected. It also helped me understand why design patterns like Singleton and object-oriented concepts like inheritance and encapsulation are useful. Having that structure already planned makes it easier to write code because you have a clearer idea of what each class is responsible for and how everything should work together.

### If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

If I could revise one part of my work, I would probably expand the system architecture section to include a more detailed diagram showing how the different components communicate. My document explains the server, database, network connections, and security requirements, but I think a visual representation would make those relationships easier to understand. I would also include more detail about how the application would handle a large number of players connecting at the same time. That would make the design more useful if another developer needed to take the documentation and begin implementing the system.

### How did you interpret the user's needs and implement them into your software design? Why is it so important to consider the user's needs when designing?

I approached the client's requirements by focusing on what they wanted the application to accomplish rather than just the technology being used. Since The Gaming Room wanted the game to work across multiple platforms, I recommended a browser-based application instead of developing separate programs for each operating system. I also considered how the application would manage multiple games and players, protect information, and handle future growth. Understanding the user's needs is important because even a technically impressive application isn't very useful if it doesn't solve the problem it was designed for. Keeping those requirements in mind helps developers make better decisions and avoid unnecessary complexity.

### How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

My approach was to start by understanding the requirements and then work through the different technical decisions needed to support them. I looked at the application structure, operating systems, storage, memory management, networking, and security before making my final recommendations. I also considered factors like cost, maintainability, and scalability instead of focusing only on whether something would work. In future projects, I would continue using UML diagrams, comparing different technical solutions, and documenting the reasoning behind my decisions. I would also spend more time planning how the different parts of an application interact before starting development. This project helped me see that software design isn't just about writing code. It's also about making decisions early that will make the application easier to build, maintain, and improve later.
