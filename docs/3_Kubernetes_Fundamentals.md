# Kubernetes Fundamentals

Study Tips Count: 20 (Fundamentals + Deep Dive)

## Topics

### General

Kubernetes (https://kubernetes.io/)

kubectl (https://kubernetes.io/docs/reference/kubectl/)

```
 kubectl [command] [TYPE] [NAME] [flags]

command: Specifies the operation that you want to perform on one or more resources, for example create, get, describe, delete.
TYPE: Specifies the resource type. 
```

### [Container Orchestration](https://github.com/gocklkatz/screenshots/blob/main/kcna/docs/3_Kubernetes_Fundamentals.md#container-orchestration)

### [Kubernetes Architecture](https://github.com/gocklkatz/screenshots/blob/main/kcna/docs/3_Kubernetes_Fundamentals.md#kubernetes-architecture)

### [Kubernetes Pods](https://github.com/gocklkatz/screenshots/blob/main/kcna/docs/3_Kubernetes_Fundamentals.md#kubernetes-pods)

### [Kubernetes Namespaces](https://github.com/gocklkatz/screenshots/blob/main/kcna/docs/3_Kubernetes_Fundamentals.md#kubernetes-namespaces)

### [Kubernetes Deployments and ReplicaSets](https://github.com/gocklkatz/screenshots/blob/main/kcna/docs/3_Kubernetes_Fundamentals.md#kubernetes-deployments-and-replicasets)

kubectl create deployment

```
 kubectl create deployment nginx --image=nginx
```

kubectl get deployment

kubectl get replicaset

kubectl get pods

kubectl rollout history

kubectl annote

kubectl scale
