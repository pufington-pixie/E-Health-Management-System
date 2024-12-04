# E-Health Management System

## Overview

The **E-Health Management System Management System** is a web application designed to help patients and doctors manage appointments efficiently. The system allows patients to book, view, update, or cancel appointments, provide their medical history, and access diagnoses and prescriptions. Doctors can manage their schedules, access patient information, provide diagnoses and prescriptions, and modify patient records. 

### Project Contributors:
- **Kushank Pulipati** (kpuli@uic.edu)
- **Srisatya Kapardi Budi** (sbudi4@uic.edu)
- **Ganesh Katta** (gkatt@uic.edu)

**Course:** CS480  

---

## Data Requirements

### 1. Patients
- Name, email, login credentials, and medical history.
- Multiple appointments allowed.
- Identified by email.

### 2. Doctors
- Name, email, specialization, schedule, and login credentials.
- Multiple appointments allowed.
- Identified by email.

### 3. Appointments
- Unique Appointment ID, Date, Time, Patient, Doctor, and Status (booked, cancelled, completed).
- Ensures no appointment clashes for patients and doctors.
- Cancelled appointments free up slots for others.

### 4. Medical History and Prescriptions
- **Medical History**: Accessible by both patient and the doctor for booked appointments.
- **Prescriptions**: Issued and updated by doctors, viewable by patients.

---

## Application Requirements

Both patients and doctors must log into the system using their email and password. These credentials are created during initial registration.

### 1. Patient Side Features:
1. **User Interface**: Separate login interface for patients.
2. **Appointment Booking**: Patients can book appointments based on doctor availability.
3. **Medical History Input**: Patients can enter their previous medical history.
4. **Manage Appointments**: View, update, or cancel appointments.
5. **View Medical Records**: Patients can view their diagnoses, prescriptions, and medical history (restricted to the doctor they have an appointment with).

### 2. Doctor Side Features:
1. **User Interface**: Separate login interface for doctors.
2. **Schedule Management**: Manages doctor availability to prevent overlapping appointments.
3. **Access Patient Information**: Doctors can view and add to patient history.
4. **Diagnoses and Prescriptions**: Doctors can provide, modify diagnoses and prescriptions.
5. **Appointment Management**: View and manage their appointment schedule to prevent clashes.

---

## Technology Stack

- **Backend**: [Node.JS, Express.JS]
- **Frontend**: [React.JS]
- **Database**: [MYSQL]

---
