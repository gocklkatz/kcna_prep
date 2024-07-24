# Kubernetes Fundamentals

Study Tips Count: 20 (Fundamentals + Deep Dive)

## Learning Objectives

- Discuss the basic architecture of Kubernetes
- Explain the different components of control plane and worker nodes
- Understand how to get started with the Kubernetes setup
- Discuss how Kubernetes is running containers
- Discuss the scheduling concepts of Kubernetes
- Explain what a Kubernetes object is and how to describe it
- Discuss the Pod concept and the problems it solves
- Understand how to scale and schedule Pods with workload resources
- Understand how to abstract Pods with services and how to expose them

## Topics

## Container Orchestration

> Understand the problems that Container Orchestration resolves

- How to handle lots (100, 1k, 10k, ...) of containers?
- How do we run containers at scale? <br/>
  -> **Container Orchestrator**
- Provisioning, deployment, scaling and more. Standards and frameworks. Integration with core components.
- Provisioning and deployment of containers. Container availablility and self healing. Scheduling and the effective use of compute resources. Exposing container services. Authorisation and security. Storage for shared/persistent workloads. Autoscaling. Extended Functionality (CRD's)
- Products: Openshift, Docker swarm, HashiCorp Nomad, **Kubernetes**

### Kubernetes General

> Kubernetes, also known as K8s, is an open source system for automating deployment, scaling, and management of containerized applications. [Kubernetes Website](https://kubernetes.io/)

### Kubernetes Architecture

> - The role of the kubelet and how it interacts with the CRI (Container Runtime Interface)
> - The role of the kube-scheduler
> - The role of the kube-proxy
> - The role of the kubeapi-server
> - The role of etcd
> - Container Runtimes and the differences between high leel and low level runtimes
> - The hierarchy of Kubernetes components - From Cluster to Node to Pod to Container
> - What is the CCM (Cloud Controller Manager) ad where this would reside in K8s

- control plane (major/system components), nodes (workload)
- **Low level container runtime** (runc, reference implementation, donated by Docker to OCI), spawning and running containers, interacts with low level linux components like namespaces and cgroups, alternatives to runc: crun, kata-runtime, gVisor

### Kubernetes Pods

### Kubernetes Namespaces

### Kubernetes Deployments and ReplicaSets

### Kubernetes Services

### Kubernetes Jobs

### Kubernetes ConfigMaps

### Kubernetes Secrets

### Kubernetes Labels

### Kubernetes API

### Kubernetes RBAC

### Kubernetes Scheduling and NodeName

### Kubernetes Storage

### Kubernetes StatefulSets

### Kubernetes NetworkPolicies

### Kubernetes Pod Disruption Budgets

### Kubernetes Security

### Helm and Helm Charts

### Service Meshes