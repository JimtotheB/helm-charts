# Helm Charts

### Contains

- Pom-v7

### Updating

```shell
helm package src/pom-v7 --destination ./docs
helm repo index ./docs --url https://jimtotheb.github.io/helm-charts
```