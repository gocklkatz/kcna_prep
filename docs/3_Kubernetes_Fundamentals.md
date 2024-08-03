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

-i, --stdin
Keep stdin open on the container in the pod, even if nothing is attached.

-t, --tty
Allocate a TTY for the container in the pod.

--rm
If true, delete the pod after it exits. Only valid when attaching to the container, e.g. with '--attach' or with '-i/--stdin'.

--restart string     Default: "Always"
The restart policy for this Pod. Legal values [Always, OnFailure, Never].
```

[kubectl get](https://kubernetes.io/docs/reference/kubectl/generated/kubectl_get/)

```
Display one or many resources
kubectl get [(-o|--output=)json|yaml|name|go-template|go-template-file|template|templatefile|jsonpath|jsonpath-as-json|jsonpath-file|custom-columns|custom-columns-file|wide] (TYPE[.VERSION][.GROUP] [NAME | -l label] | TYPE[.VERSION][.GROUP]/NAME ...) [flags]
```

[kubectl logs](https://kubernetes.io/docs/reference/kubectl/generated/kubectl_logs/)

```
Print the logs for a container in a pod or specified resource. If the pod has only one container, the container name is optional.
kubectl logs [-f] [-p] (POD | TYPE/NAME) [-c CONTAINER]
```

[kubectl port-forward](https://kubernetes.io/docs/reference/kubectl/generated/kubectl_port-forward/)

```
Forward one or more local ports to a pod.
kubectl port-forward TYPE/NAME [options] [LOCAL_PORT:]REMOTE_PORT [...[LOCAL_PORT_N:]REMOTE_PORT_N]
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
