# ClockRoom Plus

# video Link
https://drive.google.com/drive/folders/1slMC6H-X7w7vsU89hz3Vg4JOgSTX2mvv

# Problem statment
#Travelers at railway stations, bus terminals, and airports often face difficulties in finding nearby clock rooms to store their luggage. The lack of a centralized system makes it inconvenient and time-consuming to locate available clock rooms. Additionally, there is no streamlined process for arranging luggage pickup and delivery, making the experience inefficient. This creates a need for a web-based solution that helps travelers easily find nearby clock rooms, arrange luggage transportation, and make secure payments.
A modern web application for managing time and schedules efficiently.

# Team memebers
# B.Mani Sai Prasanth(99220040245@klu.ac.in)
# V.Kasi Amarnath Reddy(99220040222@klu.ac.in)
# G.Indhu(99220040056@klu.ac.in)
# B.Muni Bindu(99220040023@klu.ac.in)

# Solution Overview
The Clock Room System is a web-based platform designed to help travelers locate nearby clock rooms, arrange luggage pickup and delivery, and facilitate secure payments. The system integrates live location tracking, OTP-based authentication, and a seamless booking process to enhance user convenience and security.

## Project Structure

```
clockroom-plus/
├── frontend/           # React/TypeScript frontend
│   ├── src/           # Source code
│   ├── public/        # Static files
│   └── package.json   # Frontend dependencies
│
└── backend/           # Flask backend
    ├── templates/     # HTML templates
    ├── static/        # Static files
    ├── migrations/    # Database migrations
    ├── app.py         # Main application file
    ├── models.py      # Database models
    └── requirements.txt # Backend dependencies
```

## Setup Instructions

### Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd backend
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Set up environment variables:
   - Copy `.env.example` to `.env`
   - Update the variables in `.env`

5. Initialize the database:
   ```bash
   python init_db.py
   ```

6. Run the Flask application:
   ```bash
   flask run
   ```

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

## Features

- User authentication with OTP verification
- Role-based access control (User, Servant, Admin)
- Time management and scheduling
- Real-time location tracking
- Secure payment processing
- Modern and responsive UI

## Development

- Backend API runs on: http://localhost:5000
- Frontend development server runs on: http://localhost:5173

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request
