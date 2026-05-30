# Transport Tech Solution

A comprehensive bus transportation management system with separate interfaces for Admin, Driver, and Passenger users.

## System Features

### Admin
- Set up and manage buses
- View reports (cars used, bookings per day, daily revenue)
- Add/Delete buses from system
- Approve bookings after payment

### Driver
- Notify passengers at each bus stop
- Real-time notifications to passenger dashboards
- View assigned routes and schedules

### Passenger
- View bus directions and numbers
- Book tickets
- Specify pickup location (bus park or bus stop)
- Select drop-off location
- View passenger count per bus stop
- Real-time seat availability

## Tech Stack
- Frontend: HTML5, CSS3
- Backend: PHP
- Database: MySQL

## Database Setup
1. Create a MySQL database: `transport_tech`
2. Import `database/schema.sql`
3. Update `config/db.php` with your database credentials

## Default Admin Credentials
- **Username**: admin
- **Password**: admin123

## Installation
1. Clone the repository
2. Import the database schema from `database/schema.sql`
3. Configure `config/db.php` with your database credentials
4. Access the system via `index.php`

## Getting Started
See INSTALLATION.md for detailed setup instructions.
