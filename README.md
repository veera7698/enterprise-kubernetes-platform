# Enterprise Kubernetes Platform

A production-grade Kubernetes Platform built on AWS using Infrastructure as Code, GitOps, CI/CD, and enterprise monitoring.

---

## Project Goal

This repository demonstrates how modern companies build and operate Kubernetes platforms using production-ready DevOps practices.

The platform provisions AWS infrastructure with Terraform, deploys Amazon EKS, manages applications using GitOps with Argo CD, automates deployments using GitHub Actions, and provides complete monitoring with Prometheus and Grafana.

This project is intended as a portfolio showcasing Platform Engineering and DevOps skills.

---

# Architecture

Developer
      │
      ▼
GitHub Repository
      │
GitHub Actions
      │
Terraform
      │
AWS Infrastructure
      │
Amazon EKS
      │
Argo CD
      │
Helm Charts
      │
Applications
      │
NGINX Ingress
      │
Users

Monitoring

Prometheus
Grafana
Alertmanager

---

# Technology Stack

| Category | Technology |
|-----------|------------|
| Cloud | AWS |
| Infrastructure | Terraform |
| Containers | Docker |
| Orchestration | Kubernetes (Amazon EKS) |
| GitOps | Argo CD |
| Package Manager | Helm |
| CI/CD | GitHub Actions |
| Ingress | NGINX Ingress Controller |
| Monitoring | Prometheus |
| Dashboard | Grafana |
| Logging | Fluent Bit |
| DNS | Route53 |
| Certificates | cert-manager |
| Secrets | Kubernetes Secrets |

---

# Features

- Infrastructure as Code
- Multi-environment support
- Production-ready EKS Cluster
- GitOps Deployment
- Automated CI/CD
- Helm-based application deployment
- Kubernetes RBAC
- Monitoring
- Alerting
- HTTPS with TLS
- Autoscaling
- Rolling Updates
- Zero Downtime Deployment
- Namespace Isolation
- Ingress Controller
- Production folder structure

---

# Folder Structure

```
enterprise-kubernetes-platform/

├── terraform/
├── kubernetes/
├── helm/
├── argocd/
├── github-actions/
├── monitoring/
├── scripts/
├── docs/
└── README.md
```

---

# Deployment Workflow

1. Terraform provisions AWS infrastructure.
2. Amazon EKS cluster is created.
3. GitHub Actions builds Docker images.
4. Images are pushed to container registry.
5. Argo CD detects Git changes.
6. Helm deploys applications.
7. Prometheus monitors the cluster.
8. Grafana visualizes metrics.

---

# Skills Demonstrated

- AWS
- Terraform
- Kubernetes
- Docker
- Helm
- GitOps
- Argo CD
- GitHub Actions
- Platform Engineering
- Infrastructure as Code
- Monitoring
- Cloud Security
- CI/CD
- Production DevOps

---

# Future Enhancements

- Crossplane
- Service Mesh
- External Secrets
- Vault Integration
- Cluster Autoscaler
- Karpenter
- Multi-region deployment
- Disaster Recovery
- Cost Optimization

---

# Learning Outcomes

This project demonstrates the implementation of an enterprise-grade Kubernetes platform with automated infrastructure provisioning, GitOps-driven deployments, continuous integration, monitoring, and production-ready operational practices.

---

# Author

Veera Mani
DevOps Engineer
Tamil Nadu, India
