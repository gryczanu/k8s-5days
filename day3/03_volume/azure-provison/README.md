```sh
kubectl apply -f deployment-pv.yaml -f  pvc-azure.yaml
kubectl get pv
kubectl get pvc
kubectl get po
kubectl describe pvc az01
kubectl delete pvc az01
kubectl get pvc
kubectl delete deploy nginx-deployment-az01
kubectl describe pvc az01
kubectl get pv
```

