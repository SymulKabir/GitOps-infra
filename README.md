#### On your server, apply ArgoCD Application
To run Nginx App
```bash
kubectl apply -f argo-apps/nginx-app.yaml -n argocd
```

To run Full-Stack app App
```bash
kubectl apply -f argo-apps/full-stack-app.yaml -n argocd
```