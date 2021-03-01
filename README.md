# Unnamed Time Application
This is a prject for my MSSA Cohort.

## Description
The main focus of this application is to allow a user to be able to prioritize, track, and manage their tasks while using a built in work timer to help focus on completeing them. 




## Wire Frame Diagram

### Home
![WFD Home](https://github.com/jonathan-f-gomez/unnamed-time-application/blob/main/Requirements/Wire-Frame-Diagram/home_page.jpg)

### Create Task
![Create task](https://github.com/jonathan-f-gomez/unnamed-time-application/blob/main/Requirements/Wire-Frame-Diagram/create_task.jpg)

### Task List
![WFD Task List](https://github.com/jonathan-f-gomez/unnamed-time-application/blob/main/Requirements/Wire-Frame-Diagram/task_list.jpg)

### GoPomo Timer
![WFD Pomo](https://github.com/jonathan-f-gomez/unnamed-time-application/blob/main/Requirements/Wire-Frame-Diagram/gopomo.jpg)

### Settings
![WFD Settings](https://github.com/jonathan-f-gomez/unnamed-time-application/blob/main/Requirements/Wire-Frame-Diagram/settings.jpg)



## User Stories
As a Student, I need a website that will help me track my tasks.

As a Student, I need a website that helps me visualize when my tasks are due.

As a Student, I need an way to effectively manage my time while completing my tasks.


## Use-Cases

As a user I need a way to access my task list from anywhere so I can always reference my tasks.

As a user I need a way to add tasks to a list so I can track them.

As a user I need a way to add a name to a task to help easily identify the task.

As a user I need a way to set the priority of a task so I know which one to work on first.

As a user I need a way to set the due date for a task to manage my time.

As a user I need a way to edit a task if I make a mistake or something changes.

As a user I need a way to delete a task to remove it completely.

As a user I need a way to edit the length of my timers so that I can find a time the benefits me the most.


## Use-Case Diagram
![Image of UMLUnNamedTimeApp](https://github.com/jonathan-f-gomez/unnamed-time-application/blob/main/Requirements/UMLUnNamedTimeApp.jpg)


## Requirements

<pre><code>1. The system shall allow the current user to log in, create a user account or continue as a guest.
	1.1 The system shall provide means for an existing user to enter his/her user ID and password.
		1.1.1 Given a user ID, the system shall verify the validity of the user ID and password.
		1.1.2 Given authorization, the system shall allow the user access to their task list.
		1.1.3 The system shall allow the new user to create new user ID and allow the new user to create a password.
		1.1.4 The system shall give access to the application when the user continues as guest.		
	1.2 The system shall allow the user to access the calendar, task list, and timer.
		1.2.1 The system shall allow the user to display the user’s task list.
		1.2.2 The system shall allow the user to display the Pomodoro Timer.
		1.2.3 The system shall allow the user to display the calendar.		
	1.3 The system shall display options to create a new task.
		1.3.1 The system shall display options to edit a task.
		1.3.2 The system shall display options to delete a task.
	1.4 The system shall display options to edit the durations of the timers.		
2. The system shall save the data provided by the user in the application database.
	2.2 the System shall only save data from a guest user for that session.
3. The system shall be developed with C# language, utilizing SQL and ASP.NET .
	3.1 The system shall be hosted in Azure.
</pre></code>
