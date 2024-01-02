# Simple Python Flask Dockerized Application#

Build the image using the following command

```bash
$ docker build -t simple-flask-app:0.0.v1 .
```

Run the Docker container using the command shown below.

```bash
$ docker run -d -p 8080:5000 simple-flask-app
```

The application will be accessible at http:public_ip:8080
