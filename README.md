# eBPF-runtime-threat-detection-k8s
eBPF-Based Runtime Threat Detection for Kubernetes using Tetragon
# eBPF-based Runtime Threat Detection for Kubernetes

## 📌 Project Overview
This project implements an *eBPF-based Runtime Threat Detection system* for Kubernetes clusters.  
It monitors *kernel-level system calls in real time* to detect suspicious and malicious activities such as unauthorized shell access, abnormal process execution, and sensitive file access inside containers.

The solution is built using *Cilium Tetragon* and deployed on a *Minikube Kubernetes cluster*, enabling deep runtime security visibility with minimal performance overhead.

---

## 🚀 Key Features
- Real-time monitoring of *kernel-level events* using eBPF
- Detection of *runtime security threats* inside containers
- Monitoring of system calls like execve, open, and write
- Kubernetes-aware alerts enriched with *pod and namespace metadata*
- Lightweight and high-performance security monitoring
- End-to-end *DevSecOps observability pipeline*

---

## 🛠 Tech Stack
- *Kubernetes (Minikube)*
- *eBPF*
- *Cilium Tetragon*
- *Prometheus*
- *Grafana*
- *Loki*
- *Alertmanager*
- *Linux Kernel*

---

## 🏗 Architecture
1. Kubernetes cluster running on Minikube
2. Cilium Tetragon deployed as a DaemonSet
3. eBPF programs attached to kernel hooks
4. Runtime events collected and analyzed
5. Metrics scraped by Prometheus
6. Logs shipped to Loki
7. Alerts generated via Alertmanager
8. Visualization through Grafana dashboards

---

## 🔍 Threat Detection Use Cases
- Unauthorized shell execution inside containers
- Malicious process spawning
- Suspicious file access and modification
- Abnormal system call behavior
- Container escape attempt detection (simulated)

---

## 📊 Observability & Monitoring
- Real-time security metrics exposed via Prometheus
- Centralized logging using Loki
- Visual dashboards created in Grafana
- Actionable security alerts for rapid incident response

---

## ⚙ Deployment
- Cluster setup using *Minikube*
- Tetragon deployed as a *Kubernetes DaemonSet*
- eBPF programs automatically loaded at runtime
- Monitoring stack deployed alongside the cluster

---

## 📈 Performance
- Minimal performance overhead
- Low CPU and memory consumption during active monitoring
- Optimized for production-like Kubernetes environments

---

## 🎯 Learning Outcomes
- Hands-on experience with *eBPF internals*
- Kubernetes runtime security implementation
- Real-time threat detection techniques
- DevSecOps observability pipeline design
- Practical exposure to cloud-native security tools

---

## 👩‍💻 Author
*Anjali Singh*  
GitHub: https://github.com/singhanjali33375-rgb  
Portfolio: https://singhanjali33375-rgb.github.io/personal-portfolio/

---

## ⭐ Note
This project is created for *learning and demonstration purposes* and showcases real-world runtime security concepts used in modern cloud-native environments.
