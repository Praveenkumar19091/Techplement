# Command line Contact Management System Using Python
## Overview
The Contact Management System is a simple command-line application written in Python. It allows users to manage their contacts by providing functionalities such as adding new contacts, searching for contacts by name, and updating existing contact information. The system uses dictionaries or lists to store contact data and employs file I/O for data persistence.

## Features
- **Add Contact:** Add a new contact with details such as name, phone number, and email.
- **Search Contact:** Search for contacts by their name.
- **Update Contact:** Update existing contact information.
- **Data Persistence:** Save contacts to a file and load them on startup.
## Requirements
- Python 3.x
- No external libraries are required.
## Commands
The program provides a command-line interface with the following commands:
- **Add Contact:** To add a new contact, enter add. You will be prompted to enter the contact's name, phone number, and email.
- **Search Contact:** To search for a contact by name, enter search. You will be prompted to enter the name of the contact.
- **Update Contact:** To update an existing contact, enter update. You will be prompted to enter the name of the contact you want to update and the new information.
- **Exit:** To exit the program, enter exit.
## Data Persistence
Contacts are saved to a file named contacts.txt. The file is automatically created if it does not exist and is updated whenever contacts are added or modified.
