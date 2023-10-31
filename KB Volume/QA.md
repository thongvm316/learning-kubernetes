# QA

1. What is diff pv and pvc?
2. `storageClassName: standard` ?
3. What is `storage: 1Gi` and purpose?
4. What is diff if I just use hostPath instead config pv-pvc?

# Steps handle pv-pvc, apple for deployment

```YAML
    kubectl get sc: get default volume of KB
    kubectl apply -f host-pv.yaml
    kubectl apply -f host-pvc.yaml
    kubectl apply -f deployment.yaml
    minikube service story-service
```
