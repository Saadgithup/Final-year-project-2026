# ODARS - Online Doctor Appointment Reservation System

A fully functional web-based doctor appointment booking system built according to the SRS and SDD specifications.

## Features

### User Module
- **Login/Registration** - Patients and doctors can register and log in
- **Home Page** - Search doctors, browse departments, featured doctors
- **Doctors** - Search and filter by name/department, view doctor profiles
- **Departments** - Browse departments and associated doctors/hospitals
- **Book Appointment** - Select hospital, department, doctor, date and time
- **Contact** - Submit enquiries
- **Profile** - Edit profile, view/cancel appointments, doctors can add availability

### Admin Module
- **Dashboard** - Overview of patients, doctors, appointments, enquiries
- **Patients** - Add, edit, delete patients
- **Doctors** - Add, edit, delete doctors
- **Departments** - Add, edit, delete departments
- **Hospitals** - Add, edit, delete hospitals
- **Appointments** - View and delete appointments
- **Enquiries** - View and reply to patient enquiries

## Setup

1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

2. Run the application:
   ```
   python run.py
   ```

3. Open http://127.0.0.1:5000 in your browser

## Default Credentials

| Role   | Email              | Password   |
|--------|--------------------|------------|
| Admin  | admin@odars.com    | admin123   |
| Doctor | dr.smith@hospital.com | doctor123 |
| Patient| patient@test.com   | patient123 |

## Tech Stack

- **Backend**: Flask, SQLAlchemy, Flask-Login
- **Database**: SQLite (odars.db)
- **Frontend**: Bootstrap 5, Jinja2 templates
