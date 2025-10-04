# User Management Application

A simple full-stack web application for managing users with Flask backend and vanilla JavaScript frontend.

## Project Structure
```
SAMPLE-PROJECT/
├── app.py              # Flask backend server
├── requirements.txt    # Python dependencies
├── index.html          # Main HTML page
├── style.css           # CSS styling
└── script.js           # Frontend JavaScript
```


## Quick Start

### 1. Setup Virtual Environment
```bash
# Create virtual environment
python -m venv venv

# Activate virtual environment
# Windows:
venv\Scripts\activate
# Mac/Linux:
source venv/bin/activate
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run Application
```bash
python app.py
```

### 4. Access Application
Open your browser and go to: `http://localhost:5000`
To run the frontend: `npm run dev`
## API Endpoints
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/users` | Get all users |
| POST | `/api/users` | Create new user |
| DELETE | `/api/users/<id>` | Delete user by ID |

## Usage
1. **Add User**: Fill name and email, click "Add User"
2. **View Users**: All users display automatically
3. **Delete User**: Click "Delete" button on any user card

**Note**: Data is stored in memory and will reset when server stops.
