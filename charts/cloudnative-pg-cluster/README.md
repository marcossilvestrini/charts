# Helm Charts for cloudnative-pg-cluster

## Description

This is a Helm chart for Kubernetes that allows you to deploy the "cloudnative-pg-cluster" application to your Kubernetes cluster.

## Versioning

version: 1.0.0

The application version deployed by this chart is "1.16.0". You should update the application version as needed.

## Cloud Native Postgresql Operator

https://github.com/cloudnative-pg/cloudnative-pg/blob/main/docs/src/quickstart.md

## Chart Repository

This chart is available in the Helm repository at https://marcossilvestrini.github.io/charts/.

## How to Install the Chart

**Pre require for this chart: cloudnative-pg operator installed in cluster**

To install this chart on your Kubernetes cluster, you can use the following command:

```bash

helm repo add my-repo https://marcossilvestrini.github.io/charts/
helm install my-release my-repo/cloudnative-pg-cluster
```

## How to Uninstall the Chart

If you want to uninstall the chart, you can use the following command:

```bash
helm uninstall my-release
```
