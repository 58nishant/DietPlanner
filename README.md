#Diet Planner
Diet Planner is a personalized web application designed to generate tailored exercise and diet plans based on user preferences and fitness goals. Built with Django, the app collects user details like gender, age, height, dietary preferences, and fitness goals, and outputs a weekly exercise routine and a consistent daily diet plan.

Table of Contents
Features
Tech Stack
Installation
Usage
Screenshots
Contributing
License
Features
User Input for Customization: Collects user data on age, gender, height, dietary preference (veg/non-veg), and fitness goals like weight loss or muscle gain.
BMI Calculator: Automatically calculates BMI using height and weight inputs to guide plan recommendations.
Weekly Exercise Plan: Provides users with a day-wise exercise plan based on their selected fitness goals.
Daily Diet Plan: Generates a consistent meal plan (breakfast, lunch, and dinner) in line with the user’s dietary preference.
Responsive UI: Optimized for desktop and mobile for a smooth user experience.
Tech Stack
Frontend: HTML, CSS, JavaScript
Backend: Django, Django REST Framework
Database: SQLite (or other databases such as PostgreSQL for production)
APIs: (Optional - list any if used)
Deployment: (Add here if deployed, e.g., Heroku, Vercel, etc.)
Installation
Clone the Repository

git clone https://github.com/58nishant/DietPlanner.git
cd DietPlanner
Create and Activate a Virtual Environment

python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
Install Required Packages

pip install -r requirements.txt
Run Database Migrations

python manage.py migrate
Start the Development Server

python manage.py runserver
Access the Application Go to http://localhost:8000 in your browser.

Usage
Sign Up / Log In: Create an account to access personalized diet and exercise plans.
Enter Personal Details: Provide age, gender, height, dietary preferences, and fitness goals.
Receive Plans: Get a weekly exercise schedule and daily diet plan tailored to your needs.
Update Preferences: Adjust inputs to receive updated plans anytime.
Screenshots
(Add screenshots of the main pages here to visually showcase the app’s design)

Contributing
Fork the repository.
Create your feature branch (git checkout -b feature/AmazingFeature).
Commit your changes (git commit -m 'Add some AmazingFeature').
Push to the branch (git push origin feature/AmazingFeature).
Open a Pull Request for review.
