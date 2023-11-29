# Intro Notes

## Architecture

 - Cargo Ship:
    - Worker nodes
    - Host applications as containers
    - Captain - kubelet
    - Kube-proxy service
 - Control Ships:
    - Controller Nodes
    - manage, plane, schedule, monitor nodes
    - "controlplane"
    - key value store - ETCD

Control Plane Components:
    kube-apiserver
    Kube-scheduler
    ETCD
    Node-Controller
    Replication-Controller
    Controller-Manager

Kubelet
Kube-proxy server
