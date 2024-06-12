# CSE2100
---

# Students' Hall Management System

This program was developed as part of the **CSE 21000 - Software Development Project I** course of my university. The **Students' Hall Management System** is designed to streamline the management of student affairs within a university hall. 

## Overview

The system features a login interface that grants access exclusively to the provost. Upon logging in, the provost can manage various aspects of the hall, including room allocation, student information, and payment tracking.

## Key Features

- **Login System**: Only the provost can log in to manage the system.
- **Room Management**:
  - Add new rooms and activate/deactivate them.
  - Allocate active and unbooked rooms to students.
  - Display room availability status.
  - Prevent room allocation when all rooms are booked or inactive.
- **Student Information Management**:
  - Update student data (excluding Roll No, which is the primary key).
  - View consolidated data of all living students.
- **Payment Tracking**:
  - Record monthly payments for each student.
  - Prevent duplicate payment entries for the same month.

## Detailed Functionality

1. **Login Page**:
   - The login page is the first interface displayed.
   - Only the provost can log in and manage the system.

2. **Room Allocation**:
   - The provost can add new rooms and activate or deactivate them.
   - When a new student arrives, the system books an available room.
   - If no rooms are available, the system notifies that all rooms are booked.

3. **Student Data Management**:
   - Student data, except for the Roll No, can be updated through the system.
   - The Roll No is treated as the primary key and remains unchanged.

4. **Payment Management**:
   - For each month, the provost can upload the payment date for a specific student’s Roll No.
   - If a payment for a specific month is already recorded, additional payments for the month cannot be recorded.

5. **Data Overview**:
   - The system provides a consolidated view of all the data of the living students.

## Technologies Used

- **Java**: For backend development to ensure robust functionality.
- **SQL**: For efficient database management and storage.

## Usage

1. Launch the application.
2. Log in as the provost(if you are) using the credentials provided.
3. Use the dashboard to manage rooms, student information, and payments.
