# Elective-Recommender-System
An Elective Recommender System suggests courses based on skills, interests, and academics using Collaborative &amp; Content-Based Filtering with Genetic Algorithms. It tackles the cold start problem, optimizes recommendations, and enhances decision-making with student data for personalized course selection.
Elective Recommender System

Overview

A machine learning-based tool that helps students select elective courses based on skills, interests, and academic background. It integrates Collaborative & Content-Based Filtering with Genetic Algorithm Optimization for personalized recommendations.

Features

Hybrid Recommendation using Collaborative & Content-Based Filtering.

Cold Start Handling for new students.

Multi-Criteria Optimization based on difficulty, instructor ratings, and relevance.

Genetic Algorithm Optimization for refining recommendations.

User-Friendly Interface with interactive dashboards.

Scalable & Secure for deployment in educational institutions.

Technologies Used

Backend: Django (Python)

Machine Learning: NumPy, Pandas, Scikit-learn

Database: SQLite/PostgreSQL

Frontend: HTML, CSS, JavaScript (if applicable)

Deployment: Docker, AWS/GCP (Optional)

System Architecture

The system follows a three-tier architecture:

Frontend (Client-Side) - Handles user interaction, built with HTML, CSS, and JavaScript.

Backend (Server-Side) - Processes recommendations using Django and machine learning models.

Database Layer - Stores student data, elective courses, and recommendations.

Dataset Structure

Students Table: Stores student details, academic records, and preferences.

Courses Table: Contains elective course details, ratings, and prerequisites.

Feedback Table: Records user feedback to improve recommendations.

Recommendation Algorithms

Item-Based Collaborative Filtering - Suggests electives based on similar students' choices.

Content-Based Filtering - Matches courses based on student interests and past selections.

Matrix Factorization (SVD) - Enhances accuracy in sparse data environments.

Genetic Algorithm Optimization - Improves recommendation ranking.

API Endpoints

User Authentication:

POST /api/register/ - Register a new user.

POST /api/login/ - Authenticate and get a token.

Course Recommendations:

GET /api/recommendations/ - Fetch personalized electives.

POST /api/feedback/ - Submit feedback for recommendations.

Installation

Clone the repository:

git clone https://github.com/yourusername/Elective-Recommender-System.git
cd Elective-Recommender-System

Create and activate a virtual environment:

python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

Install dependencies:

pip install -r requirement.txt

Apply database migrations:

python manage.py migrate

Run the server:

python manage.py runserver

Open http://127.0.0.1:8000/ in your browser.

Usage

Register/Login as a student.

Input academic details and interests.

View and refine recommended electives.

Submit feedback to improve recommendations.

Contribution

Fork the repo, create a branch, make changes, and submit a pull request.

License

Licensed under the MIT License - see LICENSE file for details.

Contact

For queries, reach out via udayatk02@gmail.com.
