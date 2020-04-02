```bash
# screencapture (capture images from screen)

# Take screenshot & save it to Desktop with current date as name
screencapture -ixoa -t jpg ~/"Desktop/$(date).jpg"
```

```bash
# docker (run processes in isolated containers)

# Delete all containers
for i in $(docker ps -a -q); do docker rm $i; done

# List all containers
docker ps -a

# Remove a container after it’s stopped
docker run --rm [...]
```

```bash
# kubectl (run commands against Kubernetes clusters)

# Get info on pods in use. Has info on why they failed if they did.
kubectl describe pods

# Get services across all namespaces
kubectl get svc --all-namespaces

# Port forward the <pod> from 5432 to localhost 5300 port
kubectl port-forward <pod> 5300:5432
```
