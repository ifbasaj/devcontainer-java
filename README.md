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


registry

```terminal
docker run -d -p 5000:5000 --restart=always --name registry registry:2
```

```terminal
docker run -d -p 5000:5000 --restart=always --name registry registry:2
```

```terminal
docker tag ifbasaj/java localhost:5000/ifbasaj/java
```

```terminal
docker push localhost:5000/ifbasaj/java
```

```terminal
```

