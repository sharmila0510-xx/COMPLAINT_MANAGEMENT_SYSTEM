# Cloud-Based Campus Complaint Management System

## Overview

The Cloud-Based Campus Complaint Management System is a web-based application designed to simplify the process of submitting, tracking and managing student complaints within a college campus.

Students can submit complaints related to different campus facilities and services. Administrators can view complaints, update their status and provide remarks.

## Features

* Student complaint submission
* Automatic complaint ID generation
* Complaint tracking
* Complaint status management
* Priority classification
* Complaint category selection
* Admin login
* Admin dashboard
* Search and filter complaints
* Admin remarks
* Complaint statistics
* SQLite database
* Flask backend
* HTML, CSS and JavaScript frontend
* Cloud-accessible prototype using ngrok

## Technology Stack

### Frontend

* HTML
* CSS
* JavaScript
* Chart.js

### Backend

* Python
* Flask

### Database

* SQLite

### Cloud Access

* Google Colab
* ngrok

## Complaint Workflow

```text
Student
   |
   v
Submit Complaint
   |
   v
Complaint ID Generated
   |
   v
Database
   |
   v
Admin Dashboard
   |
   +----> Submitted
   |
   +----> In Progress
   |
   +----> Resolved
   |
   +----> Rejected
   |
   v
Student Tracks Complaint
```

## Complaint Categories

The system can manage complaints related to:

* Infrastructure
* Hostel
* Transport
* Canteen
* Internet
* Laboratory
* Classroom
* Cleanliness
* Other Campus Services

## Complaint Priority

* Low
* Medium
* High
* Critical

## Complaint Status

* Submitted
* In Progress
* Resolved
* Rejected

## Admin Demo Login

For demonstration purposes:

```text
Username: admin
Password: admin123
```

> These credentials are intended only for the college project demonstration. Production applications should use secure authentication and password hashing.

## Project Structure

```text
campus_complaint_system/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── templates/
│   ├── index.html
│   ├── submit.html
│   ├── track.html
│   ├── login.html
│   └── admin.html
│
└── static/
    ├── style.css
    └── script.js
```

## How to Run

### 1. Install dependencies

```bash
pip install -r requirements.txt
```

### 2. Start the Flask application

```bash
python app.py
```

The application will run on:

```text
http://127.0.0.1:5000
```

### 3. Cloud Access

For demonstration through Google Colab, the Flask application can be exposed using ngrok.

The ngrok authentication token should be configured privately and should never be committed to GitHub.

## Database

The application uses SQLite to store complaint information.

Each complaint contains information such as:

* Complaint ID
* Student Name
* Student Email
* Department
* Year
* Category
* Priority
* Location
* Description
* Status
* Admin Remark
* Created Date
* Updated Date

## Future Enhancements

* Secure user authentication
* Email notifications
* Student and administrator role management
* Cloud-hosted database
* Complaint image/file attachments
* Mobile application
* Advanced analytics
* Automatic complaint categorization
* Deployment on a permanent cloud platform

## Project Purpose

This project demonstrates how a web-based complaint management application can be developed using Flask, SQLite, HTML, CSS and JavaScript and accessed through a cloud-based development environment.

## Author

D SHARMILA
