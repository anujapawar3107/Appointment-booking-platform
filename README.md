# Dentist Appointment Booking Platform

A full-stack appointment booking platform for a dentist. Patients can select appointment types, choose dates, view available time slots, and book appointments. The dentist can also view and cancel appointments.

---

## Table of Contents

- [Project Overview](#project-overview)  
- [Features](#features)  
- [Tech Stack](#tech-stack)  
- [Folder Structure](#folder-structure)  
- [Setup & Installation](#setup--installation)  
- [Usage](#usage)  
- [API Endpoints](#api-endpoints)  
- [Optional Enhancements](#optional-enhancements)  

---

## Project Overview

This platform allows patients to book appointments easily:

- Select appointment type:
  - Regular Check-up (30 min)  
  - Specific Treatment (60 min)  
  - Operation (120 min)  
- Pick a date using a calendar.  
- View available time slots dynamically based on:
  - Appointment duration  
  - Already booked slots  
  - Lunch break (optional)  
- Enter name and contact to confirm booking.  
- Dentist can view all appointments and cancel if necessary.

---

## Features

**Frontend (React)**

- Clean homepage with appointment booking UI.  
- Dynamic slot availability.  
- Confirmation message after booking.  
- Dentist view for all appointments.  

**Backend (FastAPI)**

- REST API with endpoints to:
  - Fetch booked appointments  
  - Get available slots  
  - Book new appointments  
  - Cancel appointments  
- Stores appointment data in SQLite database.  

---

## Tech Stack

- Frontend: React.js  
- Backend: FastAPI (Python)  
- Database: SQLite  
- HTTP Client: Fetch API  
- Package Manager: npm & pip  

---

## Folder Structure

