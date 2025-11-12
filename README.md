# Mag Data Viewer

A simple web application with user authentication for viewing magnetometer data.

## Features

- User registration and login
- Secure password storage with hashing
- Session-based authentication
- Clean and modern UI

## Setup

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Run the application:
```bash
python app.py
```

3. Open your browser and navigate to `http://localhost:5000`

## Usage

1. **Register**: Create a new account by clicking "Register here" on the login page
2. **Login**: Enter your username and password to access the application
3. **Logout**: Click the logout button to end your session

## Data

The repository contains magnetometer and yaw sensor data in `yaw_and_mag.xlsx`.

## Security

- Passwords are hashed using Werkzeug's security utilities
- Session-based authentication with secure session keys
- SQLite database for user credentials
