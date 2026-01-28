Job Recruitment Platform
A dynamic web application built with Django designed to bridge the gap between job seekers and employers. This platform manages the entire hiring workflow, from job posting to application tracking.

💼 Key Features
Dual User Roles: Separate dashboards and functionalities for Job Seekers and Recruiters.

Job Management: Recruiters can create, edit, and delete job postings with specific requirements and descriptions.

Application Tracking: Job seekers can upload resumes and track the status of their submitted applications.

Search & Filter: Advanced filtering options to search for jobs based on categories, location, or salary.

🛠️ Tech Stack
Backend: Python 3.x, Django Web Framework

Frontend: HTML5, CSS3, JavaScript, Bootstrap

Database: PostgreSQL/SQLite

DevOps: Prepared for deployment using Docker and Kubernetes.

🚀 Setup Instructions
Clone the repository:

Bash
git clone https://github.com/Angelvij/Job_recruitment.git
Create a virtual environment:

Bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:

Bash
pip install -r requirements.txt
Database Setup:

Bash
python manage.py makemigrations
python manage.py migrate
Start the Platform:

Bash
python manage.py runserver
