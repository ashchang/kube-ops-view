# kube-ops-view
dunno why helm is deprecated and cannot be use so make this

```
kubectl apply -f kube-ops-view.yaml
```
```
kubectl port-forward service/kube-ops-view 8080:80
```

open your browser and type
```
localhost:8080
```
