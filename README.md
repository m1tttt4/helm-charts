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
helm repo add m1tttt4 https://m1tttt4.github.io/helm-charts
helm repo update
```

### List Charts

```bash
helm repo search -l m1tttt4
```

## Install Charts

```bash
helm install <my-release> m1tttt4/<chart-name>
```

## Available Charts

- [1Password SCIM Bridge](https://github.com/m1tttt4/helm-charts/tree/main/charts/op-scim-bridge)
