## Service Deployment and Basic k8s resources

- [Deployment](https://kubernetes.io/docs/concepts/workloads/controllers/deployment/)
- [Service](https://kubernetes.io/docs/concepts/services-networking/service/)
- [Ingress](https://kubernetes.io/docs/concepts/services-networking/ingress/)
- [ConfigMap](https://kubernetes.io/docs/concepts/configuration/configmap/)
- [Secret](https://kubernetes.io/docs/concepts/configuration/secret/)




## Namespace

### Ingress - if you want it to be accessible from web
- Expose service to outside

### Service - if you want it to be accessible in k8s cluster
- Pointer to deployment

### Deployments - minimum to run a service
- Docker file
- Port
- How many replicas

### Pods
- Actual service that is running
