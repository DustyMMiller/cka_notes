## Static Pods

Put kubernetes yaml files in a specified folder
Kubelet will create the pods from the files

in Kubelet config
kubelet.service
--pod-manifest-path 
--config
staticPodPath in kubeconfig.yaml

Can be used to deploy control plane components
