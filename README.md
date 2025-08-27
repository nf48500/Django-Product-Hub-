# Django-Product-Hub-
This is a simple Django-based e-commerce project that connects to a database using Python. It manages products through models, supports image/media files, and allows easy product listing with query sets.
🛒 Django Products App

A simple Django web application for displaying products stored in a database.

🚀 Features

Products are defined in the model file with fields such as name, price, stock, and creation date.

A Meta class is used to order products by creation date.

A DateTimeField is included to track when each product was added.

Data is retrieved dynamically using QuerySets.

Media files are supported for uploading and displaying product images.

Clear project structure with Models, Views, Templates, and URLs.

🛠️ Tech Stack

Python 3.13

Django 5.2

SQLite (default) / MySQL / PostgreSQL

▶️ How to Run

Clone the repository.

Create and activate a virtual environment.

Install dependencies.

Run database migrations.

Optionally create a superuser for admin access.

Start the development server.

Open the products page in your browser.

📂 Media Files

Product images are stored in the media/ directory.

Configure MEDIA_URL and MEDIA_ROOT in the settings to serve uploaded files.
