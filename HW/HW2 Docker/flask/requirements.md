# Agile

### Theme:
**Get GiggleGit demo into a stable enough alpha to start onboarding some adventurous clients**

### Epic:
**Onboarding experience**

---

### User Stories

#### User Story 1:
**As a vanilla git power-user that has never seen GiggleGit before,**  
I want to minimize the amount of relearning I do of Git so that I’m comfortable with the commands and interface.

#### User Story 2:
**As a team lead onboarding an experienced GiggleGit user,**  
I want to show and demonstrate many new interesting features.

#### User Story 3:
**As a new user to Git in general,**  
I want to be able to use GiggleGit while minimizing the learning curve for both Git and GiggleGit.

---

### Task

**Create tutorials for new Git/GiggleGit users**

---

### Tickets

#### Ticket 1:
**Record walkthroughs on the basics of using Git**

#### Ticket 2:
**Record walkthroughs on using GiggleGit**

---

### Question: 
**This is not a user story. Why not? What is it?**  
**"As a user I want to be able to authenticate on a new machine."**

#### Answer:
It specifies a task instead. It isn’t a user story because user stories are more general in that they explain what a particular party wants to see accomplished, the motivation, or their goal. The statement given does not give any extra context as to why they want to be able to authenticate on a new machine.

---

# Project Requirements

### Goal:
**Create a new tool based on the vanilla interface that allows users to merge with humor.**  
The tools should sync with the base GiggleGit packages and will be used in user studies.

### Non-goal:
**We will not incorporate additional filtering capability on the types of jokes produced with each merge.**

---

### Non-functional Requirement 1:
**Only GiggleGit users should be able to access SnickerSync features and SnickerSync should be secure.**

#### Functional Requirements:
- End-to-end encryption
- Use OAuth authentication to log into GiggleGit to use SnickerSync

---

### Non-functional Requirement 2:
**A user study needs to have random assignments of users between control groups and variants.**

#### Functional Requirements:
- Use a coin toss to assign users to control or variant groups.
- Use a spreadsheet to keep track of assignments made.
