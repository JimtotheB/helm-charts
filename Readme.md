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