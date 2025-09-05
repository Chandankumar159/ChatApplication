# Chatroom Application

A real-time chatroom app built with Flask, Flask-SocketIO, and Flask-SQLAlchemy.
Users can sign up, log in, create/join chat rooms, send messages, share files, and see real-time user counts.

# Features

• User signup & login

• Real-time messaging with Socket.IO

• Create or join multiple chat rooms

• File sharing inside rooms

• Live user count per room

• Supports SQLite (default) & MySQL with minor changes

# Setup Instructions
• Prerequisites

• Python 3.7+

# Install Dependencies
pip install -r requirements.txt

# Set up the Database
python -c "from app import create_tables; create_tables()"

# Run the Application
python app.py


Open in browser : http://localhost:5000

# Technologies Used

Backend: Flask, Flask-SQLAlchemy, Flask-SocketIO

Frontend: HTML, CSS, JavaScript

Database: SQLite (default) | MySQL (optional)

SocketIO: Real-time bi-directional communication

# 📂 Folder Structure
flask-chatroom/
├── app.py             # Main application file
├── requirements.txt   # Python dependencies
├── templates/         # HTML templates
├── static/            # Static files (CSS, JS, Images)
├── uploads/           # Directory for file uploads
├── chatroom.db        # SQLite database (auto-created)
└── README.md          # Documentation

# ScreenShots:
<img width="1920" height="1020" alt="Screenshot 2025-09-05 234508" src="https://github.com/user-attachments/assets/a3e5a454-ca09-4301-b0cd-8b4cbb032b8f" />
<img width="1920" height="1020" alt="Screenshot 2025-09-05 234549" src="https://github.com/user-attachments/assets/9a1c889e-a1dc-4390-b197-a3c2ecb12939" />
<img width="1920" height="1020" alt="Screenshot 2025-09-05 234615" src="https://github.com/user-attachments/assets/b795f393-3994-4afc-b6bb-fca6eabb95cd" />


