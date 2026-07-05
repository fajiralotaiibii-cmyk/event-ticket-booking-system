# event-ticket-booking-system
A robust desktop-based event management and ticketing platform designed to streamline event planning, user management, and ticket booking. This project follows strict Object-Oriented Programming (OOP) principles and implements a clean MVC architecture.

🚀 Key Features

Role-Based Access Control (RBAC): Distinct dashboards for Administrators, Event Managers, and Customers.

Event Lifecycle Management: Create, update, and cancel events with real-time seat tracking.

Secure Booking System: Transaction-safe booking process with automatic seat allocation and cancellation logic.

System Analytics: Built-in reporting for Administrators to track total revenue, active bookings, and system growth.

Input Validation: Robust error handling and validation for user registration and event creation.

🛠 Technical Stack

Core Language: Java

UI Framework: JavaFX / FXML

Database: Oracle Database (SQL)

Design Patterns: MVC (Model-View-Controller), Singleton (for Database & Session), Composition.

📊 System Architecture

Class Diagram

The system relies on strong OOP principles, featuring an abstract User class inherited by Admin, Manager, and Customer classes. The Event class implements the Bookable interface and utilizes Composition to manage ticket inventory.

GUI Hierarchy

The system provides a seamless navigation flow starting from a secure login screen, branching into role-specific dashboards with intuitive data tables to manage entities.

📸 Project Snapshots
