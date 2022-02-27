# Arc Container Image Refresher
**Image dump generated at: `2022-02-27-20-29-27`**
## Useful images
### Arc Data Services
|    | image                     | image_url                                              | latest_build_date              | latest_tag        |
|---:|:--------------------------|:-------------------------------------------------------|:-------------------------------|:------------------|
|  0 | arc-sqlmi                 | mcr.microsoft.com/v2/arcdata/arc-sqlmi                 | 2022-02-25T04:07:26.378287312Z | v1.4.0_2022-02-25 |
|  1 | arc-postgres-12           | mcr.microsoft.com/v2/arcdata/arc-postgres-12           | 2022-02-25T04:06:45.679788739Z | v1.4.0_2022-02-25 |
|  2 | arc-postgres-11           | mcr.microsoft.com/v2/arcdata/arc-postgres-11           | 2022-02-25T04:05:44.388850447Z | v1.4.0_2022-02-25 |
|  3 | arc-kafka                 | mcr.microsoft.com/v2/arcdata/arc-kafka                 | 2022-02-25T04:03:46.431175098Z | v1.4.0_2022-02-25 |
|  4 | arc-controller-db         | mcr.microsoft.com/v2/arcdata/arc-controller-db         | 2022-02-25T04:01:48.830315511Z | v1.4.0_2022-02-25 |
|  5 | arc-controller            | mcr.microsoft.com/v2/arcdata/arc-controller            | 2022-02-25T04:01:02.166837292Z | v1.4.0_2022-02-25 |
|  6 | arc-bootstrapper          | mcr.microsoft.com/v2/arcdata/arc-bootstrapper          | 2022-02-25T03:59:43.949204601Z | v1.4.0_2022-02-25 |
|  7 | arc-ha-supervisor         | mcr.microsoft.com/v2/arcdata/arc-ha-supervisor         | 2022-02-25T03:58:48.583299816Z | v1.4.0_2022-02-25 |
|  8 | arc-ha-orchestrator       | mcr.microsoft.com/v2/arcdata/arc-ha-orchestrator       | 2022-02-25T03:58:41.097594263Z | v1.4.0_2022-02-25 |
|  9 | arc-dns                   | mcr.microsoft.com/v2/arcdata/arc-dns                   | 2022-02-25T03:58:12.84054861Z  | v1.4.0_2022-02-25 |
| 10 | arc-service-proxy         | mcr.microsoft.com/v2/arcdata/arc-service-proxy         | 2022-02-25T03:57:56.845207675Z | v1.4.0_2022-02-25 |
| 11 | arc-monitor-kibana        | mcr.microsoft.com/v2/arcdata/arc-monitor-kibana        | 2022-02-25T03:56:46.67413577Z  | v1.4.0_2022-02-25 |
| 12 | arc-monitor-elasticsearch | mcr.microsoft.com/v2/arcdata/arc-monitor-elasticsearch | 2022-02-25T03:56:23.057825632Z | v1.4.0_2022-02-25 |
| 13 | arc-monitor-fluentbit     | mcr.microsoft.com/v2/arcdata/arc-monitor-fluentbit     | 2022-02-25T03:56:10.945585827Z | v1.4.0_2022-02-25 |
| 14 | arc-monitor-grafana       | mcr.microsoft.com/v2/arcdata/arc-monitor-grafana       | 2022-02-25T03:56:06.021550899Z | v1.4.0_2022-02-25 |
| 15 | arc-monitor-influxdb      | mcr.microsoft.com/v2/arcdata/arc-monitor-influxdb      | 2022-02-25T03:55:58.604370716Z | v1.4.0_2022-02-25 |
| 16 | arc-monitor-telegraf      | mcr.microsoft.com/v2/arcdata/arc-monitor-telegraf      | 2022-02-25T03:55:50.979462013Z | v1.4.0_2022-02-25 |
| 17 | arc-monitor-collectd      | mcr.microsoft.com/v2/arcdata/arc-monitor-collectd      | 2022-02-25T03:55:45.894236696Z | v1.4.0_2022-02-25 |
| 18 | arcdataservices-extension | mcr.microsoft.com/v2/arcdata/arcdataservices-extension |                                | 1.1.18791000      |
---
### Arc Kubernetes - AKA "HAIKU"
|    | image                          | image_url                                                       | latest_build_date              | latest_tag    |
|---:|:-------------------------------|:----------------------------------------------------------------|:-------------------------------|:--------------|
|  0 | guardcontroller                | mcr.microsoft.com/v2/azurearck8s/guardcontroller                | 2022-02-19T00:14:51.641241689Z | 1.6.7-preview |
|  1 | guardinit-container            | mcr.microsoft.com/v2/azurearck8s/guardinit-container            | 2022-02-19T00:14:08.287930665Z | 1.6.7-preview |
|  2 | clusterconnectservice-operator | mcr.microsoft.com/v2/azurearck8s/clusterconnectservice-operator | 2022-02-19T00:13:21.383104492Z | 1.6.7-preview |
|  3 | extensionoperator              | mcr.microsoft.com/v2/azurearck8s/extensionoperator              | 2022-02-19T00:12:35.975289248Z | 1.6.7-preview |
|  4 | flux-logs-agent                | mcr.microsoft.com/v2/azurearck8s/flux-logs-agent                | 2022-02-19T00:11:47.636965214Z | 1.6.7-preview |
|  5 | cluster-metadata-operator      | mcr.microsoft.com/v2/azurearck8s/cluster-metadata-operator      | 2022-02-19T00:10:58.346762646Z | 1.6.7-preview |
|  6 | resource-sync                  | mcr.microsoft.com/v2/azurearck8s/resource-sync                  | 2022-02-19T00:10:10.357184805Z | 1.6.7-preview |
|  7 | cluster-identity               | mcr.microsoft.com/v2/azurearck8s/cluster-identity               | 2022-02-19T00:09:18.23035242Z  | 1.6.7-preview |
|  8 | configoperator                 | mcr.microsoft.com/v2/azurearck8s/configoperator                 | 2022-02-19T00:08:20.106075907Z | 1.6.7-preview |
|  9 | connect-agent                  | mcr.microsoft.com/v2/azurearck8s/connect-agent                  | 2022-02-19T00:07:31.228704394Z | 1.6.7-preview |
| 10 | config-agent                   | mcr.microsoft.com/v2/azurearck8s/config-agent                   | 2022-02-19T00:06:12.344459676Z | 1.6.7-preview |
| 11 | kube-aad-proxy                 | mcr.microsoft.com/v2/azurearck8s/kube-aad-proxy                 | 2022-02-19T00:04:07.201594431Z | 1.6.7-preview |
| 12 | clusterconnect-agent           | mcr.microsoft.com/v2/azurearck8s/clusterconnect-agent           | 2022-02-19T00:03:14.151085739Z | 1.6.7-preview |
| 13 | prom-to-configdp               | mcr.microsoft.com/v2/azurearck8s/prom-to-configdp               | 2022-02-18T23:56:18.707190753Z | 1.6.7-preview |
| 14 | appliance-connect-agent        | mcr.microsoft.com/v2/azurearck8s/appliance-connect-agent        | 2022-02-18T23:50:24.905944399Z | 1.6.7-preview |
| 15 | agent-update-job               | mcr.microsoft.com/v2/azurearck8s/agent-update-job               | 2022-02-18T23:47:33.743152611Z | 1.6.7-preview |
| 16 | fluent-bit                     | mcr.microsoft.com/v2/azurearck8s/fluent-bit                     | 2022-02-18T23:46:56.411890376Z | 1.6.7-preview |
| 17 | metrics-agent                  | mcr.microsoft.com/v2/azurearck8s/metrics-agent                  | 2022-02-18T23:42:43.851027748Z | 1.6.7-preview |
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
|  0 | aks           | mcr.microsoft.com/v2/azurearck8s/aks/stable/extensionoperator                 | 2022-02-18T22:22:31.882096229Z | 1.6.6           |
|  1 | aks           | mcr.microsoft.com/v2/azurearck8s/aks/stable/configoperator                    | 2022-02-18T22:19:21.91695387Z  | 1.6.6           |
|  2 | aks           | mcr.microsoft.com/v2/azurearck8s/aks/stable/config-agent                      | 2022-02-18T22:18:05.920831492Z | 1.6.6           |
|  3 | aks           | mcr.microsoft.com/v2/azurearck8s/aks/stable/fluent-bit                        | 2022-02-18T22:08:30.43140359Z  | 1.6.6           |
|  4 | arc-preview   | mcr.microsoft.com/v2/azurearck8s/arc-preview/flux-init-container              | 2020-09-30T00:53:51.125512705Z | 0.0.1           |
|  5 | batch1        | mcr.microsoft.com/v2/azurearck8s/batch1/stable/azure-arc-k8sagents            |                                | 1.6.6           |
|  6 | batch1        | mcr.microsoft.com/v2/azurearck8s/batch1/stable/appliance/azure-arc-k8sagents  |                                | 0.4.0-appliance |
|  7 | batch1        | mcr.microsoft.com/v2/azurearck8s/batch1/preview/azure-arc-k8sagents           |                                | 1.6.7-preview   |
|  8 | batch2        | mcr.microsoft.com/v2/azurearck8s/batch2/stable/azure-arc-k8sagents            |                                | 1.6.6           |
|  9 | batch2        | mcr.microsoft.com/v2/azurearck8s/batch2/preview/azure-arc-k8sagents           |                                | 1.6.7-preview   |
| 10 | westcentralus | mcr.microsoft.com/v2/azurearck8s/westcentralus/stable/azure-arc-k8sagents     |                                | 1.6.6           |
| 11 | canary        | mcr.microsoft.com/v2/azurearck8s/canary/stable/azure-arc-k8sagents            |                                | 1.6.6           |
| 12 | canary        | mcr.microsoft.com/v2/azurearck8s/canary/stable/appliance/azure-arc-k8sagents  |                                | 0.4.0-appliance |
| 13 | fairfax       | mcr.microsoft.com/v2/azurearck8s/fairfax/stable/azure-arc-k8sagents           |                                | 1.6.6           |
| 14 | batch1        | mcr.microsoft.com/v2/azurearck8s/batch1/stable/azure-arc-monitoring           |                                | 1.6.6           |
| 15 | batch1        | mcr.microsoft.com/v2/azurearck8s/batch1/stable/appliance/azure-arc-monitoring |                                | 0.4.0-appliance |
| 16 | batch1        | mcr.microsoft.com/v2/azurearck8s/batch1/preview/azure-arc-monitoring          |                                | 1.6.7-preview   |
| 17 | batch2        | mcr.microsoft.com/v2/azurearck8s/batch2/stable/azure-arc-monitoring           |                                | 1.6.6           |
| 18 | batch2        | mcr.microsoft.com/v2/azurearck8s/batch2/preview/azure-arc-monitoring          |                                | 1.6.7-preview   |
| 19 | westcentralus | mcr.microsoft.com/v2/azurearck8s/westcentralus/stable/azure-arc-monitoring    |                                | 1.6.6           |
| 20 | canary        | mcr.microsoft.com/v2/azurearck8s/canary/stable/azure-arc-monitoring           |                                | 1.6.6           |
| 21 | canary        | mcr.microsoft.com/v2/azurearck8s/canary/stable/appliance/azure-arc-monitoring |                                | 0.4.0-appliance |
| 22 | fairfax       | mcr.microsoft.com/v2/azurearck8s/fairfax/stable/azure-arc-monitoring          |                                | 1.6.6           |
| 23 | arc-preview   | mcr.microsoft.com/v2/azurearck8s/arc-preview/fluxctl                          |                                | 0.2.0           |