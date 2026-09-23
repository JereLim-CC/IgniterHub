# Tasks for Today Management System

## Description

The Tasks for Today Management System is a CodeIgniter and MySQL-based task management application developed for IT0049 - Web System Technologies.

The system displays tasks based on their assigned date and provides separate pages for today's tasks, the complete task list, a user profile, and developer information.

## Features

- Displays tasks scheduled for today
- Displays the complete task list
- Displays a demo user profile
- Provides a static About page
- Uses MySQL for data storage
- Uses CodeIgniter MVC structure

## Pages

- `/` - Welcome page showing today's tasks
- `/tasks` - Complete task list
- `/profile` - Demo user profile
- `/about` - About/developer page

## Technologies Used

- PHP
- CodeIgniter 4
- MySQL
- HTML

## Database

Database name:

`tasks_today_db`

The database export is included in this repository:

`tasks_today_db(TSA1).sql`

The database contains:

- `tasks` table
- `users` table

## Setup

1. Install XAMPP with PHP and MySQL.
2. Place the project inside the XAMPP `htdocs` directory.
3. Create the `tasks_today_db` database in MySQL.
4. Import `TSA1_tasks_today_db.sql`.
5. Configure the local database settings in the `.env` file.
6. Run the CodeIgniter application.

## Developer

Developed by Jeremiah Lim

IT0049 - Web System Technologies
