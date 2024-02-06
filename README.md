# Express Authentication Project

This project demonstrates user authentication using Express.js, Passport.js, and PostgreSQL.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- User registration with password hashing using bcrypt
- User authentication with Passport.js
- Session management with Express sessions
- PostgreSQL database for storing user information

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js installed
- PostgreSQL installed and running
- Clone this repository

## Installation

1. Install dependencies:

   ```bash
   npm install
Set up your PostgreSQL database:

Create a database named secrets.
Adjust database connection details in the code if necessary.
Run the application:

bash
Copy code
npm start
Usage
Open your web browser and navigate to http://localhost:3000.
Explore the different routes:
/: Home page
/login: Login page
/register: Registration page
/secrets: Secrets page (requires authentication)
/logout: Log out and redirect to the home page
