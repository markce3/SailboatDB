# Comprehensive Boat Charter Management System

## Project Overview
The Boat Charter Management System is a relational database project designed to manage boat charters, customer details, boat maintenance, equipment, supplies, and crew management. This system allows boat owners to manage their boats, customers to book charters, and staff to track maintenance and supplies associated with each charter.

The database was designed using SQL and follows a structured schema with multiple related tables, such as Owner, Boat, Customer, Charter, Itinerary, Equipment, Maintenance, and more. Referential integrity is maintained using foreign key relationships between tables.

## Key Features
- **Boat Management:** Maintain records for boat owners and their boats, including boat size, length, and year built.
- **Charter Management:** Track customer bookings, including itinerary details, charter start and return dates, and charter reviews.
- **Crew Management:** Assign crew members to charters with detailed records of hours worked.
- **Maintenance Tracking:** Record boat maintenance activities, repair histories, and repair facility details.
- **Supply Tracking:** Manage supplies required for charters, such as navigation books, tide tables, and safety equipment.
- **Reviews:** Allow customers to leave ratings and reviews for their charter experiences.


## Database Schema
This project includes the following tables:

- **Owner:** Stores information about boat owners.
- **Boat:** Contains details about boats, including boat size, length, and year built.
- **Equipment:** Information about equipment used on boats.
- **Customer:** Details about customers booking charters.
- **Itinerary:** Stores start and end destinations, durations, and distances for each trip.
- **Charter:** Links boats to customers and itineraries, with dates for chartering.
- **Crew:** Information about crew members working on charters.
- **Maintenance:** Tracks maintenance activities performed on boats.
- **RepairHistory:** Records of repairs done on boats.
- **RepairFacility:** Information about the facilities performing boat repairs.
- **Review:** Customers can leave ratings and feedback on their charter experiences.
- **Supply:** Lists supplies needed for charters.
- **BoatEquipment:** Equipment used on boats.
- **SupplyCharter:** Links supplies to charters.
- **CrewHire:** Crew hired for specific charters.

## Technologies Used
- **SQL:** The database schema was designed and implemented using SQL.
- **Oracle:** The project is built using Oracle Database, with tables created and managed using SQL scripts.

## Contributions
Contributions to this project are welcome! Whether you want to fix bugs, add new features, or improve documentation, your contributions will be appreciated.
