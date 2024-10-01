# LDAP Collector Helm Chart

## Current version: 2.0.6 (August 5th, 2024).

## Installation

Should you need to change/override the configuration of the collector, use the [`values.yaml`](helm/values.yaml) file as template to create your own and upgrade the Helm installation.

To install the Helm Chart, run the following command at the `./kubernetes` directory:

```bash
$ helm install ldap-collector ./helm
```

To uninstall the Helm Chart, run the following command:

```bash
$ helm uninstall ldap-collector
```
