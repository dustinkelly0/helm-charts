# Ping Identity Helm Charts

This repository provides sample Helm charts for Ping Identity products for community use.

These helm charts are intended to be a good starting point and can be used and altered as required.


## Charts

| Chart | Type | Capability | Status | Scalable |
|--|--|--|--|--|
| PingFederate | Product | SSO / Authentication Authority | Available (Beta) | Yes |
| PingAccess | Product | Medium/Course grain Authorisation Gateway / PEP | Available (Beta) | No (TBC) |
| PingDirectory | Product | User/Device/Consent/Organisation Directory | Available (Beta) | Yes |
| PingCentral | Product | Delegated Application Management UI | Available (Beta) | Yes |
| PingDataConsole | Product | PingData Admin Console | Available (Beta) | Not required |
| PingDataGovernance | Product | Fine-grain Authorisation PDP | Not available | N/a |
| PingDataGovernance PAP | Product | Fine-grain Authz PAP | Not available | N/a |
| PingDataSync | Product | Data Synchronisation Engine | Not available | N/a |
| PingDelegator | Product | Delegated User Management UI | Not available | Yes |
| PingDirectoryProxy | Product | Directory Proxy | Not available | N/a |

## Add the Repository

```shell
helm repo add ping-devops https://helm.pingidentity.com/devops
helm repo update
helm repo list
```

## Search for a Ping chart
```shell
helm search repo ping
```

## Remove the Repository

```shell
helm repo remove ping-devops
helm repo list
```
