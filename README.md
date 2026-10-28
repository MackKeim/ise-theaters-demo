ISE Theaters Demo

A browser-based cinema ticket booking and reservation management prototype.

ISE Theaters Demo is an educational software engineering project designed to demonstrate a movie ticket booking experience through an interactive web interface.

The application explores seat selection, reservation management, ticket generation, and related cinema services.

Features

- Movie and showtime selection
- Interactive cinema seating interface
- Seat availability tracking using browser storage
- Reservation creation and lookup
- Reservation cancellation
- Downloadable PDF tickets with QR codes
- Indoor navigation concept for the cinema environment
- Demonstration checkout and payment form

Technologies

- HTML, CSS, and JavaScript
- Browser localStorage for reservation information
- jsPDF for generating PDF tickets
- QRious for generating QR codes
- Client-side web development

Running Locally

1. Clone the repository:

git clone https://github.com/MackKeim/ise-theaters-demo.git

2. Open the project directory:

cd ise-theaters-demo

3. Start a local web server:

python -m http.server 8000

4. Open http://localhost:8000 in your browser and navigate to the application's booking interface.

Some external libraries may require an internet connection.

How It Works

Users can select a movie session, view seating availability, and choose seats for a reservation.

Reservation information is stored locally in the browser, allowing the application to demonstrate booking management without requiring a backend database.

The application can generate downloadable PDF tickets containing QR codes.

The project also includes an indoor navigation concept demonstrating how visitors could navigate a cinema environment.

Project Background

ISE Theaters Demo was developed as an educational software engineering project focused on frontend development, user interface design, and interactive reservation workflows.

The project demonstrates the implementation of common ticket booking features using client-side web technologies.

Important Notes

This application is a prototype intended for demonstration and educational purposes.

- The payment form does not process real transactions
- Users should not enter real payment information
- Reservations are stored locally and are not shared between browsers or devices
- Browser storage is not a secure or production-ready reservation database
- The indoor navigation functionality is a demonstration concept rather than a complete navigation system

Project Status

ISE Theaters Demo is a university prototype and is not intended for commercial ticket sales or real-world reservation management.
