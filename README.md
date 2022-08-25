# Helm Chart Repository

## Table of Contents

- [Installation](#installation)

## Installation

### Install Helm

Install the latest version of helm. See [installing helm](https://helm.sh/docs/intro/install) for more information.

> check that helm is installed and retrieve it's version with:

```bash
helm version
```

### Add Repository

```bash
helm repo add todie https://todie.github.io/helm-charts
helm repo update
```

### List Charts

```bash
helm repo search -l todie
```

## Install Charts

```bash
helm install <my-release> todie/<chart-name>
```

## Available Charts

- [1Password SCIM Bridge](https://github.com/todie/helm-charts/tree/main/charts/op-scim-bridge)
