# Anthos

Modernize existing applications and build cloud-native apps anywhere to promote agility and cost savings.


## GKE

Google Kubernetes Engine

Sits on top of VMWare VSphere in your environment

## Comparison of GKE, GKE on Prem, Kubernetes (K8s)

Differences between GKE, GKE on Prem and the open source Kubernetes.

These are container orchestration services and tools.

### Kubernetes

![](img/k8s-architecture-diagram.png)

### GKE

![](img/gke-architecture-diagram.png)

### GKE on Prem

![](img/gke-on-prem-architecture-diagram.png)

## GKE Hub

Automatically registers On-Prem clusters upon creation

Allows customers to interact with their On-Prem workloads from the Cloud Console

![](img/gke-hub-centralized-mgt-of-hybrid-multi-cloud-infra.png)

GKE on Prem makes an outbound TLS to Google Cloud Platorm

![](img/gke-hub-outbound-tls.png)

Overview

![](img/gcp-gke-on-prem.png)

## Istio Service Mesh

Benefits

![](img/istio-service-mesh-benefits.png)

Enabling Technology

![](img/istio-enabling-service.png)

Inserts a network proxy within the pod which captures inbound and outbound network connectivity.

Service Architecture

![](img/istio-service-architecture.png)

The proxy architecture allows for:

- Traffic encryption
- Enforce access policies on per pod basis, for example by limiting access of the Pictures pod only from the Frontend pod.

## References

- [Anthos](https://cloud.google.com/anthos)
- [An introduction to Anthos (Google Cloud Community Day ‘19)](https://youtu.be/42RmVrM7B7E)