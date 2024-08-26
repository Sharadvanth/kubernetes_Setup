# Kubernetes Cluster Deployment with kubeadm

This repository contains files and instructions for deploying a Kubernetes cluster on virtual machines (VMs) using `kubeadm`. Follow the steps below to set up and manage your Kubernetes cluster.

## Prerequisites

- **Virtual Machines**: Ensure you have at least 2 VMs (one for the master node and one or more for worker nodes).
- **Operating System**: This guide assumes you are using a Linux-based OS (e.g., Ubuntu 20.04).
- **Root Privileges**: You need root or sudo access on all VMs.
- **Network**: Ensure that all VMs can communicate with each other over the network.
- **Docker**: Install Docker on all nodes.
- **kubeadm, kubelet, and kubectl**: Install these tools on all nodes.

## Setup Instructions

### 1. Preparation

- **Update Package Index**: Ensure that all nodes have the latest package lists.
  
  ```bash
  sudo apt-get update

- **Common Issues**: Check the [Kubernetes documentation](https://kubernetes.io/docs/setup/) for solutions to common setup issues.
- **Docker Issues**: For Docker-related issues, refer to the [Docker documentation](https://docs.docker.com/get-started/).
