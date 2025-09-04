# Kubernetes Projects

This repo contains hands-on Kubernetes manifests for learning DevOps:
- `deployments/` – contains `nginx-deployment.yaml`
- `services/` – contains `service.yaml`

## How to Run
1. `kubectl apply -f deployments/nginx-deployment.yaml`
2. `kubectl apply -f services/service.yaml`
3. Visit `http://localhost:<NodePort>`

## Learning Roadmap
- Already completed: deployments, services, scaling, rolling update
- Next: ConfigMaps, Ingress, Monitoring
