# Kubernetes Fundamentals

Study Tips Count: 22 (Fundamentals + Deep Dive)

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

## Container Orchestration (U)

> Understand the problems that Container Orchestration resolves

- How to handle lots (100, 1k, 10k, ...) of containers?
- How do we run containers at scale? -> Container Orchestrator
- Provisioning, deployment, scaling and more. Standards and frameworks. Integration with core components.
- Provisioning and deployment of containers. Container availablility and self healing. Scheduling and the effective use of compute resources. Exposing container services. Authorisation and security. Storage for shared/persistent workloads. Autoscaling. Extended Functionality (CRD's)
- Products: Openshift, Docker swarm, HashiCorp Nomad, Kubernetes

### Kubernetes General (C)

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



### Kubernetes Setup

### Kubernetes API

### Running Containers on Kubernetes

### Networking

### Scheduling

### Kubernetes Objects

### Interacting with Kubernetes

### Pod Concept

### Pod Lifecycle

### Worload Objects

### Networking Objects

### Volume & Storage Objects

### Configuration Objects

### Autoscaling Objects

### Scheudling Objects

### Kubernetes Security