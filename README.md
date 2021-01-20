# Django Pollster, A Voting App

A Polling Application built with Python's Django


## The App Preview
![pollster](https://github.com/tijjken/pollster/blob/master/static/Pollster1.png)
![pollster](https://github.com/tijjken/pollster/blob/master/static/Pollster2.png)
![pollster](https://github.com/tijjken/pollster/blob/master/static/Pollster3.png)
![pollster](https://github.com/tijjken/pollster/blob/master/static/Pollster4.png)


### Setup
To get this repository, run the following command inside your git enabled terminal

```
$ git clone https://https://github.com/tijjken/pollster.git
```
You will need django to be installed in you computer to run this app. Head over to https://www.djangoproject.com/download/ for the download guide

Once you have downloaded django, go to the cloned repo directory and run the following command

```
$ python manage.py makemigrations
```

This will create all the migrations file (database migrations) required to run this App.

Now, to apply this migrations run the following command
```
$ python manage.py migrate
```

One last step and then our Voting App will be live. We need to create an admin user to run this App. On the terminal, type the following command and provide username, password and email for the admin user
```
$ python manage.py createsuperuser
```

That was pretty simple, right? Now let's make the App live. We just need to start the server now and then we can start using our Pollster  App. Start the server by following command

```
$ python manage.py runserver
```

### Start the development server and visit http://127.0.0.1:8000/admin/ to create a poll.


### Once a poll is created, visit http://127.0.0.1:8000 to participate in the poll

### Improvements to be made: 
Mutiple voting capability \
User Account \
Voting History
