# Helm Charts for cloudnative-pg-cluster

## Description

This is a Helm chart for Kubernetes that allows you to deploy the "cloudnative-pg-cluster" application to your Kubernetes cluster.

## Versioning

version: 1.1.2

The application version deployed by this chart is "1.16.0". You should update the application version as needed.

## Chart Repository

This chart is available in the Helm repository at https://marcossilvestrini.github.io/charts/.

## How to Install the Chart

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