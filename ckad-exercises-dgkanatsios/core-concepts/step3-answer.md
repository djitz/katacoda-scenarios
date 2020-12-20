```
$ kubectl run busybox --image=busybox --command --restart=Never -it -- env # -it will help in seeing the output

# or, just run it without -it
$ kubectl run busybox --image=busybox --command --restart=Never -- env

# and then, check its logs
$ kubectl logs busybox
```