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

## Anthos vs AWS Azure Hybrid Clouds

### [How Google’s Anthos Is Different from AWS and Azure Hybrid Clouds](https://www.datacenterknowledge.com/google-alphabet/how-google-s-anthos-different-aws-and-azure-hybrid-clouds)

> Google takes a fundamentally different approach to the on-prem portion of hybrid cloud.

> Paul Ferrill | Apr 26, 2019

> As the cornerstone of Google's hybrid cloud offering, GKE On-Prem offers customers multiple options for modernizing legacy applications stuck on old hardware. Workload portability, or enabling applications to run anywhere, is the ultimate goal. GKE On-Prem makes it possible to build and run applications when you need to keep the data inhouse or you don't want to move large amounts of data to the cloud.

> Google's approach here is different from Amazon’s or Microsoft’s in in that GKE On-Prem runs on top of VMware vSphere. Everything runs on customer hardware with support for all the mainstream VMware OEMs, including Cisco, Dell/EMC, HPE, and Lenovo. This approach caters to the large number of existing VMware customers and keeps the familiar management and operating environment already in place.

> ....

> Microsoft's answer to the integrated on-premises and cloud development story is to go with an Azure Stack system. Similarly, the folks at Amazon want you to buy their hardware and run a clone of AWS in your data center. Google thinks you can get what you need by running on top of VMware vSphere on existing hardware at significantly lower cost than either AWS or Microsoft.

### [Compare hybrid clouds: AWS Outposts vs. Azure Stack vs. Google Anthos](https://searchcloudcomputing.techtarget.com/tip/Compare-hybrid-clouds-AWS-Outposts-vs-Azure-Stack-vs-Google-Anthos)

> Azure Stack, AWS Outposts and Google Anthos all have similar objectives but operate in different ways. Find out which hybrid cloud platform offers the right model for your company.
>
> Chris Tozzi, Fixate IO
> Published: 15 Jul 2020
>
> Azure Stack, AWS Outposts and Google Anthos are the Big Three's response to modern hybrid cloud computing needs. While they all share some core functionality and aim to synchronize cloud with on-premises deployments, each service differs when it comes to vendor lock-in considerations, hardware compatibility, supported cloud services and more.

### [Amazon API Gateway vs Apigee](https://stackshare.io/stackups/amazon-api-gateway-vs-apigee)

> Amazon API Gateway and Apigee can be categorized as "API" tools.
> 
> Some of the features offered by Amazon API Gateway are:
> 
> - Build, Deploy and Manage APIs
> - Resiliency
> - API Lifecycle Management
> 
> On the other hand, Apigee provides the following key features:
> 
> - Design, secure, analyze, and scale your APIs with the Apigee Edge API > management platform.
> - Predictive analytics to ensure intelligent and customized interactions.
> - Connect devices to the Internet, and enable partners and developers to access > device functionality and data with APIs.


### [AWS Outposts vs Google Anthos](https://stackshare.io/stackups/aws-outposts-vs-google-anthos)

> What is AWS Outposts? Run AWS infrastructure and services on premises for a truly consistent hybrid experience. It is a fully managed service that extends AWS infrastructure, AWS services, APIs, and tools to virtually any datacenter, co-location space, or on-premises facility for a truly consistent hybrid experience. AWS Outposts is ideal for workloads that require low latency access to on-premises systems, local data processing, or local data storage.
> 
> What is Google Anthos? Bringing the Google Cloud to you. Formerly Cloud Services Platform, Anthos lets you build and manage modern hybrid applications across environments. Powered by Kubernetes and other industry-leading open-source technologies from Google.
> 
> AWS Outposts and Google Anthos can be primarily classified as "Hybrid Cloud as a Service" tools.
> 
> Some of the features offered by AWS Outposts are:
> 
> - VPC extension
> - Local gateway
> - Access regional services
> 
> On the other hand, Google Anthos provides the following key features:
> 
> - Google Kubernetes Engine Support
> - GKE On-Prem Support
> - Istio on GKE Support

### [The major hybrid cloud options compared: AWS Outposts vs Azure Stack vs Google Anthos](https://www.computerworld.com/article/3428108/the-major-hybrid-cloud-options-compared-aws-outposts-vs-azure-stack-vs-google-anthos.html)

> We compare the hybrid cloud solutions from the big three public cloud providers and beyond
> 
> By Scott Carey
>
> UK Group Editor, Computerworld | NOV 6, 2019 2:52 AM PST
> 
> Now that all of the major public cloud providers have a clearly defined hybrid cloud solution on the market we can start to compare the different approaches from Amazon Web Services (AWS), Microsoft Azure and Google Cloud.
> 
> Hybrid cloud is an enterprise IT strategy that involves operating certain workloads across different infrastructure environments, be it one of the major public cloud providers, a private cloud, or on-premise, typically with a homegrown orchestration layer on top. Multi-cloud is a similar idea but tends to not involve private cloud or on-premise infrastructure.
> 
> This approach is particularly important to organisations with certain applications that will need to remain on-premise for the time being, such as low-latency applications on a factory floor, or those with data residency concerns.

## References

- [Anthos](https://cloud.google.com/anthos)
- [An introduction to Anthos (Google Cloud Community Day ‘19)](https://youtu.be/42RmVrM7B7E)