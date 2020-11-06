#

These helm repositories are intended to be a good starting point and can be used and altered as required.

## Charts

| Chart Repository | Description |
|--|--|
| [devops](devops) | Ping Identity DevOps Charts

## Add the Repositories

```shell
helm repo add pingidentity https://helm.pingidentity.com/devops
helm repo update
helm repo list
```

## Search for a Ping chart

```shell
helm search repo pingidentity
```

## Remove the Repositories

```shell
helm repo remove pingidentity
helm repo list
```

## Config/Value .yamls

### Standalone Demos configs

| Config | Description |
|--|--|
| [pingfederate.yaml](configs/pingfederate.yaml) | PingFederate Admin/Engine
| [pingdirectory.yaml](configs/pingdirectory.yaml) | Replicated Directory
| [pingaccess.yaml](configs/pingaccess.yaml) | PingAccess Server

### Use Case configs

| Config | Description |
|--|--|
| fullstack.yaml | TBD

## Deployment Examples

### PingFederate Admin/Engine

```shell
helm install pf pingidentity/devops \
     -f https://helm.pingidentity.com/configs/pingfederate.yaml
```