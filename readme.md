# ArgoCD Exploration

## Setup 
Start a cluster 
```
k3d cluster create argocd-test
```
and install argocd 
```
kubectl create namespace argocd
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/core-install.yaml
```
This will only install ArgoCD core. If you want to install the complete setup use `install.yaml` instead.  

More information can be found in the Getting Started Section in the ArgoCD documentation.  
https://argo-cd.readthedocs.io/en/stable/getting_started/
