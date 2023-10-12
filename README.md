# Airbnb Clone Project

## Description

This Airbnb Clone project is a Python-based command-line application that simulates a simplified version of the popular Airbnb platform. It allows users to manage property listings, search for accommodations, and make reservations, all from the command line.

## Command Interpreter

The command interpreter is the core of this Airbnb Clone project. It provides a set of commands that allow users to interact with the application. These commands include, but are not limited to:

- `create`: Create new user accounts, property listings, and reservations.
- `show`: Display detailed information about specific users, properties, and reservations.
- `update`: Modify user, property, and reservation details.
- `destroy`: Remove users, properties, and reservations from the system.
- `all`: List all available users, properties, and reservations.
- `quit` or `EOF`: Exit the command interpreter.

## How to Start

To start the Airbnb Clone project, follow these steps:

1. Clone the project repository from GitHub:
git clone https://github.com/your-username/airbnb-clone.git

2. Change your working directory to the project folder:
cd airbnb-clone

3. Create a virtual environment (optional but recommended):
python3 -m venv venv
source venv/bin/activate

4. Install the required dependencies using pip:
pip install -r requirements.txt

5. Run the command interpreter:
python console.py


## How to Use

Once the command interpreter is running, you can use the following commands to interact with the Airbnb Clone project:

- `create <class> <attributes>`: Create a new user, property, or reservation with specified attributes.
- `show <class> <id>`: Display detailed information about a specific user, property, or reservation.
- `update <class> <id> <attributes>`: Update attributes of an existing user, property, or reservation.
- `destroy <class> <id>`: Remove a user, property, or reservation from the system.
- `all <class>`: List all available users, properties, or reservations.
- `quit` or `EOF`: Exit the command interpreter.

Make sure to replace `<class>`, `<id>`, and `<attributes>` with the appropriate class name (user, property, reservation), ID, and attribute values.

## Examples

Here are some examples of how to use the command interpreter:

1. Create a new user:
create User first_name="John" last_name="Doe" email="johndoe@example.com" password="securepassword"

2. Show information about a specific property:
show Property 1234

3. Update a user's email address:
update User 5678 email="newemail@example.com"

4. Destroy (delete) a reservation:
destroy Reservation 9876

5. List all available properties:
all Property

6. Exit the command interpreter:
quit

