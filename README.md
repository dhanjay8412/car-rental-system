# car-rental-system
🚗 Project Overview
The Car Rental System is a web-based application that allows users to:

Browse available cars with pricing and availability status

Register and login to their accounts

Select a car and specify rental duration

Receive a booking confirmation with total price calculation

View their booking details

This project simulates a real-world car rental service with client-side JavaScript handling all business logic, data persistence via localStorage, and responsive design principles.

✨ Features
User Authentication
Registration - Create a new account with name, email, and password

Login - Secure access to existing accounts

Session Management - User data stored in browser's localStorage

Car Management
Car Listing - View all available cars with images, prices, and availability

Dynamic Availability - Cars marked as available/unavailable

Car Selection - Choose a car to rent

Booking System
Rental Duration - Specify number of rental days (minimum 1 day)

Price Calculation - Automatic total price calculation based on daily rate × days

Booking Confirmation - Detailed summary of the rental

📁 Project Structure
text
car-rental/
│
├── index.html              # Homepage / Landing page
├── car-listing.html        # Available cars listing page
├── booking.html            # Booking form page
├── bill.html               # Booking confirmation page
├── login.html              # User login page
├── register.html           # User registration page
├── README.md               # Project documentation
│
├── css/
│   ├── style.css           # Main homepage styles
│   ├── listing.css         # Car listing page styles
│   ├── booking.css         # Booking form styles
│   ├── bill.css            # Bill/confirmation page styles
│   ├── login.css           # Login page styles
│   └── register.css        # Registration page styles
│
├── js/
│   ├── main.js             # Car listing & booking logic
│   ├── booking.js          # Booking form & price calculation
│   ├── bill.js             # Bill display logic
│   └── auth.js             # Authentication logic (login/register)
│
└── images/
    ├── car1.jpg            # Car model 1 image
    ├── car2.jpg            # Car model 2 image
    └── car3.jpg            # Car model 3 image

    💻 Technologies Used
Technology	Purpose
HTML5	Structure and content of web pages
CSS3	Styling, layout, and responsive design
JavaScript (ES6)	Dynamic functionality, DOM manipulation
localStorage	Client-side data persistence for users and bookings
