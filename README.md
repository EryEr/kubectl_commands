# kubectl_commands
Basic kubectl commands


**Cluster Information**:<br>
<br>
`kubectl cluster-info`: Display information about the cluster.<br>
`kubectl config view`: Display the content of the kubeconfig file.<be>
<br>
**Listing Resources**:<br>

`kubectl get nodes`: List all nodes.<br>
`kubectl get pods`: List all pods.<br>
`kubectl get services`: List all services.<br>
`kubectl get deployments`: List all deployments.<be>
<br>
**Resource Details**:<br>

`kubectl describe node <NODE_NAME>`: Display details of the specified node.<br>
`kubectl describe pod <POD_NAME>`: Display details of the specified pod.<be>
<br>
**Creating and Deleting Resources**:<br>

`kubectl create -f <FILENAME.yaml>`: Create the resource defined in the specified YAML file.<br>
`kubectl delete -f <FILENAME.yaml>`: Delete the resource defined in the specified YAML file.<be>
<br>
**Updating Resources**:<br>

`kubectl apply -f <FILENAME.yaml>`: Update or create the resource defined in the specified YAML file.<be>
<br>
**Logs and Terminal**:<br>

`kubectl logs <POD_NAME>`: Display logs of the specified pod.<br>
`kubectl exec -it <POD_NAME> -- /bin/sh`: Connect to the specified pod with an interactive terminal.<be>
<br>
**Output Formats**:<br>

`kubectl get pod <POD_NAME> -o yaml`: Display details of the specified pod in YAML format.<br>
`kubectl get pod <POD_NAME> -o json`: Display details of the specified pod in JSON format.<br>
