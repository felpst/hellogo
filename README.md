# Full Cycle Docker Challenge
## Go Docker Challenge

This challenge is very exciting especially if you have never worked with the Go language!
You will have to publish an image to docker hub. When we run:

docker run <seu-user>/codeeducation

We should have the following result: Code.education Rocks!

Remembering that Go Lang has official images ready, it is worth checking the Docker Hub.

The image of our Go project needs to be less than 2MB =)


# Build 
```
docker build -t <seu-user>/codeeducation .
```

# Pull 
```
docker pull mrveloso/codeeducation
```

# Execute the container
```
docker run --rm mrveloso/codeeducation
```
