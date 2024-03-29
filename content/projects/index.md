---
title: "projects"
date: 2023-01-01T00:00:00-00:00
---

## Azure projects

### azure-resourcemanager-exporter ([github repository](https://github.com/webdevops/azure-resourcemanager-exporter))
Prometheus exporter for Azure ResourceManager informations (infos, quotas, limits, usages, public IPs, portscanner)

### azure-metrics-exporter ([github repository](https://github.com/webdevops/azure-metrics-exporter))
Azure Monitor metrics exporter for Prometheus with dimension support, template engine and ServiceDiscovery

### azure-keyvault-exporter ([github repository](https://github.com/webdevops/azure-keyvault-exporter))
Prometheus exporter for Azure Keyvault entries (expiry date)

### azure-resourcegraph-exporter ([github repository](https://github.com/webdevops/azure-resourcegraph-exporter))
Prometheus exporter for Azure ResourceGraph queries

### azure-loganalytics-exporter ([github repository](https://github.com/webdevops/azure-loganalytics-exporter))
Prometheus exporter for Azure LogAnaylytics (Kusto queries)

### azure-devops-exporter ([github repository](https://github.com/webdevops/azure-devops-exporter))
Prometheus exporter for Azure DevOps (VSTS) including agent pools, builds, releases, deployments, pullrequests and repo stats

### azure-auditor ([github repository](https://github.com/webdevops/azure-auditor))
Audit service for Azure cloud with Prometheus violation metrics

### azure-scheduledevents-manager ([github repository](https://github.com/webdevops/azure-scheduledevents-manager))
Azure Scheduledevents manager for kubernetes and VMs (automatic drain and Prometheus metrics)

### azure-janitor ([github repository](https://github.com/webdevops/azure-janitor))
Janitor for Azure Resources, ResourceGroups, Deployments and RoleAssignments by ttl


## Kubernetes projects

### helm azure-keyvault ([github repository](https://github.com/webdevops/helm-azure-keyvault))
Helm plugin and standalone tool for Azure - injecting Azure information and KeyVault secrets into files using go template engine

### azure-k8s-autopilot ([github repository](https://github.com/webdevops/azure-k8s-autopilot))
K8S operator for Azure VMSS/VM for automatic repair and update

### kube-bootstrap-token-manager ([github repository](https://github.com/webdevops/kube-bootstrap-token-manager))
Manager for Kubernetes bootstrap tokens with cloud support

### kube-kube-pool-manager ([github repository](https://github.com/webdevops/kube-pool-manager))
Manages Kubernetes pools (annotation, labels, roles, configSource) by any node spec (json path support)



## General projects

### Dockerfile ([github repository](https://github.com/webdevops/Dockerfile))
Dockerfiles from WebDevOps for PHP, Apache and Nginx

### public-holiday-exporter ([github repository](https://github.com/webdevops/public-holiday-exporter))
Prometheus exporter for public holidays

### deadmanssnitch-exporter ([github repository](https://github.com/webdevops/deadmanssnitch-exporter))
Prometheus exporter for DeadMansSnitch

### shelly-plug-exporter ([github repository](https://github.com/webdevops/shelly-plug-exporter))
Prometheus exporter for Shelly plugs

### gq-gmc-exporter ([github repository](https://github.com/webdevops/gq-gmc-exporter))
Prometheus exporter for GQ GMC (Geiger–Muller counter) devices

### go-crond ([github repository](https://github.com/webdevops/go-crond))
Cron daemon written in golang (for eg. usage in docker images)

### go-sync ([github repository](https://github.com/webdevops/go-sync))
CLI synchronization utility to sync project files and databases for your local project with SSH and Docker support
