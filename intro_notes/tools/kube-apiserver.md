## kube-api server

backend of kubectl
uses GET and POST requests

Responsible for:
    - Authentication
    - Validation
    - Retrieving data
    - Updating ETCD
    - Scheduling
    - Communicating with the Kubelet

Only component that interacts with ETCD store

Available as a binary that can be installed and run as a service

Important Components:
    etcd-cafile
    etcd-certfile
    etcd-keyfile
    kubelet-certificate-authority
    kubelet-client-certificate
    kubelet-client-key
    kubelet-https

Can be deployed as pod within kube-system namespace
Can be deployed as service
