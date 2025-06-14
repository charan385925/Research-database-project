# 🏨 Multi-city Hotel Chain Management System - Database Project

![image](https://github.com/user-attachments/assets/57ceb61d-faf9-44ad-be78-194e2d57d384)


## 📌 Project Description

This project implements a relational database system for managing operations across a multi-city hotel chain. It captures various entities such as hotels, rooms, guests, bookings, employees, and managers, enabling smooth tracking and management of bookings, feedback, and operations.

## 🗃️ ER Design Overview

The system is built using a normalized Entity-Relationship schema with the following key entities:

- **Hotel**: Identified by `hotel_code`, contains details such as name, city, and star rating.
- **Room**: Each room belongs to a hotel and includes information like room number, type, pricing, and availability.
- **Guest**: Tracks guest information, including loyalty level, booking history, and feedback.
- **Booking**: Captures booking details including dates, total bill, and the associated room and guest.
- **Feedback**: Allows guests to provide ratings and comments for individual bookings.
- **Employee**: Represents hotel staff, including their role, hotel assignment, and shift timing.
- **HotelManager**: Maps each hotel to its manager, who is also listed as an employee.

## 🛠️ Tables and Sample SQL Inserts

The following tables are implemented:

- `Hotel`
- `Room`
- `Guest`
- `Booking`
- `Feedback`
- `Employee`
- `HotelManager`

Sample SQL INSERT statements are included for:

- Adding hotels, rooms, guests
- Making bookings
- Capturing feedback
- Adding employees and assigning hotel managers

## 🧠 Key Features

- Guests can book rooms in any hotel, and their loyalty level evolves with booking history and feedback.
- Rooms are uniquely identified and linked to a hotel, with real-time availability tracking.
- Employees are assigned to hotels and can work in various roles and shifts.
- Feedback for each booking influences guest loyalty and service improvement.
- Manager assignment is handled through a separate `HotelManager` mapping.

## ✅ Technologies Used

- SQL (DDL + DML)
- ER Modeling
- Relational Database Design Principles

## 📂 Files Included

- SQL Table Structures
- Sample Data Insertion Scripts
- ER Diagram (conceptual)
![project4 img](https://github.com/user-attachments/assets/33c36e47-c112-42ba-90b2-6018d9208ae2)

---

> 🎓 This project was built as part
>
> 
