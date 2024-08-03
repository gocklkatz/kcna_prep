# Kubernetes Fundamentals

Study Tips Count: 20 (Fundamentals + Deep Dive)

## Topics

### General

Kubernetes (https://kubernetes.io/)

```
Kubernetes, also known as K8s, is an open source system for automating deployment, scaling, and management of containerized applications.
```

kubectl (https://kubernetes.io/docs/reference/kubectl/)

```
 kubectl [command] [TYPE] [NAME] [flags]

command: Specifies the operation that you want to perform on one or more resources, for example create, get, describe, delete.
TYPE: Specifies the resource type. 
```

k3s (https://k3s.io/)

```
The certified Kubernetes distribution built for IoT & Edge computing
```

### kubectl commands

[kubectl run](https://kubernetes.io/docs/reference/kubectl/generated/kubectl_run/)

```
Create and run a particular image in a pod.
kubectl run NAME --image=image [--env="key=value"] [--port=port] [--dry-run=server|client] [--overrides=inline-json] [--command] -- [COMMAND] [args...]
```

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
