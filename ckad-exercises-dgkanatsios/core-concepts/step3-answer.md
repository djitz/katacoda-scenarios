```bash
$ kubectl run busybox --image=busybox --command --restart=Never -it -- env # -it will help in seeing the output
```

```bash
# or, just run it without -it
$ kubectl run busybox --image=busybox --command --restart=Never -- env
```

```bash
# and then, check its logs
$ kubectl logs busybox
```