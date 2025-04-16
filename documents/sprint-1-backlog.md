# Sprint 1 backlog

Team members & representives:

  * FiSMA ry: Heikki Naski.
  * Haaga-Helia University of Applied Sciences: Elias Helin, Erkki Tiili, Janne Puukko, Johannes Haapanen, Kaj Jansson, Kirstin Luik, Oskar and Petteri Pinkkilä.
  * Sprint's scrum master: Erkki Tiili.

Duration: 22.1.2025 - 5.2.2025.

---

## 1. Main goal of sprint

FiSMA ry required for the first sprint to creating MVP of the benefit application. In order to creation be successful, the algorithmic solution and structure of the benefit app had to be developed first. 


Additionally a preminilary (visual) wireframe of UI for benefit app and functional backend code was considered beneficial for MVP.    

---

## 2. User stories and tasks

Overall number of tasks for sprint 1 was 35.


**1. Small demo to test calculations.**

Description: Product owner wishes mathematical algorithm solutions for the calculations.

Priority: High.

Status: Done.


**2. Figma UI draft.**

Description: Draw preliminary wireframe of UI for Benefit application in Figma.

Priority: High.

Status: Done.


**3. Prepare README.md(s).**

Description: Create and write necessary README.mds and other documents about Benefit application.

Priority: High.

Status: Done.


**4. Create all-in-one-repository in English.**

Description: Create one repo for everything in Benefit app, such ass frontend, backend, documents, etc. The repo name should be "benefit-app".

Priority: High.

Status: Done.



**5. Configure Github-settings**

Description: Configure Github-settings so that Main-branch is protected and validation is on.

Priority: High.

Status: Done.


**6. React-vite: Add tailwind.**

Description: Add tailwind into react-vite.

Priority: High.

Status: Done.


**7. Typescript.**

Description: Install and configure Typescript for the project.

Priority: High.

Status: Done.


**8. React-router**

Description: Add a router to react.

Priority: Mid.

Status: Done.


**9. Add a CI/CD pipeline for dev-branch.**

Description: Add a preliminiary test for dev-branch as part of CI/CD pipeline. We used for example "Java With Gradle"-workflow from Github Actions.

Priority: Mid.

Status: Done.


**10. Slack PRO-license.**

Description: Check if student discount version of Slack PRO-license is worth and inexpensive enough for our team. If not, other platforms for weekly meetings should be considered, such as Discord or Teams.

Priority: Low.

Status: Done.


**11. Create PostgreSQL.**

Description: Create a PostgreSQL database for application.

Priority: Mid.

Status: Done.


**12. PostgreSQL integration.**

Description: Integrate postgreSQL to the application.

Priority: Mid.

Status: Done.


**13. Calculator's feature insertion: navigation / query screen [1.a].**

Description: Add a browsing function for action points.

Priority: High.

Status: Done.


**14. Calculator's feature insertion: input screen [1.b].**

Description: Add an input function for action points.

Priority: High.

Status: Done.


**15. Calculator's feature insertion: output [1.c].**

Description: Add an output function for action points. 

Priority: High.

Status: Done.


**16. Calculator's feature insertion: interface outwards [1.d].**

Description: Add an outbound integration function for action points.

Priority: High.

Status: Done.


**17. Calculator's feature insertion: interface inwards [1.e].**

Description: Add an inboud integration function for action points.

Priority: Mid.

Status: Done.


**18. Calculator's feature insertion: data storage function [1.f].**

Description: Add a data storage function for action points.

Priority: High.

Status: Done.


**19. Calculator's feature insertion: algorithmic / handling function [1.f].**

Description: Add an algorithmic or handling function for action points.

Priority: High.

Status: Done.


**20. Calculator's feature Navigation/question screen [2.a].**

Description: UI and save option for task number 13.

Priority: High.

Status: Todo.


**21. Calculator's feature UI: Input screen [2.b].**

Description: UI and save option for task number 14.

Priority: High.

Status: Todo.


**22.Calculator's feature UI: Output [2.c].**

Description: UI and save option for task number 15.

Priority: High.

Status: Todo.


**23. Calculator's feature UI: Interface outwards [2.d].**

Description: UI and save option for task number 16.

Priority: High.

Status: Todo.


**24. Calculator's feature UI: Interface inwards [2.e].**

Description: UI and save option for task number 17.

Priority: High.

Status: Todo.


**25.Calculator's feature UI: Data storage function [2.f].**

Description: UI and save option for task number 18.

Priority: High.

Status: Todo.


**26. Calculator's feature UI: Algorithm function or handling function [2.g].**

Description: UI and save option for task number 19.

Priority: High.

Status: Todo.


**27. CSV output 3.**

Description: Action points' calculator needs to print out all inputed values and data to CSV -file.

Priority: High.

Status: Todo.


**28. Data class design.**

Description: Design a first draft of the tables, which are needed in the database.

Priority: High.

Status: Done.


**28. Data class coding.**

Description: Code the draft of the tables, which are needed in the database.

Priority: Mid.

Status: In progress.


**30. Conditional render.**

Description: Add a conditional render for application.

Priority: Mid.

Status: In progress.


**31. Operational postgreSQL in every developer's workstations.**

Description: Verify that postgreSQL is operational in every developer's workstations.

Priority: High.

Status: In progress.


**32. Clean backlog**

Description: Clean and update backlog in more state-of-art and readable state.

Priority: Mid.

Status: Todo.



**33. Refactor calculation's function.**

Description: Refractor calculation's function in the application. Check https://github.com/fisma-benefit-app/benefit-app/tree/refactor-demo.

Priority: Mid.

Status: Done.


**34. Refactor input's render.**

Description: Refactor input's function in the application. Check https://github.com/fisma-benefit-app/benefit-app/tree/refactor-demo.

Priority: Mid.

Status: Done.


**35. CI/CD Docker compose testing in dev-branch.**

Description: Add a docker compose worklow for CI/CD testings in dev-bracnh.

Priority: Mid.

Status: Todo.



---

## 3. Sprint review

### 3.1 Completed tasks in overall

We have managed to get a functional algorithm to work for benefit application. Also preliminary draft of UI is done. Backend has been coded. 

### 3.2 Incompleted tasks in overall (and reasons why)

There are known issues to get backend and PostgreSQL database to work in every workstation, despite them being dockerized. Known issues have been some docker's configuration in individual workstations and Java with Gradle version [PLEASE DOUBLE CHECK IF THIS STATEMENT IS CORRECT].

### 3.3 Review notes

Notes from the Wednesday's sprint review meeting (5.2.2025), icluding feedback from product owner, representives and stakeholders:
* Simple codes, which everyone understands, **is better than** new technologies and / or libraries, that are decomissioned after a year. Also, the choice of what technology to choose and integrate must be carefully consider and discussed. It is imperative to think, what technologies and tools are still trending and available in next ten years (not to mention, how familiar and easy they are for next developers).
So far, react-tailwind & postgreSQL & spring-framework is ok.

* transferability of the application and system for future groups and situations was discussed.

* The drafted framework of calculator's UI got very positive feedback. The right column "summary" is a good feature, but requires more details of what is calculated. 

* The drafted framework of calculator's UI seems have a lot of scrolling when having many calculations. Add a feature, that packs many calculations to smaller rows, so that user does not need to scroll a lot.

* The class diagram of the benefit's database is valid. Though, it requires a description about n-to-n users/project relation (i.e. relation diagram).

* A live version of fisma benefit demo, that is integrated to project management (especially most imported tasks / highest priority), would be very useful.

* We clarified for representitives that sprints are _two weeks' intervall_ between each sprint reviews. Each sprints has then _one week iterations_, where minimum one weekly scrum meeting is held on wednesday between each iterations.


[_An example_]

Sprint 2, begins on Wednesday 5.2.2025.

Sprint 2 : Iteration 1, held on 5.2.2025 - 11.2.2025.

Weekly scrum meeting, held on Wednesday 12.2.2025. Mostly team members on the scene.

Sprint 2 : Iteration 2, held on 12.2.2025 - 18.2.2025.

Sprint 2 review, held on Wednesday 19.2.2025. Team members, product owner, representetives and stakeholders on the scene.

Sprint 2, ends on Wednesday 19.2.2025, after Sprint 2 review.

Sprint 3, begins... etc.


[_End of example_]

* The high level of the benefit's code was considered great quality.

* Naming convention in the project got high praises. They followed exactly according to business standard. Keep up with good work quality!.

![image](https://github.com/user-attachments/assets/59a4e49f-1901-4716-8db0-7d2ddb68d151)

Picture 01: First example of naming convention in the benefit application.

![image](https://github.com/user-attachments/assets/ddad7590-da7b-498c-aa57-c6b140151e35)

Picture 02: Second example of naming convention in the benefit application.

Notice how each name describes very clearly its main function and purpose.

* Overall, the application is in excellent condition. Stakeholders praised for great work. One stakeholder was positively suprised.


---

## 4. Sprint retrospective


### 4.1 What went well?

Communication and scheduling has worked well. Tasks have been distributed quite evenly.


### 4.2 What could be improved?

* Some scrum meeting were overextended from decided time schedule, due some tasks were discussed for long time, almost an hour. Scrum meetings need to stick to the planned time.

* Last friday's lunch break was skipped, thus made some team members hungry and exhausted. We need to have regural timing for lunch breaks.


### 4.3 Actions to address improvements?

* Jukka Juslin recommends so called **timed daily blocks** during scrum meetings. This means that each topic/problem/idea etc. will take max. and **only max.** 2 minutes for small coffee meeting, and 5-7 minutes for long sprint review, no matter how complex the discussion. 

Each prepare **before scrum meeting** a small brief of what has been done and what is gonna do forward, written e.g. in notepad or piece of paper. Then in scrum meeting just repeat vocally all writings.

Scrum master will take responsible of ending discussion, if it overextends maximum time limit. If topic needs to be discussed more, then it can be continued _after_ scrum meeting (so that other team members can go and do other things, while volunteers can further discuss the topic in the meeting place).

* We will keep a half hour lunch break _regularly_ at 12:45 p.m. in each work day and meeting.   


---

## 5. Metrics and reports


### 5.1 Burndown chart

![image](https://github.com/user-attachments/assets/76eaa8f7-6ecd-4a38-9447-8552492428f0)

Picture 1: Semi-burndown chart from sprint 1. Made in Github Projects. 


### 5.2 Team's velocity



