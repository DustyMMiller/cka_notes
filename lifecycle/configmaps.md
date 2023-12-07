## ConfigMaps

Imperative
  kubectl create configmap app-config --from-literal=<key>=<value>
  can be done multiple times
  kubectl create configmap app-config --from-file=<file>

  envFrom:
    - configMapRef:
        name: <name>


