# ✅ Task Master — Daily Task Manager

**Task Master** is a simple full-stack web application for managing your daily tasks and improving productivity. It demonstrates core web development skills using Flask, SQLAlchemy, and SQLite.

---

## ✨ Features

- 🗂️ Add, update, and delete tasks
- 📅 Track daily goals
- ⚙️ Simple and intuitive interface
- 💾 Built with Flask + SQLAlchemy + SQLite

---

## 🛠 Tech Stack

- **Backend**: Flask, SQLAlchemy
- **Database**: SQLite
- **Frontend**: HTML, CSS (Bootstrap)
- **Environment**: Python (virtualenv)

---

## 🚀 Getting Started

Follow the steps below to set up and run the application locally.

1. Install `virtualenv`:
```
$ pip install virtualenv
```

2. Create virtual environment:
```
$ virtualenv env
```

3. Then run the command:
```
$ .\env\Scripts\activate
```

4. Then install the dependencies:
```
$ (env) pip install -r requirements.txt
```

5. Finally start the web server:
```
$ (env) python app.py
```

This server will start on port 5000 by default. You can change this in `app.py` by changing the following line to this:

```python
if __name__ == "__main__":
    app.run(debug=True, port=<desired port>)
```
