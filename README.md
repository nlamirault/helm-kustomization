# Helm Kustomization example

Use the [kustomize](https://kustomize.io/) (>= 4.3.0) `--enable-helm` flag to inflate a Helm chart as part of the kustomize build process, and patches the manifests to modify the resulting output

Usage:

```shell
$ kustomize build --enable-helm .
```
