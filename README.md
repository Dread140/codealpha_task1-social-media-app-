Social Media App

A full-stack social media application built with Django and Bootstrap, allowing users to connect, share posts, and interact with each other in a clean and responsive interface.

Features

User Authentication: Sign up, login, and logout functionality.

User Profiles: View and update profile information, see personal posts.

Feed: Browse posts from all users, like and comment on posts.

Media Uploads: Upload images with posts.

Responsive Design: Works on desktop and mobile devices using Bootstrap.

Technologies Used

Backend: Django (Python)

Database: SQLite

Frontend: Bootstrap 5

Other: Django Widget Tweaks for form rendering

Installation

Clone the repository:

git clone <repository-url>


Navigate to the project folder:

cd social_media_app_final_ready


Create and activate a virtual environment:

python -m venv venv
.\venv\Scripts\activate      # Windows
source venv/bin/activate     # Linux / macOS


Install dependencies:

pip install -r requirements.txt


Run migrations:

python manage.py migrate


Start the development server:

python manage.py runserver


Open http://127.0.0.1:8000
 in your browser.

Folder Structure

accounts/ – User authentication and profile management.

posts/ – Post creation, feed, likes, and comments.

templates/ – HTML templates for frontend.

static/ – CSS, JS, and image files.

media/ – Uploaded media files.
