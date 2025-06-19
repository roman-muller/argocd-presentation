# ArgoCD
---

### 🧠 "X as Code" - Overview

- **Infrastructure** → Terraform, Pulumi  
- **Config** → Ansible, YAML  
- **Network** → NetDevOps, Cisco NSO  
- **Security** → Snyk, tfsec  
- **Policy** → OPA, Kyverno  
- **Deployment** → ArgoCD, GitHub Actions

---

### 🚀 What is GitOps?
🗂 Git as the single source of truth

📜 Declarative infrastructure and configuration

🔄 Pull-based delivery via automation agents

🔁 Constant reconciliation to enforce desired state

---

### 🔄 Pull-Based Deployment with GitOps Agent
📦 Agent runs in Kubernetes, pulls config often

📜 Git repo stores desired state

🔍 Agent checks desired vs. actual state

🛠 Auto-fixes drift to stay in sync

🎯 Keep actual state matching desired state

---

### 🚢 A Short History of ArgoCD
- Built by **Intuit** in 2018
- Open sourced in late 2018
- **CNCF graduated project** in 2020
- **Argo ecosystem**: Workflows, Rollouts, Events
- Built especially as CD Tool for K8s

---

### 🚧 CD Workflow Without ArgoCD
⚙️ Manual setup: tools (kubectl), K8s & cloud access

👁️ No centralized deployment status monitoring

⚠️ High risk of drift, errors

🛠 Troubleshooting and rollback are complex

---

### 🚀 CD Workflow with ArgoCD
📥 Continuously pulls desired state from Git

🔍 Compares desired state with actual cluster state

⚙️ Automatically syncs and reconciles differences

👁️ Shows real-time deployment status

---

### 🧩 ArgoCD as a Kubernetes Extension

🚀 Runs inside Kubernetes as custom controllers

🔧 Adds GitOps and deployment tools to Kubernetes API

🔄 Monitors and compares state using controllers

👁️ Dashboard and CLI for easy control and visibility

🎯 Shows real-time app status


---

### 🎬 Demo


🔗 https://github.com/roman-muller/argocd-demo
