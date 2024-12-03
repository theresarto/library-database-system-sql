# Library Database Management System

This project implements a robust library database management system using SQL to handle the borrowing and reservation of resources such as books and devices. The system supports users with functionalities including resource availability tracking, fine management, and loan/reservation processes. Key features include normalization up to 3NF for efficient data management, detailed queries for resource and user statistics, and automated triggers for dynamic fine calculations.

## Features
- Tracks resources (books and devices), their copies, and availability status.
- Automates fine calculations for overdue, lost, or damaged resources.
- Enables comprehensive reporting through advanced SQL queries and views.
- Supports dynamic user management with loan limits and suspension policies.

## Implementation
The database design incorporates:
- **Entities:** Users, Loans, Fines, Reservations, Resources, Books, Devices, and Copies.
- **Relationships:** Ensuring data integrity with primary and foreign keys.
- **Triggers and Functions:** Automating repetitive tasks and maintaining consistency.

## Use Case
Ideal for academic libraries to efficiently manage loans, reservations, and resource usage while maintaining scalability and minimizing redundancy.

---

For more details, refer to the accompanying SQL script and write-up.
