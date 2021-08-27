# Title

**BLOGPROJECT**

## Description
This  is a personal blogging website where you can create and share your opinions and other users can read and comment on them. It  also has random quotes that inspire the users.  

## Author


* [**gingerlauren**](https://github.com/gingerlauren)

## Features


As a user of the web application you will be able to:

1. See all blogs
2. Create an account
3. Log in
4. Create a blog
5. Comment on a blog
6. See comments posted on each individual blog
7. Edit your profile i.e will be able to add a short bio about yourself and a profile picture



## CODEBEAT

[![codebeat badge](https://codebeat.co/badges/fd154ec5-b8be-439a-a73c-054a2eb00637)](https://codebeat.co/projects/github-com-antomuli-personal-blog-master)
## Getting started
### Prerequisites
* python3.6
* virtual environment
* pip



## Running the Application
* Install virtual environment using `$ python3.6 -m venv --without-pip virtual`
* Activate virtual environment using `$ source virtual/bin/activate`
* Download pip in our environment using `$ curl https://bootstrap.pypa.io/get-pip.py | python`
* Install all the dependencies from the requirements.txt file by running `python3.6 pip install -r requirements.txt`
* Create a `start.sh` file in the root of the folder and add the following code:

        export MAIL_USERNAME=<your-email-address>
        export MAIL_PASSWORD=<your-email-password>
        export SECRET_KEY=<your-secret-key>

* Edit the configuration instance in `manage.py` by commenting on `production` instance and uncommenting `development` instance
* To run the application, in your terminal:

        $ chmod a+x start.sh
        $ ./start.sh
        
## Testing the Application
* To run the tests for the class file:

        $ python3.8 manage.py server
        
## Technologies Used
* Python3.6
* Flask
* HTML
* Bootstrap

This application is developed using [Python3.8](https://www.python.org/doc/), [Flask](http://flask.palletsprojects.com/en/1.1.x/), [HTML](https://getbootstrap.com/) and [Bootstrap](https://getbootstrap.com/)

## Known Bugs
* The blog doesn't meet all the user's stories/needs.

* The user may have some difficulty in profile handling and management since it's still under development.


