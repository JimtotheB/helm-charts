# Helm Charts

### Contains

- Pom-v7

### Test Rendering

```shell
helm template . --values ../../test/pomv7.yaml --set deploymentHash=fhfhf
```

### Updating

```shell
helm package src/pom-v7 --destination ./docs
helm repo index ./docs --url https://jimtotheb.github.io/helm-charts
```

#TODO

Deprecate extensions/v1beta1 in favor of networking.k8s.io/v1 for Ingress.
This will require testing, and breaking template changes.

