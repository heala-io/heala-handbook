# Trello Board Management Guidelines for Development Teams

The Trello boards are used to track the progress of tasks within each development team (Frontend, Mobile, and Backend). Each board is owned and managed by a team lead, who is responsible for ensuring that the board is kept up to date.

<hr>

## Lists

 - <strong>Backlog:</strong> Contains tasks from the sprint planning and review meeting, assigned by the Engineering Manager or representative.
 - <strong>Design:</strong> Tasks from the backlog are moved to this list if they are assigned to the product team. The product team should provide links to UI designs or prototypes, after which the task can be moved to the next list (To Do).
 - <strong>To Do:</strong> Agreed tasks for each weekly sprint are moved from the backlog to this list and assigned to the appropriate team member by the tech lead. Each task must have a start and end date (e.g. Mon-Mon) and be tagged accordingly (e.g. Doctor App, Consultation Web App).
 - <strong>Doing:</strong> Contains tasks that have been started by each team member. Team members are responsible for moving tasks to this list and to subsequent lists.
 - <strong>Code Review:</strong> Once a team member has completed a task and created a PR for peer review, they should move the task to this list.
 - <strong>Testing:</strong> After the PR has been reviewed and merged, the team member who reviewed it should move the task to this list, where it will be tested by the QA engineer for quality assurance.
 - <strong>Done:</strong> The final list in the journey of the task. The QA engineer should move tasks that pass testing to this list. If a task does not pass the QA requirements, the QA engineer should move the task back to the To Do list and add a comment with a log of the discovered bugs. The QA engineer should send all logs to the designated team lead, who will assign the fix to themselves or another team member. The task will continue through this flow until it passes quality assurance and can be moved to Done.

<hr>

## Responsibilities

 - <strong>Team leads:</strong> Owners of the Trello boards, responsible for keeping the boards up to date and clearing them once a month after the KPI meeting. Also responsible for assigning tasks in the To Do list to appropriate team members.
 - <strong>Product team:</strong> Responsible for providing UI designs or prototypes for tasks in the Design list.
 - <strong>Team members:</strong> Responsible for moving tasks to the Doing list once they have started work on them, and for moving tasks to the Code Review list once they have created a PR. Also responsible for moving merged tasks to the Testing list.
 - </strong>QA engineer:</strong> Responsible for testing tasks in the Testing list and moving tasks to the Done list if they pass QA testing, or back to the To Do list if they do not.

<hr>

## Duration

Each task should have a start and end date, which should be included in the task description. The duration of the task should be agreed upon in the sprint planning and review meeting and should take into account the complexity and estimated time needed to complete the task. 

<hr>

## Dating
Tasks should be dated in the format “Mon-Mon” (e.g. “Jan 4-Jan 11") to indicate the start and end dates for the work to be completed. The duration of each task should be agreed upon in advance and should be reasonable given the complexity and scope of the work involved.

<hr>

## Labeling

Each task should be labeled with a descriptive title that accurately reflects the work to be completed.
Tasks should also be tagged with the relevant project or product (e.g. “Doctor App”, “Consultation Web App”, etc.)

<hr>

## Assignment
Team leads are responsible for assigning tasks to team members in the “To Do” list.
Team members are responsible for accepting or rejecting the assignment of a task, and for updating the status of their own tasks as they progress through the different lists on the board.

<hr>

## Note
All team members are expected to participate in the updating of the Trello boards, by moving tasks through the appropriate lists as they progress through the development process
