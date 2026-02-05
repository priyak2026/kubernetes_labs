# Kubernetes Hands-On Labs

This repository contains practical Kubernetes labs completed to demonstrate understanding of core Kubernetes concepts through YAML configuration files and kubectl commands.

These labs were performed in a hands-on lab environment to practice real Kubernetes resource creation, management, and troubleshooting.

---

## Objectives

- Understand Kubernetes architecture and objects
- Practice creating resources using YAML manifests
- Manage deployments, replicas, and services
- Perform rolling updates without downtime
- Use kubectl to inspect and manage cluster state

---

## Labs Included

### 🟢 Pod Creation
- Created Pods using YAML files
- Verified Pod status and logs
- Observed Pod lifecycle behavior

### 🟢 ReplicaSets
- Created ReplicaSets to maintain multiple Pod replicas
- Tested self-healing when Pods were deleted

### 🟢 Deployments
- Created Deployments to manage ReplicaSets
- Updated container images using rolling updates
- Performed rollout history checks and rollbacks

### 🟢 Services
- Exposed applications using ClusterIP Services
- Verified service connectivity within the cluster

### 🟢 Rolling Updates
- Updated application versions with zero downtime
- Observed how Kubernetes handles rolling updates

---

## Tools & Technologies

- Kubernetes
- YAML
- kubectl
- Docker images
- Git & GitHub

---

## What This Project Demonstrates

This project shows practical, hands-on experience with:

- Writing Kubernetes YAML manifests
- Managing application deployments
- Understanding Kubernetes networking and scaling
- Performing safe application updates in a cluster

This work represents foundational Kubernetes skills expected from a DevOps Engineer.
