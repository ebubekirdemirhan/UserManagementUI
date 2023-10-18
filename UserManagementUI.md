# User Management Screen

## Requirements

The User Management Screen is designed to manage user information, including user names, email addresses, user roles, and user enable/disable status. The following features and components are required:

- Display a list of existing users with their details.
- Add a new user with the ability to set user name, display name, phone, email, user roles, and enable/disable status.
- Update user information.
- Delete users.
- Show user roles as selectable options.
- Display user details, including User Name, Display Name, Phone, Email, User Roles, and Enabled status.

## UI Components

### Existing Users List

Display a table with the following columns:

| ID  | User Name    | E-Mail                | Enabled |
| --- | ------------ | --------------------- | ------- |
| 1   | AdminUser    | admin@piworks.net     | True    |
| 2   | Test User    | testuser@piworks.net  | True    |

- ID: A unique identifier for the user.
- User Name: The name of the user.
- E-Mail: The user's email address.
- Enabled: Indicates whether the user account is enabled or disabled (True/False).

### New User Form

A form to add or update a user with the following fields:

- User Name: Text input for the user's name.
- Display Name: Text input for the user's display name.
- Phone: Text input for the user's phone number.
- E-Mail: Text input for the user's email address.
- User Roles: A dropdown menu to select user roles with the options: "Guest," "Admin," and "SuperAdmin."
- Enabled: A checkbox to enable or disable the user account.

## Behavior

- When the page loads, it should display the list of existing users.
- Users can add a new user by filling out the New User form and clicking the "Add User" button.
- Users can edit an existing user's details by selecting a user from the list and clicking the "Edit" button.
- Users can delete a user by selecting a user from the list and clicking the "Delete" button. A confirmation prompt should appear.
- User Roles should be selected from a dropdown menu.
- Enabled checkbox should be used to enable or disable the user account.

## Initial View

When the page is first loaded, it should display the list of existing users in the "Existing Users List" table.

