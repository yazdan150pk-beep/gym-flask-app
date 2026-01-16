# Gym Flask App

A simple Flask web application for a gym website with information about memberships and services.

## Features

- **Home Page** - Welcome page with gym information
- **About Page** - Details about the gym
- **Membership Page** - Membership plans and pricing

## Project Structure

```
gym_flask_app/
├── app.py                 # Main Flask application
├── static/
│   ├── style.css         # Stylesheet
│   └── images/           # Images folder
└── templates/
    ├── index.html        # Home page
    ├── about.html        # About page
    └── membership.html    # Membership page
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yazdan150pk-beep/gym-flask-app.git
cd gym-flask-app
```

2. Create a virtual environment:
```bash
python -m venv venv
venv\Scripts\activate
```

3. Install Flask:
```bash
pip install flask
```

## Running the App

```bash
python app.py
```

The app will run on `http://localhost:5000`

## Routes

- `/` - Home page
- `/about` - About page
- `/membership` - Membership page

## Technologies Used

- Flask
- HTML/CSS
- Python

---

Made with ❤️
