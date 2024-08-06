# Fizzlet: Flashcard and Quiz App

Fizzlet is a web application designed for creating, organizing, and taking quizzes based on flashcards.

## Features
- User Registration and Login
- Create, Edit, and Delete Flashcards
- Organize Flashcards into Sets
- Take Multiple Choice Quizzes

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/fizzlet.git

Set up XAMPP and start Apache and MySQL servers.

Import the database schema into MySQL:

sh
mysql -u root -p fizzlet < fizzlet.sql

Update the config.php file with your database credentials.

Place the project folder in the htdocs directory of XAMPP.

Database
Fizzlet uses MariaDB, which is included with XAMPP, for storing user data, flashcards, and quiz results.

Database Schema
The database fizzlet contains the following tables:

Users
Column	Type
userid	INT
username	VARCHAR(255)
password	VARCHAR(255)
setsid	INT
Sets
Column	Type
setid	INT
title	VARCHAR(255)
flashcardids	INT
Flashcards
Column	Type
flashcardid	INT
question	TEXT
answer	TEXT
setid	INT
Read the Software Report
For detailed information about the project, its architecture, and its implementation, please refer to the software report: https://docs.google.com/document/d/1Bcq7Csh7QgEM-9xi8aEXr08T0ffLjSpT4E99lINGrsE/edit?usp=sharing
