# Trello Board Management Guidelines for Development Teams

The Trello boards are used to track the progress of tasks within each development team (Frontend, Mobile, and Backend) and the [quality assurance team](#trello-board-management-guidelines-for-quality-assurance-teams). Each board is owned and managed by a team lead, who is responsible for ensuring that the board is kept up to date.

<hr>

## Lists for Development Teams

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

<hr>

# Trello Board Management Guidelines for Quality Assurance Teams

The purpose of the Quality Assurance (QA) board is to track and manage the quality of the product by identifying and resolving any defects or issues. It is used to ensure that the product meets the specified requirements and is of high quality before it is released to customers.

<hr>

## Responsibilities

 - The QA Engineer is the primary owner of this board and is responsible for maintaining it.
 - The QA Engineer is responsible for creating test cases and documenting them in the “Features/Test Cases” list.
 - The Technical Support Engineer and QA Engineer are responsible for reporting any defects or issues they encounter to the appropriate tech lead or QA Engineer.
 - The tech leads and QA Engineer are responsible for trying to reproduce the reported defects or issues and moving them to the “Cannot Reproduce” or “Planned” lists accordingly.
 - The tech leads are responsible for ensuring that the correct team member is assigned to each task in the “In Progress” list.
 - The tech leads are responsible for moving tasks to the “Confirm Fix” list once they have been fixed.
 - The QA Engineer is responsible for re-testing the tasks in the “Confirm Fix” list and moving them to the “Done” list if they pass, or the “Rework Required” list if they do not pass.
 - The Product Manager is responsible for reviewing and prioritizing any tasks in the “Rework Required” list.
 - The QA Engineer is responsible for moving tasks to the “Descoped” list if they are no longer relevant or necessary.

<hr>
 
## Lists

 - “Features/Test Cases”: Contains descriptions and links to test cases and other important documentation created by the QA Engineer.
 - “Reported”: Contains a list of tasks that have been reported to the tech leads of each corresponding team or QA Engineer by either the Technical Support Engineer or the QA Engineer. The start date the bug was reported and appropriate labels/tags should be added to the task to denote the affected app.
 - “Cannot Reproduce”: Contains tasks that have been reported but cannot be reproduced by the tech leads or QA Engineer.
 - “Planned”: Contains tasks that can be reproduced and are planned for resolution.
 - “In Progress”: Contains tasks that are currently being worked on. The end date should also be included for each task.
 - “Confirm Fix”: Contains tasks that have been fixed and are waiting to be re-tested by the QA Engineer.
 - “Rework Required”: Contains tasks that did not pass the QA test or require further work. The QA Engineer should assign the card to the Product Manager for review and prioritization.
 - “Done”: Contains tasks that have been fixed and have passed the QA test.
 - “Descoped”: Contains tasks that have been descoped (e.g. no longer relevant or necessary).

<hr>

## Duration

The duration for each task will vary depending on the complexity and severity of the bug. It is important to keep track of the duration of each task so that the QA team can identify areas where improvements can be made and optimise their workflow. Each task in the QA process should have a start and end date, which should be indicated on the Trello board. The start date should be the date that the task is moved to the “Reported” list, and the end date should be the date that the task is moved to the “In Progress” list.

<hr>

## Labels/Tags
Each task should be labeled/tagged appropriately to ensure that it is easy to identify the affected app and the team responsible for the task.

<hr>

## Assignments
The Quality Assurance Engineer is the primary owner of this board and is responsible for it. The QA Engineer should assign tasks to the appropriate team members and tech leads as needed.
