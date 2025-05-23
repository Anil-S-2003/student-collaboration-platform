# Student Collaboration Online & Code Sharing Platform

A full-stack web application that allows student teams to upload buggy Python code, collaborate in real time, debug together, and share fixed versions. Built to encourage teamwork, coding practice, and interactive learning among students.

---

##  Features

-  User login & signup system (session-based authentication)
-  Upload buggy `.py` files
-  Group-based discussion and code comments
-  WhatsApp-style chat layout for shared code and feedback
-  Built-in code editor with copy/download options
-  Admin dashboard for managing uploaded code and users
-  Downloadable fixed code after collaborative editing
-  MongoDB backend to track users and submissions

---

## Tech Stack

- Frontend: HTML, CSS , JavaScript
- Backend: Python with Flask
- Database: MongoDB (via `pymongo`)
- File Storage: Server-side using Flask `uploads/` folder
- UI Design: Inspired by WhatsApp chat interface
- IDE Support: Embedded syntax-highlighted editor

---

##  Installation & Running Locally

### Step 1: Clone the Repository
git clone https://github.com/yourusername/student-collaboration-platform.git
cd student-collaboration-platform

## Step 2: Set Up Virtual Environment (Optional but recommended)
python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate

##Step 3: Install Dependencies
pip install -r requirements.txt

##Step 4: Ensure MongoDB is Running
Make sure MongoDB service is running on your local machine
(default URI: mongodb://localhost:27017/)

##Step 5: Start the Flask Application
python app.py
##Step 6: Open in Browser
http://localhost:5000
