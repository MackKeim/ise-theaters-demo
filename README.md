ISE Theaters Demo

A browser-based cinema ticket booking and reservation management prototype.

ISE Theaters Demo is a university software engineering project designed to demonstrate an interactive movie ticket booking experience. Users can select seats, manage reservations, and generate tickets through a web-based interface.

Features

• Movie ticket booking with interactive seat selection

• Reservation management and seat modification

• Ability to add additional seats to existing reservations

• Seat availability tracking to prevent duplicate bookings within the browser

• Downloadable PDF tickets containing QR codes

• Indoor navigation concept for the cinema environment

• Demonstration checkout and payment form

Technologies

HTML, CSS, JavaScript, browser localStorage, jsPDF, QRious, and GitHub Pages

Running Locally

1. Clone the repository:

git clone https://github.com/MackKeim/ise-theaters-demo.git

cd ise-theaters-demo

2. Start a local web server:

python -m http.server 8000

3. Open http://localhost:8000 in your browser and navigate to the booking page.

How It Works

The application uses browser localStorage to maintain demonstration reservations and seat availability between page visits.

Users can select available seats, create or modify reservations, and generate downloadable tickets with QR codes.

The application operates entirely in the browser without a backend server or database.

Project Background

ISE Theaters Demo was developed as an educational software engineering prototype to explore frontend development, interface design, booking workflows, and reservation management.

The project is intended for demonstration purposes and is not a commercial ticketing application.

Important Notes

The payment interface does not process real transactions. Users should not enter actual payment information.

Reservations are stored locally in the browser and are not shared across devices or users.
