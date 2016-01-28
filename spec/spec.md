Requirements
============
A. 5 Types of Users
----------------
*All users have read access*

1. **Read-Only User**
  1. Can view business plan objectives and business plan actions as well as any team / departmental goals
2. **Basic User**
  1. Can update the status field of goals assigned to them
  2. Can view all other team / department goals
3. **Team / Department Lead User**
  1. Can create, modify, and delete their own team / department's goals
  2. Can view all other team / department goals
4. **Business Plan Lead User**
  1. Can create, modify, and delete business plan objectives and business plan actions as well as any team / departmental goals
5. **Administrator User**
  1. Can create, modify, and delete business plan objectives and business plan actions as well as any team / departmental goals
  2. Can create, delete and modify all types of users
  
B. Login
------
1. Login will consist of a username and password.
2. A note directing users to speak with Administrator if they have forgotten their account information.

C. User Homepage
-------------
1. Show user's name and position within the EPL.
2. Show timeline:
  1. Include team / department goals
  2. Include business plan objectives and actions
3. Search bar to search for business plan objectives and actions or team / department goals.
4. Show Notifications.
  1. Notify user when they are assigned to a business plan objectives and actions or team / department goals.
  2. Notify Business Plan Manager and appropriate Team Lead when the status of an action, objective or goal is changed.
  3. Email notifications (Expanding our software)

D. Goal/Task Info Page
----------------------
1. Ability to edit account information if allowed
2. Show action information
3. Indicate if this action is part of the business plan; if it is, indicate the number the action coresponds to.
4. Show due date
5. Show Team Lead responsible for action and other colaberators for the action.
6. Ability to update the status of the goal if Team lead or Business Plan Lead to:
  1. Incomplete - Action has not been started to be worked on
  2. In Progress - Action is currently being worked on
  3. Complete - Action has been completed.
7. Indicate a "Success Measure" to know what most be completed for the action to be complete.
8. Additional Notes
9. Administrator, Business Plan Lead, and Team Lead can add additional fields to an action.
  1. ie. Budget

***

User Stories
============
As a Read-Only User, I want to be able to log into my account.
  - *Refers to B1 in Specifications*
As a Read-Only User, I want to view the business plan objectives.
  - *Refers to A1.1 in Specifications*
As a Read-Only User, I want to view the business plan actions.
  - *Refers to A1.1 in Specifications*
As a Read-Only User, I want to view all team / department goals.
  - *Refers to A1.1 in Specifications*
As a Read-Only User, I want to search for business plan objectives, actions, and team / department goals using keywords.
  - *Refers to C3 in Specifications*
As a Read-Only User, I want to view a timeline for upcoming business plan objectives, actions and team / department goals.
  - *Refers to C2 in Specifications*
As a Read-Only User, I want to view everyone that is involved in the completion of an action.
  - *Refers to D5 in Specifications*
As a Read-Only User, I want to know when due dates are upcoming for recent actions.
  - *Refers to D4 in Specifications*
As a Read-Only User, I want to view the current status of an action.
As a Read-Only User, I want to know the requirements for an action.
  
As a Basic User, I want to be able to log into my account.
  - *Refers to B1 in Specifications*
As a Basic user, I want to update the status field of goals assigned to me.
  - *Refers to A2.1 in Specifications*
As a Basic User, I want to view all team / department goals.
  - *Refers to A2.2 in Specifications*
As a Basic User, I want to search for business plan objectives, actions, and team / department goals using keywords.
  - *Refers to C3 in Specifications*
As a Baisc User, I want to view a timeline for upcoming business plan objectives, actions and team / department goals.
  - *Refers to C2 in Specifications*
As a Basic User, I want to view everyone that is involved in the completion of an action.
  - *Refers to D5 in Specifications*
As a Basic User, I want to know when due dates are upcoming for recent actions.
  - *Refers to D4 in Specifications*
As a Basic User, I want to view the current status of an action.
As a Basic User, I want to know the requirements for an action.
  
As a Team / Department Lead User, I want to be able to log into my account.
  - *Refers to B1 in Specifications*
As a Team / Department Lead User, I want to create, modify, and delete my own team / department goals.
  - *Refers to A3.1 in Specifications*
As a Team / Department Lead User, I want to view all other team / department goals.
  - *Refers to A3.2 in Specifications*
As a Team / Department Lead User, I want to search for business plan objectives, actions, and team / department goals using keywords.
  - *Refers to C3 in Specifications*
As a Team / Department Lead User, I want to view a timeline for upcoming business plan objectives, actions and team / department goals.
  - *Refers to C2 in Specifications*
As a Team / Department Lead User, I want to view everyone that is involved in the completion of an action.
  - *Refers to D5 in Specifications*
As a Team / Department Lead User, I want to know when due dates are upcoming for recent actions.
  - *Refers to D4 in Specifications*
As a Team / Department Lead User, I want to view the current status of an action.
As a Team / Department Lead User, I want to know the requirements for an action.
  
As a Business Plan Lead User, I want to be able to log into my account.
  - *Refers to B1 in Specifications*
As a Business Plan Lead User, I want to create, modify, and delete business plan objectives.
  - *Refers to A4.1 in Specifications*
As a Business Plan Lead User, I want to create, modify, and delete business plan actions.
  - *Refers to A4.1 in Specifications*
As a Business Plan Lead User, I want to create, modify, and delete any other team / departmental goals.
  - *Refers to A4.1 in Specifications*
As a Business Plan Lead User, I want to search for business plan objectives, actions, and team / department goals using keywords.
  - *Refers to C3 in Specifications*
As a Business Plan Lead User, I want to view a timeline for upcoming business plan objectives, actions and team / department goals.
  - *Refers to C2 in Specifications*
As a Business Plan Lead User, I want to view everyone that is involved in the completion of an action.
  - *Refers to D5 in Specifications*
As a Business Plan Lead User, I want to know when due dates are upcoming for recent actions.
  - *Refers to D4 in Specifications*
As a Business Plan Lead User, I want to view the current status of an action.
As a Business Plan Lead User, I want to know the requirements for an action.

As an Administrator User, I want to be able to log into my account.
  - *Refers to B1 in Specifications*
As an Administrator User, I want to create and assign new users and groups.
  - *Refers to A5.1 in Specifications*
As an Administrator User, I want to create, edit and modify all types of users.
  - *Refers to A5.2 in Specifications*
As an Administrator User, I want to search for business plan objectives, actions, and team / department goals using keywords.
  - *Refers to C3 in Specifications*
As an Administrator User, I want to view a timeline for upcoming business plan objectives, actions and team / department goals.
  - *Refers to C2 in Specifications*
As an Administrator User, I want to view everyone that is involved in the completion of an action.
  - *Refers to D5 in Specifications*
As an Administrator User, I want to know when due dates are upcoming for recent actions.
  - *Refers to D4 in Specifications*
As an Administrator User, I want to view the current status of an action.
As an Administrator User, I want to know the requirements for an action.