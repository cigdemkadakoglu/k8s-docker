kubectl get ds -n kube-system


kubectl label node node_name app=node-collector-prod --overwrite


kubectl get po --all-namespaces -o wide 