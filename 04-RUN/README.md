**RUN**: Executes commands in a new layer on top of the current image and commits the results. So if you have dependencies, tools, libraries, this is where you would use `RUN` that you want to install as part of your base image,  For instance,
```docker
RUN apt-get update && apt-get install -y git 
```
installs Git in the image.

---