# devilbox

1. Install docker (https://www.docker.com/)

2. Install Devilbox

```
# Get the devilbox (I cloned the repository into a docker folder in my Document folder)
$ git clone https://github.com/cytopia/devilbox
$ cd devilbox

# Download sample-env and place it in the devilbox directory.
$ cp sample-env .env

# Edit your configuration
$ nano .env

Important Lines:
83-84
366 (not hugely important)

# Start all containers
$ docker-compose up
```

##having issues?
Try this:
```
$ docker-compose stop
$ docker-compose kill
$ docker-compose rm -f
$ docker-compose up
```


## devilbox documentation
https://github.com/cytopia/devilbox
