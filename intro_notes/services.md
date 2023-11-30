## Services

Connect applications with other applications and users
Can act as built in load balancer

### Types
    - NodePort
        - Port - on service
        - TargetPort - on Pod
        - NodePort - external port (30000-32767)
        - Assumed targetPort is same as port if not provided
        - Will assign nodePort if not provided
    - ClusterIP
        - Assigns IP to a available for other pods to access
    - LoadBalancer
        - Loadbalances between all nodes for NodePorts
        - Integrates with some supported cloud platforms
