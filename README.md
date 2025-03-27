# Contact App

## Overview
The **Contact App** is a simple command-line application that allows users to manage their contacts efficiently. This project utilizes Python data structures, string manipulation, regular expressions, and file handling to implement a basic contact management system.

## Features
- Display all contact names
- Search for a contact by name
- View details of a selected contact
- Add new contacts
- Update existing contact information
- Delete contacts
- Interactive menu for user-friendly navigation

## Data Structure Used
The application uses a **list of dictionaries** to store contact information. Each contact is stored as a dictionary with the following keys:
- `name`: Contact's name (string)
- `number`: Contact's phone number (integer)
- `email`: Contact's email address (string)

Example data structure:
```python
contacts = [
    {'name': 'Aisha', 'number': 6814967831, 'email': 'aisha@gmail.com'},
    {'name': 'Payal', 'number': 8691236971, 'email': 'payal@gmail.com'},
    {'name': 'Krisha', 'number': 96328432897, 'email': 'krisha@gmail.com'}
]
```

## Functions Implemented
### 1. `show_contacts(contacts)`
Displays all contact names.

### 2. `add_contact(contacts)`
Prompts the user to enter a new contact's details and adds it to the contact list.

### 3. `delete_contact(name_del)`
Deletes a contact based on the provided name.

### 4. `update_contact(contacts)`
Updates the details of an existing contact.

### 5. `open_contact()`
Searches for a contact by name and displays the details if found. Also provides options to update or delete the contact.

### 6. Main Application Loop
Uses an infinite loop to present a menu for user interaction. The user can choose actions like adding, searching, updating, or deleting contacts until they exit the program.



