# Kube Eye
Infrastructure-as-code (IaC) templates and configurations to deploy a Kubernetes cluster integrated with Istio and Open Policy Agent (OPA). It aims to enhance security, observability, and policy enforcement within a Kubernetes environment.


## Features:

- Kubernetes Cluster: Deploy a highly available and scalable Kubernetes cluster using Terraform and the managed Kubernetes service of your preferred cloud provider.

- Istio Integration: Install and configure Istio, an open-source service mesh, to manage traffic, enforce policies, and provide observability capabilities like distributed tracing and metrics.

- Open Policy Agent (OPA): Integrate OPA with Istio to enforce fine-grained authorization policies, allowing you to define and enforce access control rules across your microservices.

- Infrastructure-as-Code: Utilize Terraform to provision and manage the required cloud infrastructure resources, such as virtual machines, load balancers, and networking components.

- Continuous Integration and Deployment (CI/CD): Implement a CI/CD pipeline to automate the deployment of your Kubernetes cluster, Istio, and OPA, enabling rapid iteration and deployment.
