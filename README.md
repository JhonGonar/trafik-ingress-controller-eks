# Traefik Ingress Controller on Minikube Kubernetes

See https://www.youtube.com/watch?v=-YwOG515M9M

## Steps

### 1.
helm install --namespace=traefik-v2 traefik traefik/traefik --values=values.yml

## Docs used in demo

- Kubernetes Deployment: https://kubernetes.io/docs/concepts/workloads/controllers/deployment/
- Kubernetes Service: https://kubernetes.io/docs/concepts/services-networking/service/
- Traefik helm chart install: https://doc.traefik.io/traefik/getting-started/install-traefik/#use-the-helm-chart
- Traefik Kubernetes Ingress: https://doc.traefik.io/traefik/providers/kubernetes-ingress/
- Traefik Kubernetes Ingress configuration: https://doc.traefik.io/traefik/providers/overview/
