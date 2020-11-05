# Ping Identity Helm Charts

This repository provides sample Helm charts for Ping Identity products for community use.

These helm charts are intended to be a good starting point and can be used and altered as required.

## Charts

| Chart | Type | Capability | Status | Scalable |
|--|--|--|--|--|
| FullStack | Demo | All Ping DevOps charts included | Available (Beta) | Yes |

## Add the Repository

```shell
helm repo add ping-demos https://helm.pingidentity.com/demos
helm repo update
helm repo list
```

## Search for a Ping chart
```shell
helm search repo ping
```

## Remove the Repository

```shell
helm repo remove ping-demos
helm repo list
```
