# School Event Management System

## Project Overview
This application manages school events, room and field reservations, and user management using Java and JDBC.

## Features
- User Management
  - Add users (students and professors)
  - View all users
  - Delete users

- Event Management
  - Add events
  - Update events
  - Delete events

- Reservation Management
  - Check availability of rooms/fields
  - Make reservations
  - Supports reservation for both rooms and fields

## Technical Requirements
- MySQL Database
- JDBC Driver
- Java 8+

## Setup Instructions
1. Create the database using the provided SQL script
2. Update database connection details in the code
   - DB_URL
   - USER
   - PASS
3. Compile and run the EventManagementSystem class

## Database Schema
- users: Stores user information
- events: Stores event details
- salles: Stores room information
- terrains: Stores field information
- reservations: Tracks event reservations

## Dependencies
- MySQL Connector/J
