## Resource Requirements and Limits

Scheduler will automatically avoid scheduling on nodes that don't have enough resources

resources:
    requests:
        memory: "4Gi"
        cpu: 2
    limits:
        memory: "5Gi"
        cpu: 3

Pods will throttle CPU when it hits a limit
Pods will not throttle memory, may end up being OOM killed

If requests is not specified it will be set as same as limit

Use LimitRange (at namespace level) to define default requests and limits
