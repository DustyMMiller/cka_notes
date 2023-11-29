# ETCD

Distributed key-value store

Listens on port 2379

ETCDCTL_API=3 .etcdctl version
export ETCDCTL_API=3

./etdctl <cmd>

Stores all cluster configs
    - Nodes
    - PODs
    - Configs
    - Secrets
    - Accounts
    - Roles
    - Bindings
    - etc.

Can be installed manually or run as a pod
In HA environment you can cluster ETCD
