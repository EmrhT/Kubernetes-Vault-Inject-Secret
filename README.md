# Kubernetes Vault Inject Secret

A simple use-case with two tier (Flask and MySQL) web application with Vault on Kubernetes.

High available Vault cluster installed with Helm. values.yaml and override.values.yaml files added for reference. 
For detailed instructions on Vault installation --> https://developer.hashicorp.com/vault/tutorials/kubernetes/kubernetes-raft-deployment-guide

A secret will be injected to MySQL statefulset. yaml files are added for reference.

A more complete discussion on project is available on this medium post --> https://medium.com/@emrah-t/injecting-secrets-into-kubernetes-pods-with-hashicorp-vault-2b283a2e7379
