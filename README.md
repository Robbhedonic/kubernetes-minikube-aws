# Kubernetes Hands-On

This repository contains practical Kubernetes examples organized by topic, including YAML manifests for Pods, Deployments, Services, ConfigMaps, Secrets, Namespaces, Resource Quotas, Limits, Probes, and more.

## Contents

- ConfigMaps and configuration examples
- Deployments and ReplicaSets
- Services and application exposure
- CPU and memory resource limits
- Namespaces and environments
- Health probes and container management
- Environment variable examples

## Requirements

- Kubernetes installed and configured
- kubectl available
- A local or remote cluster accessible

## Usage

Apply a manifest:

```bash
kubectl apply -f <file.yaml>
```

Verify resources:

```bash
kubectl get pods
kubectl get svc
kubectl get deployments
```

Delete a resource:

```bash
kubectl delete -f <file.yaml>
```

## Purpose

This repository serves as study material for learning Kubernetes in a practical way, using simple and organized examples.

## Author

Ricardo / Robbhedonic
