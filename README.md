# HotelReservation

## Overview
The **HotelReservation** project is a simple Java application that manages hotel room reservations. It allows users to create reservations, view reservation details, and update reservation dates while enforcing business rules.

## Features
- Create a reservation by specifying a room number, check-in date, and check-out date.
- View reservation details, including the room number, check-in date, check-out date, and duration of stay.
- Update reservation dates with validation to ensure future dates and proper check-in/check-out order.
- Handles invalid inputs and exceptions gracefully.

## Project Structure
The project follows a modular structure:
- **`application`**: Contains the main program entry point (`Program.java`).
- **`model.entities`**: Contains the `Reservation` class, which represents a hotel reservation.
- **`model.exceptions`**: Contains the `DomainException` class for handling domain-specific errors.

## Business Rules
1. Reservation dates must be in the future.
2. The check-out date must be after the check-in date.
3. Updates to reservation dates must also follow the above rules.

## How to Run
1. Clone or download the project.
2. Open the project in an IDE like Eclipse or Visual Studio Code.
3. Ensure you have Java 21 installed and configured.
4. Run the `Program.java` file located in the `src/application` directory.

## Example Usage
1. Enter the room number and reservation dates when prompted.
2. View the reservation details.
3. Update the reservation dates if needed.

## Exception Handling
- **`DomainException`**: Thrown when business rules are violated (e.g., invalid dates).
- **`ParseException`**: Caught when the date format is invalid.
- **`RuntimeException`**: Catches unexpected errors.

## Dependencies
- Java 21
- No external libraries are required.
# HotelReservation
# Bank
