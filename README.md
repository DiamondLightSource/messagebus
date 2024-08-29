# Messagebus

A central RabbitMQ messagebus using Argo CD for deployment on Kubernetes.

## Deployment

The RabbitMQ messagebus can be deployed as an ArgoCD app:

```bash
kubectl -n messagebus apply -f rabbitmq-app.yaml
```

after which it can be managed at https://argocd.diamond.ac.uk