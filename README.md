# Blood Donation Management System

## Overview

The **Blood Donation Management System** is a full-stack web application designed to streamline the process of blood donation, donor registration, and blood camp management. The platform allows donors to register, manage their profiles, and participate in donation camps, while administrators can manage donors and monitor the system through an administrative dashboard.

The project demonstrates the implementation of a structured web application using a Python backend and a web-based frontend with database integration.

---

## Key Features

### Donor Module

* Donor registration with personal and blood group information
* Secure login system
* Donor profile management
* Dashboard for donors to view and update details
* Access to available blood donation camps

### Admin Module

* Admin authentication
* Admin dashboard for monitoring registered donors
* Ability to view and manage donor data
* Management of blood donation camps

### System Capabilities

* Organized donor database
* Structured UI for easy navigation
* Integration with a backend API
* Database-driven operations for storing and retrieving donor data

---

## Technology Stack

### Frontend

* HTML5
* CSS3
* JavaScript

### Backend

* Python
* Flask Framework

### Database

* MySQL

### Development Tools

* Python
* Git & GitHub
* Web Browser

---

## Project Structure

```
Blood-Donation-Website
│
├── backend
│   ├── app.py
│   └── requirements.txt
│
├── database
│   └── blood_donation.sql
│
├── frontend
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── donor_dashboard.html
│   ├── donor_profile.html
│   ├── admin_login.html
│   ├── admin_dashboard.html
│   ├── camps.html
│   │
│   ├── css
│   │   └── style.css
│   │
│   └── js
│       └── script.js
│
└── README.md
```

---

## Installation and Setup

### 1. Clone the Repository

```
git clone https://github.com/yourusername/blood-donation-website.git
cd blood-donation-website
```

### 2. Install Python Dependencies

```
pip install -r backend/requirements.txt
```

### 3. Setup Database

1. Open MySQL or phpMyAdmin
2. Create a new database
3. Import the file:

```
database/blood_donation.sql
```

### 4. Configure Database in Backend

Update the database configuration in:

```
backend/app.py
```

Example configuration:

```
host = "localhost"
user = "root"
password = "yourpassword"
database = "blood_donation"
```

### 5. Run the Backend Server

```
python backend/app.py
```

The backend server will start locally.

---

## Application Workflow

1. Users access the website through the homepage.
2. New donors register using the registration form.
3. Registered users log in and manage their profiles.
4. Admin logs in through the admin panel to monitor system activity.
5. Database stores and retrieves donor and camp information.

---

## Future Improvements

* Blood request system
* Real-time donor search by location
* Email and SMS notifications
* Mobile responsive UI improvements
* API integration for hospitals and blood banks
* Role-based authentication system

---

## Learning Outcomes

This project demonstrates:

* Full-stack web application development
* REST-based backend design using Flask
* Database integration with MySQL
* User authentication implementation
* Structuring scalable web projects

---

## Author

Manmath Arvind Bharde 
Computer Engineering Student

---

## License

This project is created for educational and portfolio purposes.
