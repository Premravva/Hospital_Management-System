# Appointment Booking System

## Overview
This project is an appointment booking system where users (patients) can schedule appointments with doctors based on their availability and specialization. The system allows managing, creating, and updating records for both patients and doctors. 
It streamlines the process of booking appointments and ensures the earliest available time slots are offered.

## Features
- Create, Update, Delete, and Display** records for patients and doctors.
- Automated Appointment Matching** based on doctor availability and specialization.
- Email and Text Confirmation** for both doctors and patients regarding appointment details.

## Technologies
- Back-end**: C#, MySQL (for databases), REST API
- Front-end**: Blazor for user interface development

## Data Structure
- User Data:
  - UserID
  - Name
  - Password
  - Reason for Admission
  - Address
  - Phone Number
  - Email
  - Appointment Details
- Doctor Data:
  - DoctorID
  - Name
  - Specialization
  - Phone Number
  - Availability
  - Email
  - Appointment Details
  - Password

## Appointment Management
- The system manages and maps patient appointment requests to available doctors.
- The system checks for the earliest available time for each patient.
- Both the doctor and patient receive email and SMS notifications with appointment details and timings.

## User Stories and Features
1. Create Appointment**: Users can create new appointments.
2. Update Appointment**: Users can update existing appointment details.
3. Add New Appointment**: Admins can add new appointments manually.
4. View Patient Appointments**: Patients can view all their appointments.
5. View Doctor Appointments**: Doctors can view all appointments associated with their ID.
6. Filter Appointments by Date**: Admins can filter appointment details for a specific date.
7. Filter Appointments between Dates**: Admins can view appointment details between two dates.
8. Total Appointment Count**: Admins can fetch the total number of appointments till date.
9. Delete Appointment**: Users can delete appointments by ID.
10. Fetch Appointment by ID**: Users can fetch details for a specific appointment ID.
11. View All Appointments to Date**: Users can fetch all appointment details till date.

## How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/appointment-booking-system.git
    ```
2. Install the required dependencies.
3. Set up the MySQL database with the provided scripts.
4. Run the application via your preferred IDE or terminal.

## Future Enhancements
- Add more advanced features such as appointment reminders and cancellations.
- Implement a recommendation system for matching patients with doctors based on previous history.
- Add analytics to track appointment trends and doctor availability over time.
