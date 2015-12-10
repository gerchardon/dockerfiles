# Counter

Python app to count an redis server

## Usage

```
docker run -d --name redis redis
docker run -d -p 5000:5000 --link redis:redis gerchardon/counter
```

Inspire by : https://github.com/docker/docker/blob/v1.8.3/experimental/compose_swarm_networking.md
