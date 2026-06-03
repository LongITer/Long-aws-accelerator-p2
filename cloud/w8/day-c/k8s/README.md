# Kubernetes Scaling + Networking

This folder contains sample manifests for:

- Deployment with resource requests/limits
- HorizontalPodAutoscaler (HPA) for CPU-based scaling
- ClusterIP Service for pod networking
- Ingress for external HTTP routing

Apply with:

```bash
kubectl apply -f k8s/k8s-scaling-networking.yaml
```

Update the host in the Ingress and ensure an Ingress Controller is installed in your cluster.