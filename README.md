# Takefive Backend Docker Image

This is the base staging/production image for all backend services.


## Usage

Reference this image on the first line of all project images, eg.

```
FROM takefive/takefive-backend-docker-image
```

The default directory of this image is the `$HOME` directory.


## Building

1. Ensure that Docker Toolbelt is installed on your machine.
2. Open Docker Quickstart Terminal (CLI), and do:
```bash
$ docker build -t takefive-backend-docker-image .
```
3. After everything settles, do `git push origin master`. The image will be built automatically on docker hub.
