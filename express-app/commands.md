```
docker build -t express-app-1 -f Dockerfile.express-app .
```

```
docker run -p 8001:8000 -e PORT=8002 express-app-1
```

```
docker run -it express-app-1 /bin/bash
```