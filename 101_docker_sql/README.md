# Commands
## Build a Docker image from `Dockerfile`.
```
docker build -t test:V001 .
```
Docker build command looks into the current folder `.` for the `Dockerfile` and builds an docker image out of it. `test` is the name of new image with version `V001`.

## Run the image to create a Docker container.
```
docker run test:V001
```
