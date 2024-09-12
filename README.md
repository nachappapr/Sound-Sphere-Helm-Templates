# Sound-Sphere-Helm-Templates

This repository contains Helm charts for deploying various Sound-Sphere microservices, including authentication, product management, inventory, and more, to Kubernetes clusters.

## Microservices

- **auth**: Authentication service
- **product**: Product management service
- **inventory**: Inventory management service
- **other**: Additional microservices for Sound-Sphere

## Prerequisites

- [Helm](https://helm.sh/docs/intro/install/) installed on your local machine
- Access to a Kubernetes cluster

## Installation

### Add Helm Repository

First, add the Helm repository:

```sh
helm repo add sound-sphere https://your-helm-repo-url
helm repo update
