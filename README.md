# Django Blog Website

A fully featured blog website built with the Django framework. This project includes user authentication, post creation and management, commenting functionality, and a clean, responsive design.

## Features

* User registration and login
* Create, read, update, and delete blog posts
* Comment system for user interaction
* Pagination for blog posts
* Responsive frontend design
* Admin panel for site management

## Tech Stack

* **Backend:** Django
* **Frontend:** HTML, CSS, JavaScript (optional enhancements)
* **Database:** SQLite (default), can be switched to PostgreSQL or MySQL
* **Environment:** Python 3.x

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/your-blog-project.git
cd your-blog-project
```

2. Create a virtual environment and activate it:

```bash
python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\\Scripts\\activate    # Windows
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Apply migrations:

```bash
python manage.py migrate
```

5. Run the development server:

```bash
python manage.py runserver
```

6. Visit the site at:

```
http://127.0.0.1:8000/
```

## Project Structure

```
project_root/
│ manage.py
│ requirements.txt
├── blog/
│   ├── views.py
│   ├── models.py
│   ├── urls.py
│   ├── templates/blog/
│   └── static/blog/
└── project/
    ├── settings.py
    ├── urls.py
    └── wsgi.py
```

## Environment Variables

Create a `.env` file for sensitive settings:

```
SECRET_KEY=your_secret_key
DEBUG=True
```

## How to Create a Superuser

```bash
python manage.py createsuperuser
```

Then visit:

```
http://127.0.0.1:8000/admin/
```

## Deployment

For production deployment, consider:

* Gunicorn or uWSGI
* Nginx reverse proxy
* PostgreSQL database
* Static file handling with `collectstatic`

## License

This project is licensed under the MIT License.

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## Contact

For questions or suggestions, feel free to reach out
<img width="1919" height="1015" alt="Screenshot 2025-12-10 195908" src="https://github.com/user-attachments/assets/26730f01-e3c4-41b8-b64d-cc388f191a4e" />
<img width="1919" height=<img width="1919" height="1023" alt="Screenshot 2025-12-10 200015" src="https://github.com/user-attachments/assets/caa67784-229d-4d41-bb7a-dd0466485a89" />
"1020" alt="Screenshot 2025-12-10 200002" src="https://github.com/user-attachments/assets/5455a3d5-d036-444a-aea8-70d1b43a4570" />
<img width="1919" height="1023" alt="Screenshot 2025-12-10 200015" src="https://github.com/user-attachments/assets/5d1c609a-a1e5-4329-aa09-a5fbeb103786" />

<img width="1919" height="1014" alt="Screenshot 2025-12-10 200042" src="https://github.com/user-attachments/assets/00ade5e5-19b5-4fcf-9e0b-dd9e1ed3d5c5" />
<img width="1919" height="1021" alt="Screenshot 2025-12-10 200055" src="https://github.com/user-attachments/assets/bc461f1a-0006-4f87-8bd1-b82340145948" />

<img width="1919" height="1020" alt="Screenshot 2025-12-10 200125" src="https://github.com/user-attachments/assets/7c6c016f-1716-45c2-97b9-56f0e21ca9f4" />
