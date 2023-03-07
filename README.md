# Example SciCat Kubernetes manifests

Some example [SciCat](https://scicatproject.github.io/) manifests for deploying on Kubernetes.

These manifests are provided as-is and are an example only - you will need to adapt them before use.

## Secrets

The secrets are handled with [sealed secrets](https://github.com/bitnami-labs/sealed-secrets) - you will need to either fill out the SealedSecrets (values marked with ellipses `...`), use regular Kubernetes Secrets (unencrypted, not suitable for git), or use another secrets solution.

## Manifests description

The manifests are split into backend, frontend, mongodb, network policy, and ingress.