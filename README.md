# simple-pod-operator

### kubebuilder

```
kubebuilder init --domain test.hfgary.io --owner hfgary --repo github.com/hfgary/simple-pod-operator.git
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

### Reference

- https://www.jetify.com/docs/devbox/installing_devbox/?install-method=macos
- https://www.youtube.com/watch?v=_XUJ1HoinWA