```bash
make
docker build -t example-scratch .
docker run -it example-scratch
```

Sources:

- https://blog.codeship.com/building-minimal-docker-containers-for-go-applications/
- https://docs.travis-ci.com/user/docker/