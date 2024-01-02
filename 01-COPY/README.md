**CMD**: Provides a default command to run when a container starts from the image. There can only be one CMD instruction in a Dockerfile. If you specify more than one CMD, only the last CMD will take effect.
```docker
FROM ubuntu:latest
CMD echo "Hello World!"
``` 

---