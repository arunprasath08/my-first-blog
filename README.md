📝 My Blog on Data Engineering

A personal blog built with Django and PythonAnywhere hosting to share insights, tutorials, and experiences around Data Engineering, ETL/ELT, Data Warehousing, Azure Cloud, AI, and Analytics.

This project is both a learning journey (sharpening my web development skills) and a knowledge-sharing platform for the data community.

🚀 Features

🌐 Custom Blog Website built using Django (Python framework)

🖌️ Responsive Frontend styled with HTML + CSS (static files managed properly in Django)

✍️ Admin Panel to create and manage posts dynamically

🗂️ Organized posts around Data Engineering, ETL/ELT, Azure Cloud, AI & Analytics

☁️ Deployed on PythonAnywhere, with Git-based version control

🔄 Continuous improvements — from backend queries to frontend styling

🛠️ Tech Stack
Backend: Django (Python)
Frontend: HTML, CSS, Django Templates
Database: SQLite (default Django DB)
Deployment: PythonAnywhere
Version Control: Git + GitHub

📖 Learning Journey

This project started as a small experiment but turned into a full-fledged blog platform. Along the way, I learned:

Django Basics

Setting up projects and apps (startproject, startapp)

Models, views, templates (MVT architecture)

Admin panel customization

Frontend Integration

Linking static files correctly in Django

Using blog.css to manage blog styling

Debugging CSS caching issues both locally and in production

Dynamic Content

Querying posts in views.py (Post.objects.all())

Rendering content in templates with {% for post in posts %}

Handling published vs draft posts

Deployment

Hosting the app on PythonAnywhere

Mapping static files in the Web tab

Running collectstatic for production readiness

Fixing caching and refresh issues for updated CSS

Version Control & Collaboration

Using GitHub for versioning

Syncing changes between local and hosted versions

Structuring commits for clarity (bug fixes, features, styling updates)

⚡ Setup Instructions

Want to run this project locally?

Clone the repo

git clone https://github.com/arunprasath08/my-first-blog.git

cd my-first-blog


Set up a virtual environment

python -m venv venv

source venv/bin/activate    # On Windows: venv\Scripts\activate


Install dependencies

pip install -r requirements.txt


Run migrations

python manage.py migrate


Start development server

python manage.py runserver


Visit http:/127.0.0.1:8000/ in your browser.

Create an admin user (to add posts)

python manage.py createsuperuser

🌟 Key Takeaways

Built a full-stack blog platform using Django from scratch
Solved real-world issues like CSS not loading, static file mapping, deployment caching
Learned how to host, maintain, and scale a Python web app
Created a platform to share Data Engineering knowledge with the community

👉 Visit My Blog https://arunprasath08.pythonanywhere.com/

This is a personal learning project, but feedback and suggestions are always welcome!
Open issues for bugs or feature requests.Fork the repo and submit pull requests.

