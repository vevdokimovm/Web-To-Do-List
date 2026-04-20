# Web-To-Do-List

A simple web-based To-Do list application with add, edit, and delete functionality, built with Flask and SQLite.

## Features

- Add new tasks
- Edit existing tasks
- Delete tasks
- Persistent storage using SQLite via Flask-SQLAlchemy

## Tech Stack

- Python 3.10+
- [Flask](https://flask.palletsprojects.com/) — lightweight web framework
- [Flask-SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/) — ORM for database access
- SQLite — local database
- Jinja2 — HTML templating

## Getting Started

### Installation

```bash
git clone https://github.com/vevdokimovm/Web-To-Do-List.git
cd Web-To-Do-List
pip install -r requirements.txt
```

### Run

```bash
python app.py
```

Open [http://localhost:5000](http://localhost:5000) in your browser.

## Project Structure

```
Web-To-Do-List/
├── app.py              # Flask application and routes
├── templates/
│   └── index.html      # Main page template
├── requirements.txt
└── README.md
```

## License

MIT
