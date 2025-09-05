echo "# Kubernetes Architecture

Kubernetes is a container orchestration system that manages applications across a cluster of machines.

## Control Plane Components
- **kube-apiserver** → Serves the Kubernetes API
- **etcd** → Key-value store for cluster data
- **kube-scheduler** → Assigns Pods to nodes
- **kube-controller-manager** → Ensures desired state

## Node Components
- **kubelet** → Runs on each node, communicates with the API server
- **kube-proxy** → Handles networking and routing inside the cluster
- **Container runtime** → Runs the containers (Docker, containerd, etc.)

## Add-ons
- **CoreDNS** → Provides DNS for services
- **Dashboard** → Web UI (optional)
- **Metrics Server** → Resource metrics (CPU, memory)

---
