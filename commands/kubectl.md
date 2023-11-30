## Kubectl

### Pods (po)
kubectl run <name> --image <image_name>
kubectl get pod <name>
kubectl describe pod <name>
kubectl create -f <file_path.yaml>

### ReplicaSets (rs)
kubectl get replicaset
kubectl replace -f <file_path.yaml>
kubectl scale --replicas=<number> -f <file_path.yaml>
kubectl scale --replicas=<number> replicaset <name>

### Deployments (deploy)
kubectl get deployment



Short name 	Full name
csr       	certificatesigningrequests
cs 	componentstatuses
cm 	configmaps
ds 	daemonsets
deploy 	deployments
ep 	endpoints
ev 	events
hpa       	horizontalpodautoscalers
ing 	ingresses
limits 	limitranges
ns 	namespaces
no 	nodes
pvc 	persistentvolumeclaims
pv 	persistentvolumes
po 	pods
pdb 	poddisruptionbudgets
psp 	podsecuritypolicies
rs 	replicasets
rc 	replicationcontrollers
quota 	resourcequotas
sa 	serviceaccounts
svc 	services
