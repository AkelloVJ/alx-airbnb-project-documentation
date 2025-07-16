# Use Case Diagram - Airbnb Clone System

## Overview
This document describes the use case diagram for the Airbnb Clone system, which visualizes the interactions between different actors and the system for key functionalities.

## Use Case Diagram Description

### Actors
1. **Guest** - Users who browse and book properties
2. **Host** - Users who list and manage properties
3. **Admin** - System administrators who manage the platform
4. **Payment System** - External payment gateway integration

### Primary Use Cases

#### For Guests:
- **Register Account**: Create a new user account
- **Login/Logout**: Authenticate with the system
- **Search Properties**: Browse available properties with filters
- **View Property Details**: See comprehensive property information
- **Book Property**: Reserve a property for specific dates
- **Make Payment**: Complete payment for booking
- **Cancel Booking**: Cancel existing reservations
- **Leave Review**: Rate and review stayed properties
- **Send Message**: Communicate with property hosts
- **View Booking History**: Access past and current bookings

#### For Hosts:
- **Register Account**: Create a new host account
- **Login/Logout**: Authenticate with the system
- **Create Property Listing**: Add new properties to the platform
- **Edit Property Details**: Update property information
- **Manage Bookings**: View and respond to booking requests
- **Set Availability**: Configure property availability calendar
- **Set Pricing**: Update property pricing
- **Respond to Messages**: Communicate with potential guests
- **View Reviews**: Read guest reviews for their properties
- **Manage Payments**: Handle payment receipts and refunds

#### For Admins:
- **User Management**: Oversee all user accounts
- **Property Moderation**: Review and approve property listings
- **Content Moderation**: Monitor reviews and messages
- **System Monitoring**: Track platform performance
- **Payment Oversight**: Monitor payment transactions
- **Generate Reports**: Create system analytics reports

#### System Use Cases:
- **Validate User Input**: Ensure data integrity
- **Process Payments**: Handle payment transactions
- **Send Notifications**: Deliver email/SMS notifications
- **Update Availability**: Real-time calendar management
- **Generate Recommendations**: Suggest properties to users

## Use Case Relationships

### Include Relationships:
- "Book Property" includes "Make Payment"
- "Create Property Listing" includes "Validate User Input"
- "Process Payments" includes "Send Notifications"

### Extend Relationships:
- "Search Properties" extends "View Property Details"
- "Manage Bookings" extends "Send Notifications"

## Diagram File
The use case diagram is stored as `use-case-diagram.png` in this directory, created using Draw.io.

## Key Interactions

### Guest Journey:
1. Register → Login → Search Properties → View Details → Book → Pay → Receive Confirmation

### Host Journey:
1. Register → Login → Create Listing → Manage Bookings → Receive Payments → Respond to Reviews

### Admin Journey:
1. Login → Monitor System → Manage Users → Moderate Content → Generate Reports

This use case diagram provides a comprehensive view of all system interactions and serves as a foundation for system design and development. 