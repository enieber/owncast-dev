# owncast-dev

config owcast to run in nix-shell

## Run in docker

How to run in docker:

```sh
docker run -v `pwd`/data:/app/data -p 8080:8080 -p 1935:1935 -it gabekangas/owncast:latest
```
