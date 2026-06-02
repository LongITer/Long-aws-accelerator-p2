# K8s Container/Orchestration Task

Mục tiêu: cung cấp các manifest mẫu cho bài tập "K8s Container/Orchestration".

Files included:
- namespace.yaml  — Tạo namespace `k8s-orchestration-task`
- configmap.yaml — Ví dụ ConfigMap
- secret.yaml    — Ví dụ Secret (thay giá trị trước khi apply)
- deployment.yaml — Deployment mẫu với container `nginx`
- service.yaml    — Service để expose Deployment
- ingress.yaml    — Ingress mẫu (thay host và cấu hình TLS nếu cần)
- kustomization.yaml — Kustomize base

Quick apply (from repo root):

```bash
kubectl apply -k cloud/w8/day-b
```