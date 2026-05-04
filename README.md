
![Cluster Architecture](assets/CKA.jpg)

<h1 align="center">✨ Kubernetes Course Summary ✨</h1>

<p align="center">
A concise and practical DevOps-focused knowledge base covering <strong>CKA</strong>, <strong>Helm</strong>, and <strong>Istio Service Mesh</strong>, based on <a href="https://kodekloud.com/">KodeKloud</a>.
It provides a structured and easy-to-navigate reference for Kubernetes administration, application deployment with Helm, and advanced traffic management and observability using Istio.
</p>


 > ⚠️ **Important:** The PDF version of this course summary contains **all concepts in full detail** and is highly recommended for comprehensive study.

  
</p>

<p align="center">
  <a href="./CKA%20Course%20Summary.pdf"><img src="https://img.shields.io/badge/Download-PDF-orange?style=for-the-badge&logo=adobeacrobatreader" /></a>
  <a href="https://kubernetes.io/docs/"><img src="https://img.shields.io/badge/Kubernetes-Docs-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" /></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" /></a>
</p>

---

## 📑 Table of Contents
- [🌐 Core Concepts](#-core-concepts)
- [📦 Application Lifecycle Management](#-application-lifecycle-management)
- [🗂️ Scheduling](#️-scheduling)
- [📊 Logging & Monitoring](#-logging--monitoring)
- [🔐 Security](#-security)
- [🛠️ Cluster Maintenance](#️-cluster-maintenance)
- [💾 Storage](#-storage)
- [🌉 Networking](#-networking)
- [⚙️ Install K8s the Hard Way](#️-install-k8s-the-hard-way)
- [⚡ Install K8s with Kubeadm](#-install-k8s-with-kubeadm)
- [✅ End-to-End Tests](#-end-to-end-tests)
- [🩺 Troubleshooting](#-troubleshooting)
- [⭐ Important CKAD Topics](#-important-ckad-topics)
- [📚 Other Topics](#-other-topics)

---

## 🌐 Core Concepts
- Cluster Architecture  
- ETCD Basics & in Kubernetes  
- API Server, Controller Manager, Scheduler  
- Kubelet & Kube Proxy  
- Pods, ReplicaSets, Deployments  
- Namespaces & Resource Quotas  
- Services (ClusterIP, NodePort, LoadBalancer)  
- Imperative vs Declarative
  
![Cluster Architecture](assets/cluster%20arch.png)
---

## 📦 Application Lifecycle Management
- Rolling Updates & Rollbacks  
- Docker Entrypoint & CMD  
- Commands & Args in Kubernetes  
- Environment Variables  
- ConfigMaps & Secrets  
- Multi-Container Pods & Init Containers
  
![Rolling Update](assets/rolling%20update.png)

---

## 🗂️ Scheduling
- Manual Scheduling  
- Labels & Selectors  
- Taints, Tolerations & Affinity  
- Resource Requests & Limits  
- DaemonSets, Static Pods  
- Multiple Schedulers  

---

## 📊 Logging & Monitoring
- Monitoring Cluster Components  
- Checking Status & Logs  
- Managing Application Logs  

---

## 🔐 Security
- Authentication & TLS in Kubernetes  
- Certificates & API Access  
- RBAC (Roles, Bindings, ClusterRoles)  
- Security Contexts & Image Security  
- Network Policies  

---

## 🛠️ Cluster Maintenance
- Drain, Cordon, Uncordon  
- Upgrades & Versioning  
- Backup & Restore  

---

## 💾 Storage
- Docker Storage & Volume Drivers  
- Container Storage Interface (CSI)  
- Volumes, PVs & PVCs  

---

## 🌉 Networking
- Networking Basics (DNS, CNI, Docker)  
- Cluster & Pod Networking  
- CNI Plugins (Weave, Flannel, etc.)  
- Service Networking & CoreDNS  
- Ingress Controller
  
![K8s Networking](assets/k8s%20networking.png)

---

## ⚙️ Install K8s the Hard Way
- Cluster Design & HA  
- ETCD & Control Plane Setup  
- TLS Bootstrapping  
- Remote Access & Networking  
- Deploying CoreDNS  

---

## ⚡ Install K8s with Kubeadm
- Quick setup with Kubeadm  
- Demo deployment  

---

## ✅ End-to-End Tests
- Run & Analyze Tests with Kubetest  
- Smoke Testing  

---

## 🩺 Troubleshooting
- Application Failures  
- Control Plane Failures  
- Worker Node Failures  

---

## ⭐ Important CKAD Topics
- Readiness & Liveness Probes  
- Jobs & CronJobs  
- StatefulSets & StorageClasses  
- Headless Services  

---

## 📚 Other Topics
- Advanced Kubectl (JSONPath Queries)  
