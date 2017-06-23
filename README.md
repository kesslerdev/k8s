# k8s

kubernetes ressources

## Apps

### simple busybox for testing

```bash
kubectl create -f apps/busybox.yaml

kubectl exec -ti busybox -- sh
```