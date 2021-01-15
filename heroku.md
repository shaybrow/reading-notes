# Heroku Setup

[Back to Main Page](README.md)

1. Download the installer for your system

1. use `heroku login` to login to heroku on cmd

1. this will pull up a browser window for you to log in

1. `$ node --version` to confirm everything is up to date

1. clone the app source code

1. deploy the application `git push heroku main`

1. `heroku logs --tail` to view logs

1. use a `procfile` to declare what will happen on launch of your app

1. `heroku ps:scale web =val` to add additional dynos

1. declare and install any app dependencies

1. `heroku local` to run the app locally 

1. push and test local changes

1. acp to heroku

1. `heroku addons:` to provision any add ons

1. `heroku run bash` to run a console 

1. define config variables

1. provision your database