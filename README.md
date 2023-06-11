# Bus Booking System
The Bus Booking System is a Java-based application that facilitates the booking of bus seats for passengers. The system provides an easy-to-use graphical user interface (GUI) where users can view available seats, select a seat, and book it for a specific date. It also allows users to search for bus seat availability based on the desired date.

## Key Features
- Seat Availability: Users can view the availability of bus seats for a selected date.
- Booking: Users can book available seats by providing their name, mobile number, and preferred date.
- Seat Status: The system updates the seat status to "Booked" once a seat is successfully booked.
- Data Persistence: The system stores booking information in a database for future reference.

## Technologies Used
Java: The application is developed using Java programming language.
Swing: The GUI components are built using Swing, a Java GUI toolkit.
MySQL: The MySQL database is used to store and retrieve booking information.

## How to use
1. Launch the application.
2. Select a date to check seat availability.
3. Choose an available seat from the displayed options.
4. Enter your name, mobile number, and desired date for booking.
5. Click the "Add" button to confirm the booking.
6. The system will display a confirmation message and update the seat status to "Booked".
7. Reload the data to view the updated seat availability.
8. Clear the input fields for the next booking.

## Note
- Make sure to set up the MySQL database connection before running the application. Update the database credentials in the code if required.
- The application assumes a single bus with a fixed number of seats. Modify the code for multiple buses or dynamic seat allocation as per your requirements.
