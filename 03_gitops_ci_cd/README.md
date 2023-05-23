## ArgoCD

```bash
kubectl create namespace argocd
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
```

- [ArgoCD](https://argo-cd.readthedocs.io/en/stable/getting_started/)


## Helm

- [Charts](https://artifacthub.io/)
- [Cert Manager](https://artifacthub.io/packages/helm/cert-manager/cert-manager)
- [Kube Prometheus Stack](https://artifacthub.io/packages/helm/prometheus-community/kube-prometheus-stack)
- [ArgoCD](https://artifacthub.io/packages/helm/argo/argo-cd)
- [External Secrets](https://artifacthub.io/packages/helm/external-secrets/external-secrets)

## Crossplane interchangable with Terraform

- Manage AWS (cloud provider) resources
- [Installation](https://artifacthub.io/packages/helm/crossplane/crossplane#pre-requisites)

