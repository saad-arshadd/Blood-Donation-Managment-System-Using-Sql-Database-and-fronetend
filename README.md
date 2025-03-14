# Blood-Donation-Managment-System-Using-Sql-Database-and-fronetend
The Blood Donation System is a Python-based web application designed to streamline the process of managing blood donations, appointments, and donor information. It incorporates both front-end and back-end components, including a structured database system using SQL.

Key Features
User Authentication:

User login and management through the app.py application file.
Login activities are tracked and logged in login_logs.log.
Donor and Appointment Management:

Database tables are structured to manage donors, hospitals, and appointments.
The appointments table includes attributes such as appointment ID, donor ID, hospital ID, date, time, status, and activity status.
Database Integration:

The SQL schema is defined in the bd (1).sql file.
The database includes tables like appointments with relevant fields to manage appointment scheduling and tracking.
Web Application Framework:

Developed using Python, likely with Flask due to the presence of templates and static folders.
templates include HTML files for user interfaces.
static holds CSS, JavaScript, and media assets.
Logging and Monitoring:

User interactions, especially logins, are recorded for security and monitoring purposes.
Course Relevance: Database Systems
This project aligns with the Database Systems course by emphasizing:

Database Design: Proper normalization, primary and foreign key management, and relationship mapping among entities (like donors, hospitals, and appointments).
SQL Implementation: Use of SQL scripts for creating and managing database structures.
Data Integrity: Use of constraints like NOT NULL and ENUM types to ensure data consistency.
Transaction Management: SQL statements ensuring data accuracy and proper state transitions.
