### About Project 

This is a skill demonstration project.

I have built a simple fullstack web application using flask framework having a database. SQLAlchemy is used for facilitating the communication between the application and the database. This is an application
can be used for managing your daily task and it will make you more productive.



### How To Run

Open a terminal in the project root directory and run the following commands 

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
