# Arc Container Image Refresher
**Image dump generated at: `2022-04-12-01-43-53`**
## Useful images
### Arc Data Services
|    | image                     | image_url                                              | latest_build_date              | latest_tag        |
|---:|:--------------------------|:-------------------------------------------------------|:-------------------------------|:------------------|
|  0 | arc-sqlmi                 | mcr.microsoft.com/v2/arcdata/arc-sqlmi                 | 2022-04-06T00:08:50.497383266Z | v1.5.0_2022-04-05 |
|  1 | arc-postgres-12           | mcr.microsoft.com/v2/arcdata/arc-postgres-12           | 2022-04-06T00:08:10.715233677Z | v1.5.0_2022-04-05 |
|  2 | arc-postgres-11           | mcr.microsoft.com/v2/arcdata/arc-postgres-11           | 2022-04-06T00:07:14.572854891Z | v1.5.0_2022-04-05 |
|  3 | arc-kafka                 | mcr.microsoft.com/v2/arcdata/arc-kafka                 | 2022-04-06T00:05:41.057741348Z | v1.5.0_2022-04-05 |
|  4 | arc-controller-db         | mcr.microsoft.com/v2/arcdata/arc-controller-db         | 2022-04-06T00:04:13.550781986Z | v1.5.0_2022-04-05 |
|  5 | arc-controller            | mcr.microsoft.com/v2/arcdata/arc-controller            | 2022-04-06T00:03:06.75624548Z  | v1.5.0_2022-04-05 |
|  6 | arc-bootstrapper          | mcr.microsoft.com/v2/arcdata/arc-bootstrapper          | 2022-04-06T00:01:53.768680184Z | v1.5.0_2022-04-05 |
|  7 | arc-ha-supervisor         | mcr.microsoft.com/v2/arcdata/arc-ha-supervisor         | 2022-04-06T00:00:59.710377453Z | v1.5.0_2022-04-05 |
|  8 | arc-ha-orchestrator       | mcr.microsoft.com/v2/arcdata/arc-ha-orchestrator       | 2022-04-06T00:00:52.680541537Z | v1.5.0_2022-04-05 |
|  9 | arc-dns                   | mcr.microsoft.com/v2/arcdata/arc-dns                   | 2022-04-06T00:00:24.732910141Z | v1.5.0_2022-04-05 |
| 10 | arc-service-proxy         | mcr.microsoft.com/v2/arcdata/arc-service-proxy         | 2022-04-06T00:00:08.733784206Z | v1.5.0_2022-04-05 |
| 11 | arc-monitor-kibana        | mcr.microsoft.com/v2/arcdata/arc-monitor-kibana        | 2022-04-05T23:58:59.015230167Z | v1.5.0_2022-04-05 |
| 12 | arc-monitor-elasticsearch | mcr.microsoft.com/v2/arcdata/arc-monitor-elasticsearch | 2022-04-05T23:58:35.549586063Z | v1.5.0_2022-04-05 |
| 13 | arc-monitor-fluentbit     | mcr.microsoft.com/v2/arcdata/arc-monitor-fluentbit     | 2022-04-05T23:58:24.697013125Z | v1.5.0_2022-04-05 |
| 14 | arc-monitor-grafana       | mcr.microsoft.com/v2/arcdata/arc-monitor-grafana       | 2022-04-05T23:58:18.869493987Z | v1.5.0_2022-04-05 |
| 15 | arc-monitor-influxdb      | mcr.microsoft.com/v2/arcdata/arc-monitor-influxdb      | 2022-04-05T23:58:12.048910485Z | v1.5.0_2022-04-05 |
| 16 | arc-monitor-telegraf      | mcr.microsoft.com/v2/arcdata/arc-monitor-telegraf      | 2022-04-05T23:58:04.730347777Z | v1.5.0_2022-04-05 |
| 17 | arc-monitor-collectd      | mcr.microsoft.com/v2/arcdata/arc-monitor-collectd      | 2022-04-05T23:57:59.857555241Z | v1.5.0_2022-04-05 |
| 18 | arcdataservices-extension | mcr.microsoft.com/v2/arcdata/arcdataservices-extension |                                | 1.1.19211001      |
---
### Arc Kubernetes - AKA "HAIKU"
|    | image                          | image_url                                                       | latest_build_date              | latest_tag    |
|---:|:-------------------------------|:----------------------------------------------------------------|:-------------------------------|:--------------|
|  0 | msi-adapter                    | mcr.microsoft.com/v2/azurearck8s/msi-adapter                    | 2022-04-08T05:09:18.117388506Z | 1.0.0         |
|  1 | guardcontroller                | mcr.microsoft.com/v2/azurearck8s/guardcontroller                | 2022-03-30T09:50:14.353258914Z | 1.7.1-preview |
|  2 | guardinit-container            | mcr.microsoft.com/v2/azurearck8s/guardinit-container            | 2022-03-30T09:49:31.166931064Z | 1.7.1-preview |
|  3 | clusterconnectservice-operator | mcr.microsoft.com/v2/azurearck8s/clusterconnectservice-operator | 2022-03-30T09:48:46.468635754Z | 1.7.1-preview |
|  4 | extensionoperator              | mcr.microsoft.com/v2/azurearck8s/extensionoperator              | 2022-03-30T09:47:07.501822123Z | 1.7.1-preview |
|  5 | flux-logs-agent                | mcr.microsoft.com/v2/azurearck8s/flux-logs-agent                | 2022-03-30T09:46:13.942415952Z | 1.7.1-preview |
|  6 | cluster-metadata-operator      | mcr.microsoft.com/v2/azurearck8s/cluster-metadata-operator      | 2022-03-30T09:45:30.970762242Z | 1.7.1-preview |
|  7 | resource-sync                  | mcr.microsoft.com/v2/azurearck8s/resource-sync                  | 2022-03-30T09:44:39.048073362Z | 1.7.1-preview |
|  8 | cluster-identity               | mcr.microsoft.com/v2/azurearck8s/cluster-identity               | 2022-03-30T09:43:36.441584171Z | 1.7.1-preview |
|  9 | configoperator                 | mcr.microsoft.com/v2/azurearck8s/configoperator                 | 2022-03-30T09:42:29.932804947Z | 1.7.1-preview |
| 10 | appliance-connect-agent        | mcr.microsoft.com/v2/azurearck8s/appliance-connect-agent        | 2022-03-30T09:41:27.410584545Z | 1.7.1-preview |
| 11 | connect-agent                  | mcr.microsoft.com/v2/azurearck8s/connect-agent                  | 2022-03-30T09:40:14.131418238Z | 1.7.1-preview |
| 12 | config-agent                   | mcr.microsoft.com/v2/azurearck8s/config-agent                   | 2022-03-30T09:39:27.050760448Z | 1.7.1-preview |
| 13 | prom-to-configdp               | mcr.microsoft.com/v2/azurearck8s/prom-to-configdp               | 2022-03-30T09:38:33.737098823Z | 1.7.1-preview |
| 14 | kube-aad-proxy                 | mcr.microsoft.com/v2/azurearck8s/kube-aad-proxy                 | 2022-03-30T09:37:27.609274407Z | 1.7.1-preview |
| 15 | clusterconnect-agent           | mcr.microsoft.com/v2/azurearck8s/clusterconnect-agent           | 2022-03-30T09:36:12.783092368Z | 1.7.1-preview |
| 16 | agent-update-job               | mcr.microsoft.com/v2/azurearck8s/agent-update-job               | 2022-03-30T09:31:49.797738263Z | 1.7.1-preview |
| 17 | fluent-bit                     | mcr.microsoft.com/v2/azurearck8s/fluent-bit                     | 2022-03-30T09:18:49.35975984Z  | 1.7.1-preview |
| 18 | metrics-agent                  | mcr.microsoft.com/v2/azurearck8s/metrics-agent                  | 2022-03-30T09:11:45.426395178Z | 1.7.1-preview |
---
## Use*less* images
There are a bunch of useless images in MCR - these seem to be suspect:
### Arc Data Services
|    | image                 | image_url                                          | latest_build_date              | latest_tag        |
|---:|:----------------------|:---------------------------------------------------|:-------------------------------|:------------------|
|  0 | arc-ha-operator       | mcr.microsoft.com/v2/arcdata/arc-ha-operator       | 2021-07-29T17:30:48.75187855Z  | v1.0.0_2021-07-30 |
|  1 | arc-server-controller | mcr.microsoft.com/v2/arcdata/arc-server-controller | 2021-05-28T01:36:29.11422795Z  | latest            |
|  2 | arc-control-watchdog  | mcr.microsoft.com/v2/arcdata/arc-control-watchdog  | 2021-04-26T21:41:27.245453254Z | latest            |
|  3 | mssql-ha-operator     | mcr.microsoft.com/v2/arcdata/mssql-ha-operator     | 2021-02-26T23:03:10.355773453Z | latest            |
---
### Arc Kubernetes - AKA "HAIKU"
|    | image         | image_url                                                                     | latest_build_date              | latest_tag      |
|---:|:--------------|:------------------------------------------------------------------------------|:-------------------------------|:----------------|
|  0 | aks           | mcr.microsoft.com/v2/azurearck8s/aks/stable/extensionoperator                 | 2022-03-30T09:47:07.501822123Z | 1.7.1           |
|  1 | aks           | mcr.microsoft.com/v2/azurearck8s/aks/stable/resource-sync                     | 2022-03-30T09:44:39.048073362Z | 1.7.1           |
|  2 | aks           | mcr.microsoft.com/v2/azurearck8s/aks/stable/configoperator                    | 2022-03-30T09:42:29.932804947Z | 1.7.1           |
|  3 | aks           | mcr.microsoft.com/v2/azurearck8s/aks/stable/config-agent                      | 2022-03-30T09:39:27.050760448Z | 1.7.1           |
|  4 | aks           | mcr.microsoft.com/v2/azurearck8s/aks/stable/fluent-bit                        | 2022-03-30T09:18:49.35975984Z  | 1.7.1           |
|  5 | arc-preview   | mcr.microsoft.com/v2/azurearck8s/arc-preview/flux-init-container              | 2020-09-30T00:53:51.125512705Z | 0.0.1           |
|  6 | batch1        | mcr.microsoft.com/v2/azurearck8s/batch1/stable/azure-arc-k8sagents            |                                | 1.6.6           |
|  7 | batch1        | mcr.microsoft.com/v2/azurearck8s/batch1/stable/appliance/azure-arc-k8sagents  |                                | 0.5.1-appliance |
|  8 | batch1        | mcr.microsoft.com/v2/azurearck8s/batch1/preview/azure-arc-k8sagents           |                                | 1.7.1-preview   |
|  9 | batch2        | mcr.microsoft.com/v2/azurearck8s/batch2/stable/azure-arc-k8sagents            |                                | 1.6.6           |
| 10 | batch2        | mcr.microsoft.com/v2/azurearck8s/batch2/preview/azure-arc-k8sagents           |                                | 1.7.1-preview   |
| 11 | westcentralus | mcr.microsoft.com/v2/azurearck8s/westcentralus/stable/azure-arc-k8sagents     |                                | 1.6.6           |
| 12 | canary        | mcr.microsoft.com/v2/azurearck8s/canary/stable/azure-arc-k8sagents            |                                | 1.6.6           |
| 13 | canary        | mcr.microsoft.com/v2/azurearck8s/canary/stable/appliance/azure-arc-k8sagents  |                                | 0.5.1-appliance |
| 14 | fairfax       | mcr.microsoft.com/v2/azurearck8s/fairfax/stable/azure-arc-k8sagents           |                                | 1.6.6           |
| 15 | batch1        | mcr.microsoft.com/v2/azurearck8s/batch1/stable/azure-arc-monitoring           |                                | 1.6.6           |
| 16 | batch1        | mcr.microsoft.com/v2/azurearck8s/batch1/stable/appliance/azure-arc-monitoring |                                | 0.5.1-appliance |
| 17 | batch1        | mcr.microsoft.com/v2/azurearck8s/batch1/preview/azure-arc-monitoring          |                                | 1.7.1-preview   |
| 18 | batch2        | mcr.microsoft.com/v2/azurearck8s/batch2/stable/azure-arc-monitoring           |                                | 1.6.6           |
| 19 | batch2        | mcr.microsoft.com/v2/azurearck8s/batch2/preview/azure-arc-monitoring          |                                | 1.7.1-preview   |
| 20 | westcentralus | mcr.microsoft.com/v2/azurearck8s/westcentralus/stable/azure-arc-monitoring    |                                | 1.6.6           |
| 21 | canary        | mcr.microsoft.com/v2/azurearck8s/canary/stable/azure-arc-monitoring           |                                | 1.6.6           |
| 22 | canary        | mcr.microsoft.com/v2/azurearck8s/canary/stable/appliance/azure-arc-monitoring |                                | 0.5.1-appliance |
| 23 | fairfax       | mcr.microsoft.com/v2/azurearck8s/fairfax/stable/azure-arc-monitoring          |                                | 1.6.6           |
| 24 | arc-preview   | mcr.microsoft.com/v2/azurearck8s/arc-preview/fluxctl                          |                                | 0.2.0           |