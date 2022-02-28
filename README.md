# Software-Design-Document
Submitted for a project in CS230-Operating Platforms

**Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?**
Our client, The Gaming Room, wanted to develop a game that is a rendition of the 1980’s television game Win, Lose, or Draw. The game consists of four rounds of play lasting one minute each. Drawings are rendered at a steady rate and are fully complete at the 30-second mark. If the team does not guess the puzzle before time expires, the remaining teams have an opportunity to offer one guess each to solve the puzzle with a 15-second time limit.

Our client was interested in expanding their gaming app to multiple platforms using various software patterns in a distributed environment. Specifically, before making a decision, The Gaming Room had asked for us to evaluate the three traditional operating platforms (Linux, Mac, and Windows), as well as mobile platforms, for how the game application software could be deployed and run and what would be required to do so.

**What did you do particularly well in developing this documentation?**
Some of the things we implemented well in this project was consistency in delivering the required milestones effectively and efficienctly. This came in the form of three deliverable versions of the Software document, beginning with an executive summary, design constraint, and domain model in the first version; followed by an updated evaluation of the development requirements, such as the server, client, and tools in the second version; and finally a complete and thorough recommendation section in the final version.

**What about the process of working through a design document did you find helpful when developing the code?**
We found that designing the domain model was partucularly helpful in navigating some of the critical requirements of the software, such as having only one instance of the game exist in memory at any given time and ensuring that the game and team names were unique. Designing the domain model helped us resolve this by configuring a singleton pattern for the game instance and an iteration pattern to make ensure the game and team names were unique.

**If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?**
Although this document was revised three times in its current delivery, if we were to implement one more revision it would be for the system architecture since view we didn't spend much time in that section. Describing the system and subsystem architecture present in the application, including physical components or tiers, is an important factor to consider, and with some much needed research, we would revisit this section in a fourth revision.

**How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?**
The user needs were interpreted by means of requirements and implementation strategy options to fulfill those requirements. Design conbstraints were also taken into consideration, as well as particular user preferences. 

**How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?**
Researching various system architecture patterns will be helpful to analyze and design similar software applications in the future
