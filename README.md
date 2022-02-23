[![CircleCI](https://circleci.com/gh/0hlov3/helm-charts/tree/main.svg?style=svg)](https://circleci.com/gh/0hlov3/helm-charts/tree/main)
[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/ohlove)](https://artifacthub.io/packages/search?repo=ohlove)
# helm-charts
0hlov3s Public Helm Charts

## Add Charts
```shell
helm repo add 0hlov3 http://schoenwald.me/helm-charts/
helm repo update
```

## Development
### Lint the chart
```shell
helm lint helm-charts/*
```

### Create the Helm chart package
```shell
helm package helm-charts/*
```

### Create the Helm chart repository index
```shell
helm repo index --url http://schoenwald.me/helm-charts/ .
```