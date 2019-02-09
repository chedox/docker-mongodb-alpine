# docker-mongodb-alpine

MongoDB docker image based on alpine linux
--------------------------------------------

Installation
---------------
Clone Dockerfile from this github repository:

https://github.com/chedox/docker-mongodb-alpine


Build image in Docker by using this command:
---------------------------------------------
docker build -t chedox/mongodb-alpine:latest .


To run this images, type this command:
---------------------------------------
docker run -d -p 27017:27017 -v ~/usr/apps/data/docker_data/mongodb:/data/db chedox/mongodb-alpine:latest


Mounting volume
------------------------
That's to put -v ~/usr/apps/docker_data/mongodb:/data/db


MongoDB GUI interface
------------------------
To use mongoDB GUI browser, you can use Robomongo.

To find Ip Address, type this command:

docker inspect (containerid)

