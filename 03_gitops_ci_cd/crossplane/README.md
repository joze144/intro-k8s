## Crossplane to manage AWS resources


### Install with Helm

- Install Crossplane
```bash
$ helm install crossplane --namespace crossplane-system crossplane-stable/crossplane
```

- Install AWS provider

```bash
$ kubectl apply -f aws-provider.yaml
$ kubectl apply -f aws-provider-config.yaml
```

## Create AWS Resources

- Crossplane can manage AWS resources through AWS proovider
- ArgoCD will syncer ./definitions directory
- AWS resources can be created from ./templates folder
