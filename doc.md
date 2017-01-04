```
docker build -f DockerfileBase -t polyaxon/base .
docker push polyaxon/base
```

```
docker build -f cpu/Dockerfile-1.1.0 -t polyaxon/polyaxon-1.1.0 .
docker push polyaxon/polyaxon-1.1.0
```

```
docker build -f cpu/Dockerfile-1.2.0 -t polyaxon/polyaxon-1.2.0 .
docker push polyaxon/polyaxon-1.2.0
```

```
docker build -f gpu/Dockerfile-1.1.0 -t polyaxon/polyaxon-gpu-1.1.0 .
docker push polyaxon/polyaxon-gpu-1.1.0
```

```
docker build -f gpu/Dockerfile-1.2.0 -t polyaxon/polyaxon-gpu-1.2.0 .
docker push polyaxon/polyaxon-gpu-1.2.0
```
