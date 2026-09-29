> 
Full-stack PayPal login simulation deployed on Kubernetes - focused on learning K8s architecture and secure data handling.

🔗 *Live Demo Repo:* https://github.com/ossmaahmed/paypal

🎯 Project Objectives
- Simulate a real-world login flow to understand security risks
- Learn how to secure applications against phishing attacks
- Practice end-to-end DevOps deployment

🛠️ Tech Stack
- *Frontend:* React + Vite
- *Backend:* Node.js / Express
- *Database:* MySQL
- *DevOps:* Docker, Kubernetes, Nginx Ingress

☸️ Kubernetes Concepts Implemented
- *Workloads:* Deployment, Pod, ReplicaSet
- *Networking:* Service, Ingress, NetworkPolicy
- *Storage:* PersistentVolume (PV), PersistentVolumeClaim (PVC)
- *Scheduling:* Taints & Tolerations, Node Affinity, Node Selector

📁 Structure
├── backend/   # API & Auth
├── frontend/  # React UI
└── k8s/       # All K8s manifests

🚀 How to Run

```bash
1. Clone
git clone https://github.com/ossmaahmed/paypal.git

2. Deploy on K8s
kubectl apply -f k8s/
kubectl get pods
kubectl get ingress
🙏 Acknowledgment
Special thanks to Eng. Khaled and NTI (National Telecommunication Institute) for the great mentorship during the DevOps track.

---
Built with ❤️ for learning

