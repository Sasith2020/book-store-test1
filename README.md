# VerseReads

This repository contains a minimal Django project skeleton for the VerseReads eBook bookstore. The UI uses Tailwind CSS and HTMX with a responsive navbar, landing page and login page.

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

Visit `http://localhost:8000/` to see the landing page.
