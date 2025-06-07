# VerseReads

This repository contains a minimal Django project skeleton for the VerseReads eBook bookstore. The UI uses Tailwind CSS and HTMX with Inter fonts and a responsive navbar, landing page and authentication pages.

## Development

1. Ensure Python 3.11 and Django are installed.
2. Install requirements:
   ```bash
   pip install -r requirements.txt
   ```
3. Run migrations and start the server:
   ```bash
   python manage.py migrate
   python manage.py runserver
   ```

Visit `http://localhost:8000/` to see the landing page. Access the login page at `/accounts/login/` and the signup page at `/accounts/signup/`.
