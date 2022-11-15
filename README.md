# cluster-api-headstart
Cluster API - Headstart

Based on "Cluster API" at https://github.com/kubernetes-sigs/cluster-api

Based on "10 New DevOps Tools to Watch in 2023" at https://medium.com/4th-coffee/10-new-devops-tools-to-watch-in-2023-e974dbb1f1bb

## 100 - Introduction

Cluster API is a Kubernetes sub-project focused on providing declarative APIs and tooling to simplify provisioning, upgrading, and operating multiple Kubernetes clusters.

Started by the Kubernetes Special Interest Group (SIG) Cluster Lifecycle, the Cluster API project uses Kubernetes-style APIs and patterns to automate cluster lifecycle management for platform operators. The supporting infrastructure, like virtual machines, networks, load balancers, and VPCs, as well as the Kubernetes cluster configuration are all defined in the same way that application developers operate deploying and managing their workloads. This enables consistent and repeatable cluster deployments across a wide variety of infrastructure environments.

If the official definition baffles you, think this: you can run one kubectl apply command to create a K8s cluster, and it works for AWS, Azure, DigitalOcean, Docker, GCP, OpenStack, and more.

No need for creating Terraform modules (or worse, trying to figure out all the parameters of somebody else’s modules) for K8s clusters, no need to figure out how to use eksctl for AWS and something else for another cloud; simply kubectl apply to create clusters. Sounds impressive, right? I know. That’s why it’s on the top-10-tools-to-watch list.
