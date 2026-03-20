# Blog Website (Flask Project)

A Flask-based blog web application that allows users to register, log in, create posts, and view blog content. The project demonstrates full-stack development using Python, HTML, CSS, and SQLite.

---

## Features

* User registration and login
* Create and view blog posts
* Structured templates using Flask (Jinja2)
* Static styling with CSS
* SQLite database integration

---

## Tech Stack

* Backend: Python (Flask)
* Frontend: HTML, CSS
* Database: SQLite
* Tools: Git, GitHub

---

## Project Structure

```
blog_website/
│
├── instance/
│   └── site.db              # SQLite database
│
├── static/
│   └── css/
│       └── style.css        # Stylesheet
│
├── templates/
│   ├── base.html
│   ├── create_post.html
│   ├── index.html
│   ├── login.html
│   ├── post.html
│   └── register.html
│
├── app.py                   # Main Flask application
├── requirements.txt
└── README.md
```

Note: The `venv/` folder is not included in the repository.

---

## Installation and Setup

1. Clone the repository

```
git clone https://github.com/Sreelakshmi-2005-cs/Blogpost.git
cd Blogpost
```

2. Create virtual environment

```
python -m venv venv
```

3. Activate virtual environment

Windows:

```
venv\Scripts\activate
```

Mac/Linux:

```
source venv/bin/activate
```

4. Install dependencies

```
pip install -r requirements.txt
```

5. Run the application

```
python app.py
```

6. Open in browser

```
http://127.0.0.1:5000
```

---

## Future Improvements

* Add user authentication security enhancements
* Improve UI design
* Add comments and likes feature
* Deploy the application online

---

## Author

Sreelakshmi

