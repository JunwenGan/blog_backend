# Overview
 This is the backend for the Dendi Blog, a RESTful API built with Flask and integrated with MongoDB to handle article management, user authentication, and comments functionality. The backend is designed to provide a robust and scalable API for the frontend to interact with.
# Features
Authentication: Secure JWT-based user authentication and authorization.
CRUD Operations:
Articles: Create, Read, Update, Delete articles (admin-only).
Comments: Add and view comments for articles.
Pagination: Paginated API endpoints for fetching articles.
Environment-Specific Configurations: Seamless switch between local development and production environments.
Secure Storage: MongoDB as the database for scalable data handling.
# Tech Stack
Framework: Flask, flask-restful
Database: MongoDB for managing articles, users, and comments.
Authentication: Flask-JWT-Extended for secure token-based authentication.
Environment Management: Python dotenv for configuration management.
# Setup Instructions
1. git clone https://github.com/your-username/blog-backend.git
2. python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. pip install -r requirements.txt
4. Configure environment variables
Create a .env file in the root directory with the following contents:
5. python app.py

