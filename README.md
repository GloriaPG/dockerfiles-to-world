# dockerfiles-to-world
They are my Dockerfiles

# How to build image?
```{r, engine='bash', count_lines}
$ docker build --tag=myuser/myimage:1.0 /path/to/dockerfile
```

# How to push my image to private or public registry?
```{r, engine='bash', count_lines}
$ docker login -u user ip-or-domain-registry:port
$ docker push ip-or-domain-registry:port/myuser/myimage:1.0
```

