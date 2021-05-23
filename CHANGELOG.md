# Changelog

## [0.0.1] - 2021-05-22

Created a new cluster in **minikube** by running this...

`minikube start -p <name_of_new_cluster>`

Good to note that the `-p` option is also used for other cluster data retrieval.

`minikube status -p <name_of_new_cluster>`

Created a dir for namespaces and a config file for the `reverse-proxy` namespace. 

Applied the configuration and verified the namespace exists.

`kubectl get namespaces`

- [namespaces dir](./namespaces/)

