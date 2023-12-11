 > As you complete each section you **must** remove the prompt text. Every *turnin* of this project includes points for formatting of this README so keep it clean and keep it up to date. 
 > Prompt text is any lines beginning with "\>"
 > Replace anything between \<...\> with your project specifics and remove angle brackets. For example, you need to name your project and replace the header right below this line with that title (no angle brackets). 
# \<Dog DataBase\>
 > Your author list below should include links to all members GitHub (remove existing author).
 
 > Authors: \<[Howie Nguyen, Alvin Hoang, Justin Delcid, and Adam Chamas] https://github.com/Howie315 (https://github.com/Synerge360) (https://github.com/jjdelcid) (https://github.com/adamc0120)\>
 
 > You will be forming a group of **FOUR** students and working on an interesting project. The project has 4 phases, each one with specific requirements. A list of proposed project ideas that have been successful in previous quarters is listed in the project specifications document on Canvas. You can select an idea from the list, start thinking about the  you will implement, what design patterns can help you implement them, and why. If you want to propose your own original idea, you will have to contact an instructor to discuss the project and obtain written permission before you submit your project proposal (Phase 1). Your project needs to implement at least one design pattern iteratively, which you will have to justify in later phases.The project work should be divided almost equally among team members. You can of course help each other, but it needs to be clear who will be responsible for which features. Additionally, you are expected to follow Scrum patterns, specifically the use of a Scrum (Project) board, Sprints, and Scrum meetings. While Daily Scrums are not required we highly encourage you to practice them.

 
 > ## Expectations
 > * Incorporate **at least one** design pattern
 >   * It is recommended that you include a design pattern that we will teach this session (Composite, Strategy, or Visitor)
 > * Your project should be implemented in C++. If you wish to choose anoher programming language (e.g. Java, Python), please discuss with your lab TA to obtain permission.
 > * You can incorporate additional technologies/tools but they must be approved (in writing) by the instructor or the TA.
 > * Each member of the group **must** be committing code regularly and make sure their code is correctly attributed to them. We will be checking attributions to determine if there was equal contribution to the project.
 > * Each member of the group must actively participate in the Github Project board and reviewing commited code.
> * All project phases are to be submitted to this GitHub repository. You should modify this README file to reflect the different phases of the project. In addition, you should regularly hold sprint meetings with your group. You will need to hold two scrum/check-in meetings with your lab TA/reader in two different weeks in addition to the final demo.


## Project Description
 > Your project description should summarize the project you are proposing. Be sure to include:
 > * Why is it important or interesting to you?
 > * It is important us because we want to be able to store Dogs information and description so that the consumer could adopt/buy a dog. All of us are dog lovers so we're really into it.
 > * What languages/tools/technologies do you plan to use? (This list may change over the course of the project)
 >   * [toolname](link) - Short description
 >  * **Visual Studios Code - We will use this IDE to code and create test cases for our program.**
 >  * **Node.js - This is the Javascript to run the native website.**
 > * What will be the input/output of your project? What are the features that the project provides?
 > * **We will allow the user to input a new dog object and remove existing dogs as they are being adopted/bought. We plan on making a GUI in Visual Studios so the user could easily access methods.**
 > * This description should be in enough detail that the TA/instructor can determine the complexity of the project and if it is sufficient for the team members to complete in the time allotted. 
 > 
 > You also need to set up an empty project board by choosing the  “Automated kanban with review” option on Github. You should also have a Backlog and In testing columns added.
 > ## Phase II
 > In addition to completing the "Class Diagram" section below, you will need to:
 > * Create an "Epic" (note) for each feature and each design pattern and assign them to the appropriate team member. Place these in the `Backlog` column
 > * Complete your first *sprint planning* meeting to plan out the next 7 days of work.
 >   * Create smaller actionable development tasks as issues and assign them to team members. Place these in the `TODO` column.
 >   * These cards should represent roughly 7 days worth of development time for your team, taking you until your first meeting with the TA
 > * Schedule two check-ins using Calendly. You need to pick both time slots during your lab on week 8. Your entire team must be present for both check-ins.
 >   * The first check-in needs to be scheduled with your lab TA. During that meeting, you will discuss your project design/class diagram from phase II.
 >   * The second check-in should be scheduled with a reader. During that meeting you will discuss:
 >     * The tasks you are planning for the first sprint
 >     * How work will be divided between the team members

## Class Diagram
 > Include a **class diagram(s)** for your project and a **description** of the diagram(s). Your class diagram(s) should include all the main classes you plan for the project. This should be in sufficient detail that another group could pick up the project this point and successfully complete it. Use proper UML notation (as discussed in the course slides).
 > * https://lucid.app/publicSegments/view/8d61ee63-dc74-4de9-9850-db7bf4388a9b/image.png
 > * In our diagram, we have the UI class which is the main class where the user will interact with the program. Below the UI class would be the Dog class, where Dog objects will be made for each dog and be stored into a list. Below that we have the leaves such as addDog, removeDog, and showDog which are part of the Dog class. 
 
 > ## Phase III
 > You will need to schedule a check-in for the second scrum meeting with a reader (using Calendly). Your entire team must be present. This meeting will occur on week 8 but NOT during lab time.
 > * Before the meeting you should perform a sprint plan like you did in Phase II.
 > * You should also update this README file by adding the following:
 >   * What design pattern(s) did you use? For each pattern you must explain in 4-5 sentences:
 >     * We chose composite pattern
 >     * It was was necessary because the navigation bar has all the links leading to those pages and inherits the navigation bar in each page.
 >     * In addtion, it was easier to implement our UI like this because the design was easy to navigate through.
 >     * Why did you pick this pattern? And what feature did you implement with it?
 >     * We chose composite pattern because we have navigation that leads to About, Home, Dog listings and Dog add. 
 >     * How did the design pattern help you write better code?
 >     * It was easier to write code with because all we had to do was make pages for each link and inherit it from navigation bar. 
 >   * An updated class diagram that reflects the design pattern(s) you used. You may combine multiple design patterns into one diagram if you'd like, but it needs to be clear which portion of the diagram represents which design pattern (either in the diagram or in the description).
 >   * https://lucid.app/publicSegments/view/8d61ee63-dc74-4de9-9850-db7bf4388a9b/image.png
 >   * https://lucid.app/lucidchart/0933c191-85aa-4413-bd59-5dcdee72e922/edit?invitationId=inv_7088c6c1-5dc8-4ed8-8441-332b787605e5
 >   * Make sure your README file (and Project board) are up-to-date reflecting the current status of your project. Previous versions of the README file should still be visible through your commit history.
> 
> During the meeting with your reader you will discuss: 
 > * How effective your last sprint was (each member should talk about what they did)
 > * Any tasks that did not get completed last sprint, and how you took them into consideration for this sprint
 > * Any bugs you've identified and created issues for during the sprint. Do you plan on fixing them in the next sprint or are they lower priority?
 > * What tasks you are planning for this next sprint.

 
 > ## Final deliverable
 > All group members will give a demo to the TA/reader during lab time. The TA/reader will check the demo and the project GitHub repository and ask a few questions to all the team members. 
 > Before the demo, you should do the following:
 > * Complete the sections below (i.e. Screenshots, Installation/Usage, Testing)
 > * Plan one more sprint (that you will not necessarily complete before the end of the quarter). Your In-progress and In-testing columns should be empty (you are not doing more work currently) but your TODO column should have a full sprint plan in it as you have done before. This should include any known bugs (there should be some) or new features you would like to add. These should appear as issues/cards on your Project board.
 > * Make sure your README file and Project board are up-to-date reflecting the current status of your project (e.g. any changes that you have made during the project such as changes to your class diagram). Previous versions should still be visible through your commit history. 
 
 ## Screenshots
 > Screenshots of the input/output after running your application
 > * ![image](https://user-images.githubusercontent.com/73147167/157732562-e1bfc989-b829-4c36-95ec-5b1e00bc851f.png)
 > * ![image](https://user-images.githubusercontent.com/73147167/157732588-123d2640-221d-407f-a249-5e6719fb751e.png)
 > * ![image](https://user-images.githubusercontent.com/73147167/157732661-fdd972c8-6570-4653-9642-9660f4247c91.png)
 > * ![image](https://user-images.githubusercontent.com/73147167/157732715-cbbc3bea-3114-48f8-8170-70009827779e.png)

 ## Installation/Usage
 > * First install Node.js here: https://nodejs.org/en/
 > * Then git pull the files from the master branch.
 > * In terminal, enter the dog database folder with cd ./dog-database/.
 > * Also in terminal, type the following: 
 > * npm install
 > * npm install react-router-dom
 > * npm install bootstrap
 > * npm install react-fade-in
 > * npm install react-loading
 > * npm install firebase
 > * npm install react-toastify
 > * npm install react-promise-tracker
 > * npm install expo-image-picker
 > * npm install react-test-renderer
 > * Type "npm start" in terminal to run the program.
 ## Testing
 > How was your project tested/validated? If you used CI, you should have a "build passing" badge in this README.
 > * For our project, we tested it using inputs and checking if the outputs match with our inputs. In our case, we would check the inputs for Dog name, age, breed, and description. We would also check if the image matches the one we uploaded. To check our tests, we would look at the dog listings and see if our dog objects correspond to our tests correctly. 
 
