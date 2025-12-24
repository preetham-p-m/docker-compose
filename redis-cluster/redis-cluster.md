# Redis cluster

- Create cluster

```sh
docker exec -it redis8-node-1 redis-cli --cluster create redis8-node-1:7001 redis8-node-2:7002 redis8-node-3:7003  --cluster-replicas 0
```

- Verify

```sh
docker exec -it redis8-node-1 redis-cli -p 7001 cluster info
```
