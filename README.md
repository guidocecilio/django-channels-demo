# django-channels-demo
WebSockets demo (via Django Channels) managing the communication between the client and the server.

This demo pretend to show the use of Django Channels and an Aurelia web application that use the service as 
a fullduplex API to keep clients updated of changes.

The code is based on the [Getting Started With Django Channels](https://realpython.com/blog/python/getting-started-with-django-channels/)
tutorial.

## Requirements
* Python 2.0
* Django >= 1.10.5
* Django Channels >= 1.0.3
* Redis Server


## Installation

```shell
$ git clone git@github.com:guidocecilio/django-channels-demo.git
$ cd django-channels-demo
```

### Create and activate the virtual environment
```shell
$ virtualenv --no-site-package .env
$ source .env/bin/activate
```
### Installing requirements
```shell
(.env) $ pip install -r requirements.txt
```

### Applying migrations
```shell
(.env) $ python example_channels/manager.py migrate
```

## Running the server
```shell
(.env) $ python example_channels/manage.py runserver
```
Once the server is running, visit the "[http://localhost:8000](http://localhost:8000)" to test the app.

## Redis
This application demo use Redis

### Installing Redis server
#### Installing Redis Server on Ubuntu 16.04
To install Redis server:
```shell
$ sudo apt-get install redis-server
```

To start Redis service:
```shell
$ sudo systemctl restart redis-server.service
```









