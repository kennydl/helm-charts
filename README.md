# helm-charts

## Create chart
```
## Create a chart called deployment
helm create deployment
```

## Upgrade chart
```
## First change version in Chart.yaml
$ helm package deployment
$ helm repo index .
```

# Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

### Once Helm has been set up correctly, add the repo as follows:
> helm repo add my-charts https://kennydl.github.io/helm-charts

### To retrieve the latest versions of the packages:
> helm repo update

### To list all charts by alias:
> helm search repo my-charts

### To remove an alias repo:
> helm repo remove my-charts

### To install a chart:

> helm install [release-name] my-charts/[chart-name]

### To uninstall the chart:

> helm delete [release-name]