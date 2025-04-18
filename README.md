# Personal Assistant Bot

A simple command-line assistant bot that manages contacts and responds to basic commands.

## Features

- **Add contacts**: Store a new contact with a name and phone number (`add <name> <phone>`).
- **Change contacts**: Update an existing contact's phone number (`change <name> <new_phone>`).
- **Show phone**: Retrieve a contact's phone number (`phone <name>`).
- **List all**: Display all saved contacts (`all`).
- **Greetings and exit**: Responds to `hello` and exits on `exit` or `close`.

## Requirements

- Python 3.6 or higher

## Installation

**Clone the repository**

```bash
if [ ! -d "homework1-2" ]; then
  git clone https://github.com/<your-username>/homework1-2.git
fi
cd homework1-2
```

## Usage

```bash
python3 homework1-2.py
```

## Available Commands

- `hello` – Bot greets you.
- `add <name> <phone>` – Adds a new contact.
- `change <name> <phone>` – Changes an existing contact’s phone.
- `phone <name>` – Shows the phone number for the contact.
- `all` – Lists all contacts.
- `exit` or `close` – Exits the program.

## Example Session

```
Welcome to the assistant bot!
Enter a command: hello
How can I help you?
Enter a command: add Alice 123456789
Contact added.
Enter a command: phone Alice
123456789
Enter a command: all
Alice: 123456789
Enter a command: change Alice 987654321
Contact updated.
Enter a command: phone Alice
987654321
Enter a command: close
Good bye!
```
