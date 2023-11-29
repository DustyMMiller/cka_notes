# ETCD

## version 2
etcdctl backup
etcdctl cluster-health
etcdctl mk
etcdctl mkdir
etcdctl set

## version 3
etcdctl snapshot save
etcdctl endpoint health
etcdctl get
etcdctl put

export ETCDCTL_API=3

add certs
```
--cacert /etc/kubernetes/pki/etcd/ca.crt
--cert /etc/kubernetes/pki/etcd.server.crt
--key /etc/kubernetes/pki/etcd/server.key
```

### Example command:
kubectl exec etcd-master -n kube-system -- sh -c \
"ETCDCTL_API=3 etcdctl get / --prefix --keys-only \
--limit=10 --cacert /etc/kubernetes/pki/etcd/ca.crt \
--cert /etc/kubernetes/pki/etcd/server.crt  --key \
/etc/kubernetes/pki/etcd/server.key"
