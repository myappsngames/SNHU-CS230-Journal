# SNHU CS230: Operating Platforms Journal
Showcases a software design document

## Reflection

#### Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?
* The Gaming Room wants a web-based multiplayer version of their mobile game "Draw It or Lose It".  This game involves teams guessing words based on images from a library. Draw It or Lose It is loosely similar to the 1980s television game Win, Lose or Draw, where teams compete to guess what is being drawn. Rather than a player drawing images on an easel to help team members guess the puzzle (a phrase, title, or thing), the application will render images from a large library of stock drawings as clues. A game consists of four rounds of play lasting one minute each. Drawings are rendered at a steady rate and are fully complete at the 30-second mark. If the team does not guess the puzzle before time expires, the remaining teams have an opportunity to offer one guess each to solve the puzzle with a 15-second time limit.

Draw It or Lose It Software Requirements:
* A game will have the ability to have one or more teams involved.
* Each team will have multiple players assigned to it.
* Game and team names must be unique to allow users to check whether a name is in use when choosing a team name.
* Only one instance of the game can exist in memory at any given time. This can be accomplished by creating unique identifiers for each instance of a game, team, or player.

#### What did you do particularly well in developing this documentation?
* Alignment with Requirements: The software design document clearly outlines the client's requirements and demonstrates how my design choices address each requirement.
* Consideration of Design Constraints: I have identified potential challenges like network latency, cross-platform compatibility, and security, and proposed solutions to mitigate them.

#### What about the process of working through a design document did you find helpful when developing the code?
* Clear understanding of requirements: A well-defined design document outlines the project's goals and functionalities. This helped me avoid misunderstandings and write code that meets the client's needs.
* Identification of potential challenges: By anticipating and addressing design constraints like network latency or security in the document, I could proactively implement solutions during development, avoiding problems later in the coding process.

#### If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
* One potential area for revision in the design document could be the Evaluation section. While it currently identifies development considerations for different platforms, it doesn't explicitly tie those considerations back to the client's requirements or the chosen technical approach (cloud-based platform, web application).

#### How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
* The document starts by outlining the client's requirements, which directly translate to user needs.
* Importance of user's needs when designing:

    * Increased User Satisfaction: By understanding what users want and expect from the software, you can design features and functionalities that meet their needs.
    * Improved Product Adoption: If the software doesn't address user needs, they are less likely to adopt it. Considering user needs from the beginning helps ensure the software is relevant and solves a problem for its target audience.
    * Reduced Development Costs: Focusing on user needs helps avoid creating features that nobody wants or uses. This reduces development time and costs associated with unnecessary functionalities.
    * Clearer Design Direction: Understanding user needs provides a guiding principle for design decisions. When faced with technical choices, considering user needs helps determine the best path forward.

#### How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
* I approached designing software with a user-centered design. A user-centered design places the user's needs at the center of the design process.
* Future techniques or strategies:
  * Design Patterns:  Utilizing established design patterns can promote code reuse, maintainability, and adherence to best practices.
  * Prototyping: Low-fidelity prototypes (e.g., wireframes, mockups) can be created quickly and iterated upon to validate assumptions and refine the design.
  * Agile Development: Short development sprints, daily stand-up meetings, and user story creation can help ensure the project stays on track and meets user requirements.
