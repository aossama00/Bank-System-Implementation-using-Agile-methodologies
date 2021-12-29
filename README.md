# Bank-system
# Part 1
## Team Members involved in each team:

### Frontend team:
Name | Role	| Expertise
---- | ---- | --------
Youssef Ali|	GUI | Java
Ali Ahmad|	IT support |	Python
Ahmad Sobhy |	Security |	C++

### Backend team:
Name | Role	| Expertise
---- | ---- | --------
Omar Fathy |	Database |	SQL
Abdullah Yehia |	Account functionalities |	Python
Ahmad Ossama |	Web development | Javascript
Yara Wagdy|	Data Science | R

### Testing team:
Name | Role	| Expertise
---- | ---- | --------
Khaled Emad |	Unit Testing |	SQL
Adel Sameh |	Integration Testing |	Python & Java
Sara Sabry|	System Testing |	C++

## Project description
Our product is a highly secured banking system that is only accessed by authorized users, it stores accounts of customers and their amount of money. Customers can transfer money between accounts by the help of employees. There are 10 members working on this project in an agile manner. We aim to create a suitable sized database that can contain all records needed linked with a friendly graphical user interface that all users can handle easily so that it can cover all banking responsibilties required. Employees will be able to handle all customers accounts' functionalities using the system

## My product Vision
### Stakeholders:
* Bank Owner
* Bank Managers
* Bank employees

### Far Vision:
Create a banking system that have a user friendly GUI handled by employees and managers that can do the following:
Create/edit/delete accounts
Manage loans and benefits
Deposit/withdraw money 
Check customers' account details

### Near Vision (Sprint 1):
Create a secured database that contain all customers' accounts
Assign database access to only authorized users
Friendly user interface with homepage that allow users to login to the system
Employees can add new customers to the database

### Near Vision (Sprint 2):
Create employee's account page
Employees edit and control all customer's functionalities

## User Story Points estimation convention:
Fibonacci Series (1, 2, 3, 5, 8, 13...), where 13 represents big story that needs a lot of functionalities and could be vague to the members so it will take about 5 working days. While 1 and 2 points represent well-known stories as homepage or account page design that does not need an effort and could be finished in 1 day or less. 3 represent well known stories but requires more testing that takes 2 days. 5 and 8 represent around 3 - 4 days.

## Product Backlog Items (ordered rationale):
The rationale of this order of my Product Backlog Items is that our team see it is the most important thing to crete a secured database to hold all customers' accounts.
then it must be secured to prevent data theft. Then the employee will need to login through a homepage to his account. After that the system verify his login details. to move the user (employee) to his account page (which is completed in sprint 2). Then employee and manager could be able to add records to the database.Then the design of the account of employee is done in sprint 2 which allow the employee to do all the customers ' account functionalities. Here are some of the PBIs ordered from the highest priority to least ones.
* A user friendly interface with homepage that have system login credentials is needed at the first thing to allow users to enter system easily before anybanking complications (assigned to Ahmad Ossama & Ali Mohamed). This story has the highest business value for the product owner as he wants simple UI to start acting with the system.
* Database created and must be accessed by only authorized users to prevent any corruption of confidential data as customers' account numbbers and transactions so it is very important to be finished quickly (assigned to Ahmad Sobhy & Sara Sabry)
* Register/login new user account to the system is very important after storing records for login credentials in database to allow the users to use the system freely using their private accounts (assigned to Khaled Emad)
* After that the employee can now add customers to the database so this option will be qualified for him to add them in database (assigned to Yara Wagdy).
* Then Employee could also add records as transactions to customers' accounts which is dependent on the previous story (assigned to Yara Wagdy).
* Manager which can also login to the system should have functionality of adding new employees has the least priority as adding new employees was not of high business value for the product owner (assigned to Omar fathy).
* Then in the second epic the employee will be able to enter his account to control customers' accounts details. This point has high business value but it comes after all database and UI design is set to be able to work in bug-free environment. (assigned to Youssef Ali).
* After that comes the stories of functionalities with less priorities that doesnot have to be ordered as withdrawal, depositing, adding records..etc. As they are all of same importance and have similar loads. (assigned to Ahmed Sobhy).

The whole order of PBIs can be seen in the screenshots document 



# Part 2

## 1. Story Points
Our team could do up to an average of 40 points in each sprint. Each sprint is 3 weeks. As sprint 1 was estimated as 34 and sprint 2 was 39.

## 2. Daily Scrum Document
### Example 1
Team Member  | Question	| Sunday    | Monday | Tuesday | Wednesday	| Thursday
------------ | --------  | -------- | ------ | ------  | ------    | ------
Ali Mohamed  | What did you do yesterday?	| Started UI design | Add textfields & buttons | Started updating customer database | Started creating homepage	| Homepage features testing
Ali Mohamed  | What are you doing today?	| Security testing on database | Added features to the homepage | Unit testing on each record of database | Still editing homepage	| Finishing UI design
Ali Mohamed  | Is there anything blocking you?	|   - | Homepage takes > 1 second to reload  | Some records are missing in database | Web design seems a bit unorganized |  -

## 2. Daily Scrum Document
### Example 2
Team Member    | Question	| Sunday    | Monday | Tuesday | Wednesday	| Thursday
-------------- | --------  | -------- | ------ | ------  | ------    | ------
Abdullah Yehia | What did you do yesterday?	| Started java coding for money withdrawal | Added customers to the database | Adding features to the employee's account | Unit testing on money withdrawal functionality	| hyperlink login page with employee's account
Abdullah Yehia | What are you doing today?	| Security testing on database | Solving bugs found in the code | Reviewing GUI on the whole system | Integration Testing for money withdrawal with	other functionalities| Finishing Java coding
Abdullah Yehia | Is there anything blocking you?	| bugs in the java code | Some employees cannot reach their accounts | Sytem cannot handle more than 100 users |   - |   -

## 3. Sprint Document
### Sprint 1

#### Sprint 1 Goal:
* A secured database that contain all customers' accounts shall be created and tested
* Assign database access to only authorized users
* A friendly user interface with homepage that allow users to login to the system shall be created
* Register new account functionality is implemented and tested to add new employees to the system
* Security Testing is done on the database before moving to another sprint 

#### Delivered Epic: 
Secure Database


### Sprint 2
#### What was done in the last sprint:
All items of sprint 1 were finished before the beginning of Sprint 2 except the last PBI which allow the manager to add employees as it needs extensive testing.
Hence it will be done in the start of sprint 2

#### Sprint 2 Goal:
* Create employee's account page
* Employees edit and control all customer's functionalities
* Unit Testing on the employee account page functionalities 
* Integration testing would be done between login page and account page

#### Delivered Epic:
Customer Account Functionalities

## 4. WorkFlow
### 4.1. Rationale
All stories at first are put in the "TO DO" state. After starting the sprint, stories at the begining of thesprint moves to "IN PROGRESS" state.
Then this story starts working and moves to the "TASK REVIEW" state which evaluates the task and ensures it passes the definition of acceptance.
If it passes the acceptance criteria and state ensures it is completed, it can be accepted and moves to "DONE" state. Otherwise, the task would fail task review and marked as uncompleted task so it moves back to "IN PROGRESS" state
Once the story reaches the "DONE" state it cannot move back to any state. It has to be carried to the next sprint if any problems occur in the sprint planning meeting

### 4.2 Rules:
Assign Task review state and the transition of acceptance criteria to Khaled Emad, Sara Sabry and Adel Sameh (Testing team) to indicate wether this task is accepted or failed and need to move back to "IN PROGRESS" again.
Transition of stories between states cannot be done except by me (Ahmad Ossama) and the testing team members (Khaled Emad, Sara Sabry and Adel Sameh).
Story cannot jump to "TASK REVIEW" from "TO DO" as it must moves first to "IN PROGRESS" state. As well as it  cannot jump to "DONE" from "IN PROGRESS" as it must moves first to "TASK REVIEW" state.
No story can move from "IN PROGRESS" back to "TO DO" state as this will disturb the rest of the team. Whenever an assignee take a story he has to work on it.
