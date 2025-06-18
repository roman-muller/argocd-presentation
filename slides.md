# Argo CD
---

### 🧠 "X as Code" - Overview

- **Infrastructure** → Terraform, Pulumi  
- **Config** → Ansible, YAML  
- **Network** → NetDevOps, Cisco NSO  
- **Security** → Snyk, tfsec  
- **Policy** → OPA, Kyverno  
- **Deployment** → ArgoCD, GitHub Actions

> 💡 All aspects of infrastructure and operations can now be versioned, tested, and automated — **as code**!

---

### 🚀 What is GitOps?
🗂 Git as the single source of truth

📜 Declarative infrastructure and configuration

🔄 Pull-based delivery via automation agents

🔁 Constant reconciliation to enforce desired state

---

### 🔄 Pull-Based Deployment with GitOps Agent
📦 Agent runs inside Kubernetes, pulling config regularly

📜 Git repo defines the desired state

🔍 Agent compares desired vs. actual state continuously

🛠 Automatically fixes drift to keep states in sync

🎯 Always align actual state with desired state

---

### 🔀 Alternatives in GitOps CD

| Tool    | UI     | Multi-tenancy | Health Checks |
|---------|--------|----------------|----------------|
| Argo CD | ✅ Rich | ✅ Built-in    | ✅ Built-in    |
| Flux    | ⚙️ CLI | ⚠️ Limited     | ❌ Plugins     |
| Weave    | 🧩 Minimal | ⚠️ Basic       | 🔧 Plugins     |

---

### 🚢 A Short History of Argo CD
- Built by **Intuit** in 2018
- Open sourced in late 2018
- **CNCF graduated project** in 2020
- Core of **Argo ecosystem**: Workflows, Rollouts, Events

---

### 🚧 CD Workflow Without Argo CD
⚙️ Manual setup: tools (kubectl), K8s & cloud access

🔄 Deployments via scripts, no automation or visibility

👁️ No centralized deployment status monitoring

⚠️ High risk of drift, errors

🛠 Troubleshooting and rollback are complex

---

## Thank You!
