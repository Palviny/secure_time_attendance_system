# Time & Attendance Management System (TAMS)

## Requirements
- Python 3.10+
- pip
- Windows/macOS/Linux

## Setup (Local Installation)
1. Clone the repository
2. Create and activate a virtual environment
3. Install dependencies
4. Initialize the database
5. Create an admin user
6. Run the app

### Commands (Windows PowerShell)
```powershell
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python update_db.py
python create_admin.py
python app.py
