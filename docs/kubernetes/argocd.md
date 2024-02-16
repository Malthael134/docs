# ArgoCD - CI/CD using GitOps

!!! info
    ArgoCD Documentation: [https://argo-cd.readthedocs.io/en/stable/](https://argo-cd.readthedocs.io/en/stable/)

```bash
helm repo add argo https://argoproj.github.io/argo-helm
helm repo update
helm install argocd argo/argo-cd --version 5.53.8 -n argocd --create-namespace
```
