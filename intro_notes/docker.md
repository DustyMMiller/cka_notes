docker vs containerd

CRI - Container Runtime Interface
OCI - Open Container Initiative
    - imagespec
    - runtimespec

dockershim introduced as a hack to run docker in CRI

can install containerd on its own

ctr - comes with containerd - solely for debugging containerd
nerdctl - docker-like cli for containerd (docker compose)
crictl - provides CLI for CRI compatible container runtimes
