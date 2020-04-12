# Dorker
Fedora Docker with all my commonly used dev tools installed

### Starting the container

```
docker run -it\
  -v $HOME/.ssh:/root/.ssh\
  -v $HOME/workspace:/workspace\
  -v $HOME/.aws:/root/.aws\
  -v /var/run/docker.sock:/var/run/docker.sock\
  -h fedora_docker\
  abhi56rai/dorker:latest
```
