# Face Recognition Attendance System

A modern attendance tracking system that uses face recognition technology to automatically record attendance. The system captures faces every 10 seconds and logs attendance in real-time.

## Features

- Automatic face capture every 10 seconds
- Real-time face recognition and attendance marking
- User registration system to add new faces
- Attendance records with filtering and export capabilities
- Dashboard with attendance statistics and trends
- Responsive design for all devices

## Tech Stack

- **Frontend**: React with TypeScript, Tailwind CSS
- **Backend**: Flask with Python
- **Face Recognition**: face_recognition library
- **Data Storage**: JSON files (can be upgraded to a database)

## Installation

### Prerequisites

- Node.js
- Python 3.6+
- pip

### Setup

1. Clone the repository
2. Install frontend dependencies:

```bash
npm install
```

3. Install backend dependencies:

```bash
cd api
pip install -r requirements.txt
```

4. Start the development servers:

```bash
npm start
```

This will start both the React frontend and Flask backend servers.

## Usage

1. **Register Faces**: Navigate to the "Register Face" page to add new users to the system.
2. **Take Attendance**: Go to the "Attendance Camera" page where faces will be automatically captured every 10 seconds.
3. **View Records**: Check attendance records on the "Attendance Records" page with filtering options.
4. **Dashboard**: See attendance statistics and trends on the Dashboard.

## Project Structure

- `/src`: React frontend code
  - `/components`: Reusable UI components
  - `/context`: React context for state management
  - `/pages`: Main application pages
- `/api`: Flask backend code
  - `app.py`: Main Flask application
  - `/data`: Storage for face data and attendance records (created at runtime)

## Development

To start only the frontend:

```bash
npm run dev
```

To start only the backend:

```bash
cd api
flask run
```

## License

MIT