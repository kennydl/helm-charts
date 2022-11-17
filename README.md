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