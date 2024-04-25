### [JSL11] Agile Board - Kanban Task Management App

LOOM Presentation link: [https://www.loom.com/share/a15cd9375a5742608fc4bee3abb04f8f?sid=d4a642a6-68cb-432b-afc8-ffc06c2621de]

# Project Overview
- In this final project I was tasked to tackle the provided user stories to both identify and fix bugs in the code, as well as to develop my own functions to extend the application's capabilities. Key assignments included importing utility functions, initializing data, and diving into debugging tasks such as setting up data correctly in local storage, dynamically displaying boards and tasks, and enhancing user interactions.

# Elements Included 

### Task Interaction and Detail Management
- *Clicking an Individual Task for Details*: As a user, I want to click on an individual task so that I can view its details and make edits if necessary.
- *Opening the Task Edit Modal*: As a user, I want to open a modal window when adding or editing tasks to easily input task information.
- *Updating the Task Title*: As a user, I want to update the task title within the modal to change how it’s displayed on the board.
- *Updating the Task Description*: As a user, I want to update the task description within the modal so I can better describe what needs to be done.
- *Updating the Task Status*: As a user, I want to update the current status of a task (todo, doing, done) to track its progress.
- *Saving Task Changes*: As a user, I want to save the changes I make to a task so that the updated details are stored and displayed.
- *Updating the UI with Task Changes*: As a user, I expect the changes I make to a task to be reflected immediately on the UI without needing to refresh.
- *Deleting a Task from the Edit Modal*: As a user, I want the ability to delete a task directly from the edit modal if it’s no longer needed.
- *Canceling Edits Without Saving*: As a user, I want to be able to cancel my edits and close the modal without saving to avoid accidental changes.
- *Editing Task Details*: As a user, I want to edit the details of an existing task to correct or update information as needed.
- *Easy Navigation Between Task Statuses*: As a user, I want to easily move tasks between statuses (todo, doing, done) to reflect their current progress.
- *Viewing Task Details*: As a user, I want to view detailed information about a task to understand its scope and requirements fully.

### Task Deletion and Confirmation Mechanisms
- *Clicking "Delete Task" Button*: As a user, I want to click a "Delete Task" button within the task edit modal so I can remove tasks that are no longer necessary.
- *Immediate UI Update on Task Deletion*: As a user, I expect a task to disappear from the UI immediately after I confirm its deletion to reflect the current state of my task list.


### Theme Customization
- *Switching to Dark Mode*: As a user, I want to switch to dark mode so that I can reduce eye strain in low-light conditions.
- *Switching Back to Light Mode*: As a user, I want to switch back to light mode from dark mode to better suit bright environments and see the logo update accordingly.


### Managing the Sidebar
- *Hiding the Side Bar for More Workspace*: As a user, I want the ability to hide the side bar to gain more workspace.
- *Opening the Side Bar for Navigation and Options*: As a user, I want to easily open the side bar to navigate between boards.


### Task Lifecycle Management
- *Clicking "Add New Task" to Start Adding a Task*: As a user, I want to click the "Add New Task" button so I can begin the process of adding a new task to my board.
- *Modal Opens for New Task Input*: As a user, I expect the modal to open when I click "Add New Task" to provide me with a form to input the task's details.
- *Adding a Title to the New Task*: As a user, I want to be able to add a title to my new task so I can clearly identify it on the board.
- *Adding a Description to the New Task*: As a user, I want to be able to add a description to my new task to provide more details about what needs to be done.
- *Selecting a Status for the New Task*: As a user, I want to select a status for my new task (e.g., Todo, Doing, Done) to categorize it based on its progress.
- *Creating the New Task*: As a user, I want to click a "Create Task" button in the modal to save the new task to the board.
- *New Task Appears in UI Under Correct Status*: As a user, I expect the new task to appear in the UI under the correct status column immediately after creation.
- *Viewing New Task Details*: As a user, I want to view detailed information about the New Task to understand its scope and requirements fully.
- *Editing New Task Details*: As a user, I want to edit the details of the New Task to correct or update information as needed.


### Local Storage and Data Persistence
- *Saving New Tasks in localStorage*: As a user, I want my newly created tasks to be saved in localStorage so that my tasks persist even when I close or refresh the browser.
- *Reflecting Task Updates in localStorage*: As a user, I expect tasks that I update to have their changes reflected in localStorage so that any modifications are not lost.
- *Removing Deleted Tasks from localStorage*: As a user, I want tasks that I delete to be removed from localStorage so that my task list remains accurate and up-to-date.

# Reflections
## Areas of Mastery 
- Using the '.addEventListeners' method to attach an event handler to a specific element. I feel much more comfortable with this method and am ready to use more of it in future projects.

## Challenges Faced
- Getting my toggleTheme function to work as it didn't switch themes accordingly.
- Coding a declaration that ensures that the "AGILE BOARD" svg/logo switches from dark to light in accordance to the theme. 
- Having to debug my project while paying attention to the information in the local storage was a hassle because I couldn't rememeber what was saved in the storage and was often confused. 

## Areas of Improvement 
- I would like to improve on manipulating elements' classes in my JavaScript file by using the '.classList' property and the 'querySelector' method in order to interact with the UI in my projects.
- Importing functions from a different file.

# Overall Learning Experience
- Throughout this project I had to enhance the application by crafting code to meet specific functionalities outlined in the user stories, like managing task details, toggling theme customization, and ensuring the persistence of data through local storage. This blend of debugging and creative coding allowed me to apply my critical thinking and problem-solving skills in a hands-on manner, equipping me for the intricacies of real-world software development scenarios. Although it was quite challenging and frustrating, it definitely paid off at the end because I was able to complete my project.