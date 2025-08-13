# Elevate Lab Python Internship — Task 6 → Flask Portfolio Website

## 📋 Task Overview
**This project is a personal portfolio website built using the Flask web framework.**  
It displays personal details, provides a contact form, and uses a responsive design for different devices.  
The goal of the task was to create a simple yet functional portfolio that can be extended with more features in the future.

---

## 🎯 Objective
- Create a personal portfolio site.

---

## 📚 Approach

1. **Set up Flask Application**
   - Created a Flask app with routes for the homepage (`/`) and contact page (`/contact`).

2. **Design the Frontend**
   - Used HTML and CSS for layout.
   - Ensured the site is responsive for mobile and desktop.

3. **Implement Contact Form**
   - Used Flask’s request handling to process form data.
   - Displayed a success message using Flask’s flash system.

4. **Organize Files**
   - Templates (`index.html`, `contact.html`) stored in the `templates` folder.
   - Static assets like CSS in the `static` folder.

---

## 📂 Folder Structure

```
Flask-Portfolio/
│
├── app.py               # Main Flask application file
├── static/              # CSS
│   └── style.css
├── templates/           # HTML templates
│   ├── index.html
│   └── contact.html
└── README.md            # Project documentation
```

---

## 🛠 Tools Used

- **Python** – Main programming language.
- **Flask** – Web framework for routing and template rendering.
- **HTML5 & CSS3** – Frontend design and layout.
- **Jinja2** – Template engine used by Flask.

---

## ⚙ Setup Instructions

1. **Clone this repository**
   ```bash
   git clone https://github.com/USERNAME/REPO-NAME.git
   cd REPO-NAME
   ```

2. **Create and activate a virtual environment**
   ```bash
   python -m venv venv
   # On Windows
   venv\Scripts\activate
   # On Mac/Linux
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install flask
   ```

4. **Run the application**
   ```bash
   python app.py
   ```
   The app will run at: **http://127.0.0.1:5000/**

---
