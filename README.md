# django-channels-demo
WebSockets demo (via Django Channels) managing the communication between the client and the server.

This demo pretend to show the use of Django Channels and an Aurelia web application that use the service as 
a fullduplex API to keep clients updated of changes.

The code is based on the [Getting Started With Django Channels](https://realpython.com/blog/python/getting-started-with-django-channels/)
tutorial.

## Requirements
asgi-redis==1.4.2
asgiref==1.1.2
attrs==17.2.0
autobahn==17.6.2
Automat==0.6.0
channels==1.1.6
constantly==15.1.0
daphne==1.3.0
Django==1.11.3
hyperlink==17.2.1
incremental==17.5.0
msgpack-python==0.4.8
pytz==2017.2
redis==2.10.5
six==1.10.0
Twisted==17.5.0
txaio==2.8.0
zope.interface==4.4.2

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





