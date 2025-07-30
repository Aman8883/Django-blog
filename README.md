# Django Blog Project

A blog application built with Django following "Django by Example" tutorial.

## Features

- Blog post listing
- Post detail views
- Admin interface for content management
- Responsive design with background images

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/django-blog.git
   cd django-blog
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run migrations:**
   ```bash
   python manage.py migrate
   ```

5. **Create a superuser (optional):**
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server:**
   ```bash
   python manage.py runserver
   ```

7. **Access the application:**
   - Main site: http://127.0.0.1:8000/
   - Admin panel: http://127.0.0.1:8000/admin/

## Project Structure

```
django-blog/
├── blog/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── templates/
├── static/
├── media/
├── manage.py
├── requirements.txt
└── README.md
```

## Technologies Used

- Django 4.x
- Python 3.x
- HTML/CSS
- Font Awesome
- SQLite (default database)

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is for educational purposes.
