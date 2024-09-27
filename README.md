# Event Booking College

A web application for booking events, built with Node.js, EJS, MongoDB, and integrated with Razorpay for payment processing.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- User registration and login
- Event listing and search functionality
- Booking events with secure payments
- Admin panel for event management
- Responsive design for mobile and desktop

## Technologies Used

- **Node.js**: Backend JavaScript runtime
- **Express**: Web framework for Node.js
- **EJS**: Templating engine for rendering HTML
- **MongoDB**: NoSQL database for data storage
- **Razorpay**: Payment gateway for secure transactions
- **Bootstrap**: Front-end framework for responsive design

## Installation

### Prerequisites

- Node.js (v12 or higher)
- MongoDB (local or cloud instance)

### Steps

 **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/event-booking-college.git
   cd event-booking-college
Install dependencies:
bash

npm install

# Set up environment variables:
Create a .env file in the root directory and add the following:
env

PORT=3000
MONGODB_URI=your_mongodb_connection_string


Start the application:
bash

npm start

Open your browser and go to:
arduino

http://localhost:3000

# Usage

Navigate to the homepage to view upcoming events.
Register for an account or log in.
Browse events, select one, and proceed to book it.
Complete the payment using Razorpay.

# Contributing

Contributions are welcome! Please follow these steps:
Fork the repository.
Create your feature branch: git checkout -b feature/YourFeature
Commit your changes: git commit -m 'Add some feature'
Push to the branch: git push origin feature/YourFeature
Open a pull request.
