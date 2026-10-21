# Expense Tracker

A Flask-based expense tracker built incrementally as a learning project.

## Tech Stack

- Python 3 / Flask 3.1
- SQLite (via `database/db.py`)
- Jinja2 templates

## Setup

```bash
python -m venv venv
source venv/Scripts/activate   # Windows (Git Bash)
# venv\Scripts\Activate.ps1    # Windows (PowerShell)
pip install -r requirements.txt
```

## Run

```bash
python app.py
```

The app serves on http://127.0.0.1:5001.

## Project Status

Routes and database logic are being built incrementally, step by step:

- [x] Landing, register, and login pages (templates wired up)
- [ ] Step 1 — Database setup (`database/db.py`: `get_db()`, `init_db()`, `seed_db()`)
- [ ] Step 3 — Logout
- [ ] Step 4 — Profile page
- [ ] Step 7 — Add expense
- [ ] Step 8 — Edit expense
- [ ] Step 9 — Delete expense

## Project Structure

```
app.py              Flask app and routes
database/db.py       SQLite connection and schema setup
templates/           Jinja2 HTML templates
static/              CSS and JS assets
```
