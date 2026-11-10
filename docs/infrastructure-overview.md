# Kubernetes Infrastructure Overview

## Project

Three-node Kubernetes cluster built using VMware and AlmaLinux.

## Architecture

| Node | Role | CPU | RAM |
|---|---|---:|---:|
| Control | Control Plane | 2 vCPU | 3.5 GiB |
| Worker 1 | Application Worker | 2 vCPU | 2.6 GiB |
| Worker 2 | Database Worker | 2 vCPU | 2.6 GiB |

## Platform

- Operating System: AlmaLinux 9.8
- Kubernetes: v1.35.10
- Container Runtime: containerd 2.4.2
- CNI: Flannel
- Package Management: Helm
- Ingress Controller: Traefik
- Kubernetes Dashboard: Headlamp

## Installed Components

| Component | Purpose |
|---|---|
| Flannel | Pod networking |
| Traefik | Ingress traffic management |
| Headlamp | Kubernetes dashboard |
| NGINX | Application workload |
| Helm | Kubernetes package management |

## Namespaces

- app-lab
- headlamp
- traefik
- kube-system
- kube-flannel

## Learning and DevOps Activities

- Kubernetes cluster administration
- Worker node management
- Deployments and Services
- NodePort networking
- Ingress configuration
- TLS and HTTPS
- Traefik middleware
- Helm deployment
- Git and GitHub integration
- Infrastructure inventory automation

## Repository Purpose

This repository documents a practical Kubernetes and DevOps learning lab.
It is intended for educational and portfolio purposes.

Internal IP addresses, SSH credentials, private keys and raw infrastructure
inventory are intentionally excluded.
