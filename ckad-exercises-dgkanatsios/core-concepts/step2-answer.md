```
$ kubectl run nginx --image=nginx --dry-run=client -n mynamespace -o yaml > pod.yaml

$ kubectl create -f pod.yaml -n mynamespace
```