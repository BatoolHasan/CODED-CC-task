# CODED-CC-task

### Note: Make sure to fork repo

### make sure `python` is installed

### make sure `pip` is installed `python3 get-pip.py`

### make sure `sqlmap` is installed `pip install sqlmap`

### run `npm i`

### run `npm start`

This simple webpage shows a login page. The valid credentials are:
username: admin
password: admin123

Make sure to try the credentials to validate it is working.
In theory, this password should be the only valid way to login as user admin.

## 1. Try to add malformed input values in the password field to login

## What is the malformed input value that allows you to gain access?

## 2. Run sqlmap. What are the possible injection points?

### Hint: use sqlmap -u "http://localhost:8080" --forms --crawl=2

## 3. Run sqlmap. What is the name of the table in this database?

## 4. Run sqlmap. Find the data of the table found in 3.

## 5. Use sqlmap to reveal what input can be used as credentials to login
