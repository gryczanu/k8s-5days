# Custom Resources

Custom resources are extensions of the Kubernetes API.

https://kubernetes.io/docs/concepts/extend-kubernetes/api-extension/custom-resources/

# Create crd

```sh
kubectl get podcreators
kubectl apply -f bash-operator/kubernetes
kubectl get CustomResourceDefinition
kubectl get CustomResourceDefinition podcreators.bash-operators.maque
kubectl get podcreators
```

```sh
kubectl apply -f bash-operator/example
kubectl get podcreators
kubectl logs -l app=pod-creator
kubectl get pod
kubectl get po | grep marcin
kubectl describe svc test
```
