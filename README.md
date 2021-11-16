# ToDo-application
1. Project Overview


A command line interface based application to manage TO-DO list (for single user)


2. Software Requirements 
ID
Requirements
2.1
Software Requirement
python (3.*)
MySQL database 

Recommended python libraries :   
Argparse module 
Click 
MySQL database 
python-mysql module
Re(Regular Expression) module
Datetime module

3. Technical Requirements

 Functional Requirements


User can use command line options to utilise it’s features
eg. 
>> python todo.py --list
>> python todo.py --list incomplete
>> python todo.py --list complete
>> python todo.py --create <title>
>> python todo.py --edit-title <task-id> <updated-title>
>> python todo.py --edit-status <task-id> <updated-status> 
>> python todo.py --delete <task-id>
Fields for task - id(auto increment), title, created_at, completed_at, status(default: incomplete) 
Use MySQL database to store tasks data
Feature - Create new task (Disallow task creation with duplicate “title”)
Feature - Edit existing task (update title, mark as complete)
Feature - List all tasks with date as optional filter
Feature - Delete task(s)
Feature - Text search by task title





