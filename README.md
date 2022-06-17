# Docker Demo #

Run using docker-compose

```bash
$ docker-compose up
```

Run using docker

Build the backend using the following command.

```bash
$ cd backend
$ docker build -t python-demo:latest .
$ docker run -d -p 5000:5000 --name python-demo-running python-demo
```
