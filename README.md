# Car Rental System

A Python-based car rental system designed to manage vehicle reservations, track availability, and handle customer information. This system allows users to rent cars, check available vehicles, and manage rental periods.

## Features

- **Car Listings**: View available cars for rent, including details like car make, model, and rental price.
- **Car Reservation**: Customers can reserve cars for a specified time period.
- **Customer Management**: Manage customer information such as name, contact details, and rental history.
- **Availability Check**: Check if a car is available for the desired rental dates.
- **Rental Duration**: Specify rental start and end dates.
- **Pricing Calculation**: Calculate the total rental price based on the rental period.
- **User Authentication**: Login functionality for system administrators and customers (if applicable).

## Requirements

- Python 3.x
- Tkinter (for GUI)
- SQLite3 (for database management)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/car-rental-system.git
    ```

2. Navigate to the project directory:
    ```bash
    cd car-rental-system
    ```

3. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the main Python script to start the system:
    ```bash
    python main.py
    ```

2. You will be prompted with a GUI interface to interact with the car rental system. You can either:
    - **Browse Available Cars**: View the list of cars available for rent.
    - **Make a Reservation**: Choose a car and reserve it for a given period.
    - **View Rental History**: Check your past reservations and rental details.

## Database Structure

The system uses SQLite3 to store car and customer data. The following tables are used:

- **Cars**: Stores car information (make, model, availability, price).
- **Customers**: Stores customer details (name, contact information).
- **Reservations**: Stores reservation data (customer ID, car ID, rental dates).

## Example

```bash
Available Cars:
1. Tesla Model S - $100/day
2. BMW 3 Series - $80/day
3. Audi A4 - $90/day

Enter your choice: 1
Enter rental start date (YYYY-MM-DD): 2025-03-10
Enter rental end date (YYYY-MM-DD): 2025-03-15

Your reservation has been confirmed!
