kubectl apply -f https://raw.githubusercontent.com/kubernetes/dashboard/v2.7.0/aio/deploy/recommended.yaml

```sh
kubectl create -f admin-user.yml
kubectl create -f rbac-admin.yml

kubectl -n kubernetes-dashboard create token admin-user
```

kubectl proxy


http://localhost:8001/api/v1/namespaces/kubernetes-dashboard/services/https:kubernetes-dashboard:/proxy/#/login
