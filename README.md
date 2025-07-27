
# Student Performance Predictor

This project is a web-based application designed to predict and analyze student academic performance using historical data and machine learning models. It provides insights and predictions based on various parameters collected from students in two Portuguese schools.

## Features

- Predict student performance based on various input factors
- User authentication system (login/signup for students and faculty)
- Dashboards for students and faculty with detailed statistics
- Data visualization and reporting tools
- Dockerized setup for easy deployment

## Technologies Used

- **Python**
- **Flask** – for backend web development
- **SQLite** – for lightweight database management
- **HTML/CSS/JS** – for frontend UI
- **Jupyter Notebook** – for ML model experimentation
- **Scikit-learn** – for machine learning
- **Bootstrap** – for responsive design
- **Docker** – for containerization

## Setup Instructions

1. Clone the repository or download the ZIP.
2. Navigate to the root directory.
3. (Optional) Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
5. Run the application:
   ```bash
   python app.py
   ```
6. Open `http://127.0.0.1:5000` in your browser.

## File Structure

- `app.py` – Main Flask application
- `Notebook.ipynb` – Jupyter notebook with data analysis and model training
- `templates/` – HTML templates (frontend views)
- `static/` – Static files like CSS, JS, and images
- `students.db`, `users.db` – SQLite databases
- `student-mat.csv`, `student-por.csv` – Datasets used for model training
- `.github/workflows/` – CI/CD workflows
- `Dockerfile` – Docker configuration

## Datasets

- Two datasets: `student-mat.csv` (Math) and `student-por.csv` (Portuguese)
- Collected from UCI Machine Learning Repository

## Deployment

This application is ready to be deployed on services like Render or Heroku. A sample GitHub Actions workflow is included for automated deployment.

