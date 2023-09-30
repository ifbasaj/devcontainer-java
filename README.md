# devcontainer-java

Build

```terminal
docker build --pull --rm -f "Dockerfile" -t ifbasaj/java:20230930 "." 
docker build --pull --rm -f "Dockerfile" -t ifbasaj/java "." 
```

Run

```terminal
docker run -it ifbasaj/java bash
```
push

```terminal
docker push ifbasaj/java:20230930
docker push ifbasaj/java
```

[^registry]: https://docs.docker.com/registry/deploying/
