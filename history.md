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

```bash1  kind create cluster --name=swap-clu --comfig=config.yml
    2  kind create cluster --name=swap-clu --config=config.yml
    3  cat config.yml 
    4  kubectl get nodes
    5  kubectl get node
    6  vim deployement.yml
    7  kubectl apply -f deployement.yml 
    8  vim deployement.yml 
    9  kubectl apply -f deployement.yml 
   10  vim deployement.yml 
   11  kubectl apply -f deployement.yml 
   12  vim deployement.yml 
   13  kubectl apply -f deployement.yml 
   14  vim deployement.yml 
   15  kubectl apply -f deployement.yml 
   16  vim deployement.yml 
   17  kubectl apply -f deployement.yml 
   18  kubectl apply -f namespeac.yml 
   19  kubectl apply -f deployement.yml 
   20  kubectl get pods
   21  kubectl get pods -n nginx
   22  kubectl scale deployment nginx-deployment --replicas=4 -n nginx
   23  kubectl get pods -n nginx
   24  kubectl get pods -o wide -n nginx
   25  kubectl scale deployment nginx-deployment --replicas=10 -n nginx
   26  kubectl get pods -n nginx
   27  kubectl get pods -o wide -n nginx
   28  kubectl scale deployment nginx-deployment --replicas=1 -n nginx
   29  kubectl get pods -o wide -n nginx
   30  kubectl scale deployment nginx-deployment --replicas=4 -n nginx
   31  kubectl get pods -o wide -n nginx
   32  kubectl set image deploy/nginx-deployment nginx=nginx:1.25 -n nginx
   33  kubectl get pods -o wide -n nginx
   34  kubectl describe pod nginx-deployment-6f66f85776-fw9nv
   35  kubectl get pods
   36  kubectl get pods -n naginx
   37  kubectl get pods -o wide -n nginx
   38  kubectl get pods -n nginx
   39  kubectl describe pod nginx-deployment-6f66f85776-fw9nv -n nginx
   40  kubectl rollout undo deployment nginx-deployment -n nginx
   41  kubectl get pods -o wide -n nginx
   42  kubectl describe pod nginx-deployment-96b9d695-5hbjs -n nginx
   43  kubectl delete deployement.yml 
   44  kubectl delete deployment nginx-deployment -n nginx
   45  kubectl get pods
   46  kubectl get pods -n nginx
```
Deployment.yml cmd
