# User Management Screen UI Specification

## Requirements:
- Provide a clear overview of existing users.
- Enable administrators to add new users.
- Allow easy management and navigation of user information.

## UI Components:
- **User List Table:** Displays existing users with columns for ID, Username, Email, and Status (Enabled/Disabled).
- **New User Button:** Triggers a form to input details for a new user.
- **Hide Disabled Users Toggle:** Filters the view to show/hide disabled user accounts.

## Initial Display:
- The user list table is populated with all users, both enabled and disabled.
- The ‘New User’ button is visible and accessible.
- The ‘Hide Disabled Users’ toggle is set to show all users.

## Behavior:
- **Adding a New User:**
  - Clicking the ‘New User’ button opens a form with fields for Username, Display Name, Phone, Email, and a checkbox for ‘Enabled’.
  - A dropdown for ‘Role’ selection is provided with options like Guest, Admin, and SuperAdmin.
  - A ‘Save User’ button submits the form and adds the new user to the list.
- **Filtering Users:**
  - The ‘Hide Disabled Users’ toggle filters out disabled users from the list when activated.
  - Toggling again will revert the list to show all users.

## Form Validation:
- All fields are required except for the Phone number, which is optional.
- The Email field must validate for the correct format.
- Upon submission, if any errors are detected, they are highlighted with error messages displayed near the respective fields.
