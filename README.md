# Photoshare
A web-based social network application (Photoshare) with a local servers and own DBMS
- [x] Back-end database design with relational model and relational algebra
- [x] Used SQL and Flask to build the local social network servers

ER-diagram for the back-end SQL database available here:
https://docs.google.com/drawings/d/1e12D737VA3nLqVPf9z5KWdkf04bbRbb8ov5sFg-AW4s/edit?usp=sharing

## Note: Steps to get the local server and Flask application running
0. open the terminal, cd to the directory and:
1. install all necessary packages 'pip install -r requirements.txt' (or use pip3)
2. export flask (Mac, Linux)'export FLASK_APP=app.py', (Windows)'set FLASK_APP=app.py'

3. run schema.sql using MySQL Workbench
4. Change line 32 in app.py to your MySQL root password.

6. back to the terminal, 'python -m flask run' (or use python3)
7. open your browser, and open the local website 'localhost:5000'
