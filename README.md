## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Built with](#built-with)
  - [Useful resources](#useful-resources)
- ## Overview

### The challenge

Users should be able to:

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Create, read, update, and delete boards and tasks
- Receive form validations when trying to create/edit boards and tasks
- Mark subtasks as complete and move tasks between columns
- Hide/show the board sidebar

Expected Behaviour:

- Boards
  - Clicking different boards in the sidebar will change to the selected board.
  - Clicking "Create New Board" in the sidebar opens the "Add New Board" modal.
  - Clicking in the dropdown menu "Edit Board" opens up the "Edit Board" modal where details can be changed.
  - Columns are added and removed for the Add/Edit Board modals.
  - Deleting a board deletes all columns and tasks and requires confirmation.
- Columns
  - A board needs at least one column before tasks can be added. If no columns exist, the "Add New Task" button in the header is disabled.
  - Clicking "Add New Column" opens the "Edit Board" modal where columns are added.
- Tasks
  - Adding a new task adds it to the bottom of the relevant column.
  - Updating a task's status will move the task to the relevant column.

Bonus: 
  - The tasks can be dragged and dropped to a new column.

### Screenshot

![Main page](https://github.com/Kathiravanthirumalalagan/Task_management_VE3/assets/112416858/195f3a0d-c580-4581-8b6f-7c41ccc4d315)
![Add New task](https://github.com/Kathiravanthirumalalagan/Task_management_VE3/assets/112416858/b964e363-8cdb-488f-95e8-6f0f22524d06)
![Sub task page](https://github.com/Kathiravanthirumalalagan/Task_management_VE3/assets/112416858/6c2e6085-e5f7-42e4-ba9b-843d4b8f6679)
![Edit page](https://github.com/Kathiravanthirumalalagan/Task_management_VE3/assets/112416858/d480c80b-e093-4883-8dcc-02ec74368582)
![Delete page](https://github.com/Kathiravanthirumalalagan/Task_management_VE3/assets/112416858/211eb3ad-f4be-4a0a-b70f-c67f2ea10436)

### Built with

- Semantic HTML5 markup
- CSS
- Flexbox
- Mobile-first workflow
- Drag and Drop API
- [React](https://reactjs.org/) - JS library
- [Redux](https://redux.js.org/) - State management tool

