
# New Django Project

## Blog
A simple blog app built with Django, which allows users to create, manage, and interact with blog posts.

---

## Features

- **User Authentication**: Users can sign up, log in, and manage their accounts.
- **Blog**: Users can create, edit, delete, and view blog posts.

---

## Technologies Used

- Django
- SQLite (default database for development)
- HTML/CSS for frontend
- Bootstrap for UI styling

---

## Setup Instructions

### Prerequisites

Make sure you have the following installed:

- Python 3.x
- Django (You can install it using `pip install django`)

### Installation Steps

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/umerkk9/new.git
   cd new
   ```

2. Create a virtual environment (optional but recommended):

   ```bash
   python -m venv venv
   ```

3. Activate the virtual environment:
   - For Windows:
     ```bash
     venv\Scriptsctivate
     ```
   - For macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

4. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Run migrations to set up the database:

   ```bash
   python manage.py migrate
   ```

6. Create a superuser to access the Django admin panel:

   ```bash
   python manage.py createsuperuser
   ```

7. Run the development server:

   ```bash
   python manage.py runserver
   ```

8. Open your browser and go to `http://127.0.0.1:8000/` to view the app.

---

## Admin Panel

You can access the Django admin panel at `http://127.0.0.1:8000/admin/` and log in with the superuser credentials created earlier. From there, you can manage users and blog posts.

---

## How to Use

1. Sign up for a new account or log in with an existing account.
2. Once logged in, navigate to the blog section to create, edit, or view blog posts.
3. You can manage your user profile from the user app.

---

## Contribution

Feel free to fork the repository and make improvements. You can open a pull request for any contributions you'd like to make.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
