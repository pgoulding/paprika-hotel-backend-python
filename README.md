# Paprika Hotel Back End (Python)

A Python API for a hotel signupbuilt with FastAPI, Uvicorn, SQLAlchemy, and PostgreSQL.

## Table of Contents

- [Paprika Hotel Back End (Python)](#paprika-hotel-back-end-python)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Features](#features)
  - [Technologies Used](#technologies-used)
  - [MVP Targets](#mvp-targets)
  - [Future Iterations and Goals](#future-iterations-and-goals)
  - [Contributing](#contributing)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)

## Installation

1. Clone the repo

   ```sh
   git clone https://github.com/pgoulding/paprika-hotel-backend-python
   ```

2. Navigate to the project directory

   ```sh
   cd paprika-hotel-backend-python
   ```

3. Install dependencies

   ```sh
   pip install -r requirements.txt
   ```

4. Set up the database

   ```sh
   python app/database.py
   ```

## Usage

1. Start the application

   ```sh
   uvicorn app.main:app --reload
   ```

2. Access the application
Open your browser and go to <http://localhost:8000>

## Features

- User authentication and authorization
- CRUD operations for items
- API integration with PostgreSQL

## Technologies Used

- Python
- FastAPI
- SQLAlchemy
- PostgreSQL
- Uvicorn

## MVP Targets

1. User Management
   - [ ] User Signup
   - [ ] User Login
   - [ ] User Profile

2. Reservation Management
   - [ ] Create Reservation
   - [ ] View Reservations
   - [ ] Modify Reservation
   - [ ] Cancel Reservation

3. Room Management
   - [ ] View Room Availability
   - [ ] Room Details
   - [ ] Admin Management

4. Manage Rooms
   - [ ] View All Reservations

## Future Iterations and Goals

1. Advanced User Features
   - [ ] Forgot Password
   - [ ] User Notifications

2. Payment Integration
   - [ ] Payment Processing
   - [ ] Refunds

3. Enhanced Reservation Features
   - [ ] Search and Filter Reservations
   - [ ] Reservation History

4. Room Enhancements
   - [ ] Room Reviews and Ratings
   - [ ] Room Upgrades

5. Admin Dashboard
   - [ ] Analytics and Reports
   - [ ] User Management
6. Scalability and Performance
   - [ ] Load Balancing
   - [ ] Database Optimization

7. Security Enhancements
   - [ ] Two-Factor Authentication
   - [ ] Rate Limiting

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch.

   ```sh
   git checkout -b feature/your_feature
   ```

3. Make your changes.
4. Commit your changes.

   ```sh
   git commit -m 'Add some feature'
   ```

5. Push to the branch.

   ```sh
   git push origin feature/your_feature
   ```

6. Open a pull request.

## License

Distributed under the MIT License. See LICENSE for more information.

## Acknowledgments

- FastAPI Documentation
- SQLAlchemy Documentation
- PostgreSQL Documentation