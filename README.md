# Django-Bank – Fuat Bank Web Application

> A full-stack banking website built with Django and Bootstrap, featuring account management and transaction capabilities.

---

## About the Project

Django-Bank (Fuat Bank) is a banking web application built with Python and Django. It includes user account management, a banking system module, and transaction functionality. The project is designed with Bootstrap for a responsive and professional look.

---

## Features

- User account creation and authentication
- Banking system with account overview
- Transaction management (send / receive funds)
- Core banking logic separated into dedicated app modules
- Django admin panel for management
- Responsive UI with Bootstrap

---

## Technologies Used

| Technology | Version |
|---|---|
| Python | 3.x |
| Django | – |
| Bootstrap | 4/5 |
| HTML5 / CSS3 | – |
| JavaScript | – |

---

## Project Structure

```
Django-Bank/
├── accounts/         # User authentication app
├── bankingsystem/    # Banking logic app
├── bankingsystems/   # Banking configuration
├── core/             # Core app (homepage, shared views)
├── transactions/     # Transaction handling app
├── manage.py
└── requirements.txt
```

---

## Getting Started

Follow these steps to run the project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/fuatsevinc/Django-Bank.git
   cd Django-Bank
   ```

2. **Create a virtual environment**
   ```bash
   python3 -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations**
   ```bash
   python3 manage.py makemigrations
   python3 manage.py migrate
   ```

5. **Run the development server**
   ```bash
   python3 manage.py runserver
   ```

6. Open your browser and visit: `http://127.0.0.1:8000/`

---

## License

This project is open source and available under the [MIT License](LICENSE).

---

Developed by [fuatsevinc](https://github.com/fuatsevinc) · [www.fuatsevinc.com](https://www.fuatsevinc.com)
