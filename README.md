# simple-pod-operator

### kubebuilder

```
kubebuilder init --domain test.hfgary.io --owner hfgary --repo github.com/hfgary/simple-pod-operator.git

kubebuilder create api --group core --version v1 --kind Pod # create resource no, create controller yes

go run cmd/main.go
```

### kind

```
kind create cluster

kind delete cluster
```

### devbox

```
devbox version
0.13.7
```

```
devbox init

devbox search go

devbox add go@1.23.4
devbox add docker@27.4.1
devbox add kind@0.26.0
devbox add kubectl@1.32.0
devbox add kubebuilder@4.3.1

devbox shell

refresh
```

### Test

```
kubectl run test --rm -it --image=nginx -- /bin/bash
```

### Reference

- https://www.jetify.com/docs/devbox/installing_devbox/?install-method=macos
- https://www.youtube.com/watch?v=_XUJ1HoinWA