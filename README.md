# Dev Journey

#### Author: [Ariso Okanga](https://github.com/Arisodee)

## Description
This web application allows users to post their journey towards becoming developers: some materials that helped them, challenges faced, what kept them going and future plans and goals,

A user will be able to:

1. Sign up and log in
2. Post their journey and have other users comment on them
3. View posts by other users and comment on them
4. Delete their posts
5. Post links to great resources

| Behavior            | Input                         | Output                        | 
| ------------------- | ----------------------------- | ----------------------------- |
| Login	if already have an account |if you dont have , click on the sign up link and fill the form  | If login is successful, user is able to post and comment on posts | Click on `Add comment` | navigated to where a user can write a comment | Signs In/ Signs Up| Add a new post|Click on the new post at the navbar to be redirected to the new post form| Post is rendered on the home page
| Click on log Out| Redirects to the home page read-only view | Logs out user  |

### Link to Live Site 
- [Dev Journey](https://ariso-devjourney.herokuapp.com/)


## Technologies Used
- Python 3.6
- Django MVC framework
- HTML, CSS and Bootstrap
- JavaScript
- Postgressql
- Heroku

### Prerequisite
This project requires a prerequisite understanding of the following:
- Django Framework
- Python3.6
- Postgres
- Python virtualenv

## Setup and installation

#### Clone the Repository
####  Activate virtual environment
Create and activate virtual environment using python3.6 as default handler
    `python3.6 -m venv virtual && source virtual/bin/activate`
####  Install dependancies
Install dependancies that will create an environment for the app to run `pip3 install -r requirements.txt`
####  Create the Database
    - psql
    - CREATE DATABASE devjourney;
####  .env file
Create a file named`.env`  and copy paste the following filling-in where appropriate:
```
SECRET_KEY='<your secret key>'
DEBUG=True
DB_NAME='devjourney'
DB_USER='<your database username>'
DB_PASSWORD='<password to your database>'
DB_HOST='127.0.0.1'
MODE='dev'
ALLOWED_HOSTS='.localhost', '.herokuapp.com', '.127.0.0.1'
DISABLE_COLLECTSTATIC=1
```
#### Run initial Migration
python3.6 manage.py makemigrations dev
python3.6 manage.py migrate

#### Run the app
python3.6 manage.py runserver
Open terminal on localhost:8000

## Known bugs
No known bugs at the moment

## Support and contact details
Incase you come across errors, have any questions, ideas ,concerns, or want to contribute to the application, feel free to reach me at : arisodee@gmail.com

### License

* LICENSED UNDER  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](license/MIT)


