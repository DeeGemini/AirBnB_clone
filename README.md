AirBnB Clone-Console Project

1. Description of the Project

This Airbnb Clone Console project aims to replicate the basic functionality of Airbnb's platform, allowing users to manage properties, bookings, and more through a command-line interface.

2. Command Interpreter

How to Start It

- To start the command interpreter, simply run the following command:
	bash
	python main.py

How to Use It

- Once the interpreter is running, you can use the following commands:

>>> create <entity>: Create a new instance of the specified entity.
>>> show <entity> <id>: Display details of the specified entity with the given ID.
>>> update <entity> <id> <attribute> "<value>": Update the attribute of the specified entity with the given value.
>>> destroy <entity> <id>: Delete the specified entity with the given ID.
>>> all <entity>: Display all instances of the specified entity.
>>> quit: Exit the command interpreter.

Examples
- Creating a new property:
	bash
	create Place
- Showing details of a booking:
	bash
	show Booking 123
- Updating property information:
	bash
	update Place 456 description "Cozy cabin in the woods"
- Deleting a user:
	bash
	destroy User 789
- Listing all available properties:
	bash
	all Place

