# Web To-Do List
## Author: Richard Coucoules

This project is a web-based to-do list app built with Vue.js. This app is considered complete and has reached end of development. For posterity, the development requirements are retained below.

### Upon completion, the app will have the following functionality:
  - [x] The user should be able to add tasks to the app.
  - [x] The user should be able to delete tasks from the app.
  - [x] The user should be able to check tasks off of the app and see that they are complete.
  - [x] The user should be able to save their to-do list.

### The following features are planned to be added to meet these functional requirements:
  - [x] The user will initially be presented with a new task prompt to create a new task.
    - [x] The new task prompt will appear as the first task in the task area upon page load.
    - [x] The new task prompt will have an input section where the user can enter the task name.
    - [x] The user will have an accept button to add the task to the task list.
  - [x] The user will be able to press the "+" at the bottom right of the task list to generate a new task prompt at the bottom of the task list to create additional tasks.
    - [x] In addition to the properties listed above, the new task prompt for all tasks except the first will have a cancel button to cancel the process of task creation.
  - [x] Tasks in the task list will have a trash can icon on the right hand side. Clicking this icon will allow the user to delete the associated task.
    - [ ] ~~UNDER CONSIDERATION: Present the user with a confirm screen to confirm task deletion.~~
  - [x] Tasks in the task list will have a check box on the left hand side. Checking this box will signify the task is complete.
    - [x] The title of the task will be italicized, the text will be struck through, and the text color will be lightened to signify task completion.
    - [ ] ~~UNDER CONSIDERATION: Move the completed task to the bottom of the to-do list.~~
  - [x] The user will be able to click a link to save the contents of their to-do list.
    - [ ] ~~UNDER CONSIDERATION: Allow the user to download the contents of their to-do list and upload the downloaded file to repopulate an empty to-do list.~~
    - [x] UNDER CONSIDERATION: Allow the user to save the to-do list on the server by entering a unique string as an identifier.
