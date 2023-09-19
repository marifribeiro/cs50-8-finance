# CS50's Finance

![finance](https://user-images.githubusercontent.com/45573073/72932217-15ba0280-3d3e-11ea-81e5-5b77ad9f86d2.png)

## Introduction

This application was the 8th week's exercise of Harvard's CS50 - Introduction to Computer Science online course.
You can learn more about CS50 at [Harvard's CS50](https://online-learning.harvard.edu/course/cs50-introduction-computer-science).

The exercise proposes the following:
* Implemented a web application that enables the user can "buy" and "sell" stocks, following the criteria below:
* Complete the implementation of **register** in such a way that it allows a user to register for an account via a form.
* Complete the implementation of **quote** in such a way that it allows a user to look up a stock’s current price.
* Complete the implementation of **buy** in such a way that it enables a user to buy stocks.
* Complete the implementation of **sell** in such a way that it enables a user to sell shares of a stock (that he or she owns).
* Complete the implementation of **index** in such a way that it displays an HTML table summarizing, for the user currently logged in, which stocks the user owns, the numbers of shares owned, the current price of each stock, and the total value of each holding (i.e., shares times price). Also display the user’s current cash balance along with a grand total (i.e., stocks' total value plus cash).
* Complete the implementation of **history** in such a way that it displays an HTML table summarizing all of a user’s transactions ever, listing row by row each and every buy and every sell.
* Complete the implementation of **check** in such a way that it checks whether a username is available.

## Created with
This application uses Python, HTML and styling with Bootstrap. It also uses [IEX API](https://iexcloud.io/) to get the stocks values in real time and a SQL database to store users information, such as username, a hash of the password, the stocks they bought or sold and the history.

## Run
You will need [Python](https://www.python.org/downloads/) and [Flask](https://flask.palletsprojects.com/en/1.1.x/installation/) installed on your computer to run this application.

Start by installing [Python 3](https://www.python.org/downloads/). Here's a [guide on the installation](https://wiki.python.org/moin/BeginnersGuide/Download).
Once you have Python, and clonned this repository, run the following commands:

To install pip, run:

`sudo apt install python3-pip`

To install Flask, run:

`sudo apt install python3-flask`

To install this project's dependecies, run:

`pip3 install -r requirements.txt`

Define the correct file as the default Flask application:

Unix Bash (Linux, Mac, etc.):

`export FLASK_APP=application.py`

Windows CMD:

`set FLASK_APP=application.py`

Windows PowerShell:

`$env:FLASK_APP = "application.py"`

Run Flask and you're good to go!

`flask run`
