# Bus Reservation System

This is a simple Bus Reservation System built using Python and Django framework. The system allows users to search for available buses, make reservations, and view their booking details.

## Features

- User authentication: Users can sign up, log in, and log out.
- Bus search: Users can search for available buses based on their origin, destination, and date of travel.
- Seat selection: Users can select seats from the available seats on the chosen bus.
- Reservation: Users can make reservations for selected seats.
- Booking details: Users can view their booking details including the bus details, seat numbers, and reservation status.

## Technologies Used

- Python
- Django
- SQLite (for database)

## Installation

1. Clone the repository:

```
git clone https://github.com/your-username/bus-reservation-system.git
```

2. Navigate to the project directory:

```
cd bus-reservation-system
```

3. Install dependencies:

```
pip install -r requirements.txt
```

4. Run migrations:

```
python manage.py migrate
```

5. Create a superuser:

```
python manage.py createsuperuser
```

6. Start the development server:

```
python manage.py runserver
```

7. Visit `http://127.0.0.1:8000/` in your browser to access the application.

## Usage

1. Sign up or log in using your credentials.
2. Search for available buses by providing origin, destination, and date of travel.
3. Select available bus and seats.
4. Make a reservation.
5. View booking details in the dashboard.

