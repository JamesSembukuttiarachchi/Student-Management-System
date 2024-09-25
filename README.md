## Project Overview

A web-based student management system built with Flask, SQLite, and Flask-Login for authentication. This application allows users to manage students by adding, editing, and deleting their information. It also includes a user authentication system.

## Features

- User registration and authentication using Flask-Login
- Add, edit, and delete students
- SQLite database integration with Flask-SQLAlchemy
- Securely handles sensitive information like the secret key using environment variables

## Tech Stack

- **Backend**: Flask
- **Database**: SQLite (via SQLAlchemy ORM)
- **Authentication**: Flask-Login
- **Frontend**: HTML, Bootstrap (or any other CSS framework)
  
## Installation and Setup

### Prerequisites

- Python 3.x installed
- `pip` (Python package installer) installed
- `git` installed (for cloning the repository)

### Step-by-Step Guide

1. **Clone the repository:**
   ```bash
   git clone https://github.com/JamesSembukuttiarachchi/student-management-system.git
   cd student-management-system
   cd student_management
   ```
   
### Installation Instructions

1. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

2. **Set up environment variables:**
   Create a `.env` file in the root directory and add your secret key:
   ```bash
   echo "FLASK_SECRET_KEY=your_secret_key" > .env
   ```

3. **Run the application:**
   ```bash
   python3 app.py
   ```
