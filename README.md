# HousewareSEIntern2024
Houseware, Software Engineer Intern, Frontend

# Test Plan for TodoMVC React Application

## Overview
The TodoMVC application is a simple todo list management system built using React. The primary objective of testing this application is to ensure its functionality, including correct behavior of components and handling of user interactions.

## Components to Test
1. TodoItem
2. TodoList
3. TodoApp

## Types of Tests
1. **Unit Tests:** Test individual functions and components in isolation.
2. **Integration Tests:** Test the interaction between different components.
3. **End-to-End Tests:** Test the entire application flow from user input to output.

## Test Cases

### 1. TodoItem Component
- **Unit Tests:**
  - Verify rendering of todo item with completed and incomplete states.
  - Ensure toggle functionality of todo item.
  - Validate edit functionality of todo item.
  - Confirm delete functionality of todo item.
- **Integration Tests:**
  - Validate interaction between todo item and todo list (e.g., toggling, editing, deleting).
- **End-to-End Tests:**
  - Test the entire lifecycle of a todo item (creation, editing, deletion).

### 2. TodoList Component
- **Unit Tests:**
  - Ensure rendering of todo list with various numbers of items.
  - Validate filtering functionality of todo list (all, active, completed).
  - Test clear completed functionality.
- **Integration Tests:**
  - Validate interaction between todo list and todo item components.
- **End-to-End Tests:**
  - Test adding, toggling, editing, and deleting todo items in the list.

### 3. TodoApp Component
- **Unit Tests:**
  - Verify rendering of the entire application.
  - Test adding new todo items.
  - Test clear all functionality.
- **Integration Tests:**
  - Validate interaction between todo app, todo list, and todo item components.
- **End-to-End Tests:**
  - Test the complete flow of the application from adding todos to clearing them.

## Sample Tests
1. **Unit Test for TodoItem Toggle Functionality:**
   - **Description:** Test if toggling a todo item changes its completed state correctly.
   - **Steps:**
     1. Create a mock todo item with an initial completed state.
     2. Toggle the todo item.
     3. Assert that the completed state has been toggled correctly.

2. **Integration Test for TodoList and TodoItem:**
   - **Description:** Test if toggling a todo item in the list updates the list correctly.
   - **Steps:**
     1. Render a todo list with multiple todo items.
     2. Toggle one of the todo items.
     3. Assert that the todo item's completed state has been updated in the list.

3. **End-to-End Test for Adding a Todo Item:**
   - **Description:** Test if adding a new todo item results in the correct rendering.
   - **Steps:**
     1. Load the application.
     2. Add a new todo item.
     3. Assert that the new todo item is rendered correctly in the list.

## GitHub Repository
You can find the implementation of the test plan along with the TodoMVC React application in the following GitHub repository: [TodoMVC React Testing](https://github.com/imvenkatesanc/housewareintern2024)
