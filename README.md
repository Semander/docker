### Here all the comands I've used:

> building docker image:

**docker build . -t semander/node-web-app**

> looking for all the docker images:

**docker images**

> running docker image:

**docker run -p 80:80 -d semander/node-web-app**

> finding ID

**docker ps**

> outputing logs with found ID:

**docker logs <container_id>**
