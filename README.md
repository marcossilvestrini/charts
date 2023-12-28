# Helm Charts By Silvestrini

## Chart repository

<https://marcossilvestrini.github.io/charts>

## Charts Released

app-silvestrini\
cloudnative-pg-cluster

## How to Install the Chart

Example for install chart on your Kubernetes cluster, you can use the following command:

```bash
helm repo add silvestrini https://marcossilvestrini.github.io/charts
helm upgrade --install --namespace pg-cluster-app --create-namespace pg-cluster-app silvestrini/cloudnative-pg-cluster
```

## How to Uninstall the Chart

If you want to uninstall the chart, you can use the following command:

```bash
helm uninstall pg-cluster-app
```
