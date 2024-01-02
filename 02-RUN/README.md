**RUN**: Executes commands in a new layer on top of the current image and commits the results. For instance,
```docker
FROM ubuntu:latest
RUN apt-get update && apt-get install -y git 
```
installs Git in the image.

---