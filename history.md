# Kubernetes & Kind Command History

This document records the complete command history and learning steps while
working with **Kind (Kubernetes in Docker)**, namespaces, pods, and GitHub.

---

## Cluster & Namespace Checks

```bash
kubectl get ns
1  kubectl get ns
    2  config.yml
    3  vim config.yml
    4  kubectl create cluster --name swapnil-cluster --config=config.yml
    5  kubectl create cluster --name=swapnil-cluster --config=config.yml
    6  kind create cluster --name=swapnil-cluster --config=config.yml
    7  kind cluster delete swapnil-cluster
    8  kind delete cluster --name swapnil-cluster
    9  kubectl get ns
   10  vim config.yml 
   11  kind create cluster --name=swapnil-cluster --config=config.yml
   12  kubectl get ns
   13  kubectl get nodes
   14  kubectl get posds
   15  kubectl get pods
   16  kubectl run nginx --image=ngin
   17  kubectl run nginx --image=nginx
   18  kubectl delete pod nginx
   19  kubectl run nginx --image=nginx
   20  kubectl get pods
   21  kubectl create ns nginxx
   22  kubectl get ns
   23  kubectl run nginx --image=nginx -n nginxx
   24  kubectl get ns -n nginxx
   25  kubectl get pod -n nginxx
   26  kubectl get pods
   27  kubectl delete pos nginx -n nginxx
   28  kubectl delete pod nginx -n nginxx
   29  kubectl get pods 
   30  kubectl get pod -n nginxx
   31  ls
   32  git
   33  vim install.sh
   34  chmod +x install.sh 
   35  ./install.sh 
   36  sudo usermod -aG docker $USER
   37  newgrp docker
   38  kubectl get pods
   39  kubectl get pod

```
