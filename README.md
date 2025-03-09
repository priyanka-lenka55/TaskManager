# Task Management System

## Backend Setup (Django)

### Steps to Set Up the Backend

1. **Clone the repository**  
   ```sh
   git clone <your-repo-url>


2. **Create and activate a virtual environment**  
   ```sh
   python -m venv venv
   source venv/bin/activate  # For macOS/Linux
   venv\Scripts\activate     # For Windows
   ```

3. **Install dependencies**  
   ```sh
   pip install -r requirements.txt
   ```

4. **Set up the database (PostgreSQL or SQLite)**  
   Update `settings.py` with your database configuration.

5. **Run database migrations**  
   ```sh
   python manage.py migrate
   ```

6. **Create a superuser (for admin access)**  
   ```sh
   python manage.py createsuperuser
   ```

7. **Run the server**  
   ```sh
   python manage.py runserver
   ```
   The API will be available at `http://127.0.0.1:8000/`.

##Frontend

create react app
npx create-react-app task-manager
cd task-manager

npm install axios react-router-dom styled-components - install required packages

then start
npm start

---


## Technologies Used

### Backend:
- Django – Web framework
- Django REST Framework (DRF) – API development
- SQLite – Database (SQLite can be used for development)
- djangorestframework-simplejwt – JWT-based authentication

### Frontend:
- React.js – UI development
- Axios – API handling
- React Router – Navigation
- CSS – Styling
---

## Future Enhancements
- Add task reminders via email notifications
- Implement search and filter functionality for tasks
