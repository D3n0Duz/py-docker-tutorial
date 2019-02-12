# This is a simple python server with a dockerfile. #


Build the image using the following command

```bash
$ docker build -t [IMAGE NAME] .
$ docker build -t simple-flask-app:latest .
```

Run the Docker container using the command shown below.

```bash
$ docker run -d -p [PORT]:[PORT] [IMAGE NAME]
$ docker run -d -p 5000:5000 simple-flask-app
```

The application will be accessible at http:127.0.0.1:5000.
