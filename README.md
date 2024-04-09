# Electronic Programming Quiz System

## Overview

This Java application simulates an electronic quiz system designed to test users on programming concepts. The system supports various types of questions, including multiple-choice and true/false questions. It dynamically fetches questions from a database, presents them to the user, and evaluates the responses to calculate the user's score.

## Features

- **Dynamic Question Loading**: Questions are loaded from a Microsoft Access database, allowing for a flexible and expandable question set.
- **Support for Multiple Question Types**: The system can handle different types of questions, including multiple-choice and true/false, making it versatile.
- **Interactive User Interface**: Users can interact with the quiz through the console, receiving immediate feedback on their answers.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) installed on your machine.
- Microsoft Access or a compatible DBMS installed, with the database file `Question.accdb` set up.

### Database Setup

Ensure your `Question.accdb` database contains a table named `Questions` with the following columns:
- `ID` (AutoIncrement)
- `QText` (Text) - The question text
- `Answer` (Text) - The correct answer
- `Point` (Number) - The point value of the question
- `Type` (Text) - The type of question (e.g., MC for multiple-choice, TF for true/false)

