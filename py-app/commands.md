```
docker build -t py-app-1 -f Dockerfile.py-app .
```

```
docker run -p 8001:8000 -t py-app-1
```

```
docker run -it py-app-1 /bin/bash
```