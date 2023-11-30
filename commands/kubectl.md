## Kubectl

### Pods
kubectl run <name> --image <image_name>
kubectl get pod <name>
kubectl describe pod <name>
kubectl create -f <file_path.yaml>

### ReplicaSets
kubectl get replicaset
kubectl replace -f <file_path.yaml>
kubectl scale --replicas=<number> -f <file_path.yaml>
kubectl scale --replicas=<number> replicaset <name>

