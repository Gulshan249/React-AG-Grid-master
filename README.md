# User Management: User Management with React and AG Grid

UserMaster is a React application that enables users to perform CRUD (Create, Read, Update, Delete) operations on a user list. The user list is displayed in an AG Grid table with features for filtering and cell editing.

# Table of Contents

- Features
- Live Demo
- Prerequisites
- Installation
- Usage


# Features
- CRUD Operations: Add, read, update, and delete users.
- User Fields: Name, Email, Address, and Phone No.
- Validation
  - Name: Required, minimum 3 characters.
  - Email: Required, must be a valid email format.
  - Address: Required.
  - Phone No: Required, must be a valid phone number.
  - AG Grid Integration:
  - Filtering: Filter the list based on any field.
  - Cell Editing: Edit user details directly within the table cells.

# Live Demo
You can see UserMaster in action by visiting the following link:

UserMaster - https://react-ag-grid-project.vercel.app/

# Prerequisites
Ensure you have the following tools installed:

  - Node.js (>= 14.0): Download and Install Node.js
  - npm (>= 6.0): npm is included with Node.js. Check your npm version with npm -v.

# Installation

- Clone the Repository:
  - git clone https://github.com/Gulshan249/React-AG-Grid-master
  cd React-AG-Grid-master

- Install Dependencies:
  - npm install

- Start the Application:
  - npm start

# Usage
Here’s a guide on how to interact with the UserManagement application for managing user data:

- Add a User

  - A form will pop up. Fill in the user details in the following fields:
  - Name: (Required) Enter at least 3 characters.
  - Email: (Required) Must be a valid email format.
  - Address: (Required) Enter a valid address.
  - Phone No: (Required) Enter a valid phone number format.
  
After filling in the details, click the "Save" button to add the user to the list.
The user will now appear in the table with the details provided.

- Edit a User
  - Locate the user you want to edit in the table.
  - Click directly on the cell that contains the information you want to update. The cell will become editable.
  - Make the necessary changes to the information. Changes are saved automatically once you click outside the cell or press Enter.
  - The table will update immediately to reflect your changes.
 
- Delete a User
  - Find the user you want to remove in the table.
  - Click the "Delete" button located in the Actions column corresponding to the user. This button is typically represented by a trash can icon or labeled as "Delete".
  - The user will be removed from the list instantly, and the table will update to show the remaining users.

- Filter Users
  - Each column in the table has a filter box at the top.
  - Click on the filter box of the column you want to filter.
  - Choose the filter option you need from the dropdown list. Options include:
  - Contains: Shows rows where the column contains the specified text.
  - Does Not Contain: Shows rows where the column does not contain the specified text.
  - Equals: Shows rows where the column exactly matches the specified text.
  - Does Not Equal: Shows rows where the column does not match the specified text.
  - Blank: Shows rows where the column is empty.
  - Not Blank: Shows rows where the column is not empty.
  - Enter the text or select the criteria you want to filter by.
  - The table will dynamically update to show only the rows that meet the filter criteria.
