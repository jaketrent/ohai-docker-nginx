Simplest static site with nginx on Docker.

## Run

Build container:

```
docker build -t customweb .
```

Run container:

```
docker run -it --rm -d -p 8080:80 --name web2 customweb
```

See static site:

```
xdg-open localhost:8080
```

See running containers:

```
docker ps
```

Stop container:

```
docker stop web2
```
