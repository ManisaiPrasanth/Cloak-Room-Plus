# ClockRoom Plus

A modern web application for managing time and schedules efficiently.

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
