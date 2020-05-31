# k8s-gitops-manifests

[![test](https://github.com/bcochofel/k8s-gitops-manifests/workflows/test/badge.svg)](https://github.com/bcochofel/k8s-gitops-manifests/blob/master/.github/workflows/test.yml)
[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)](https://github.com/pre-commit/pre-commit)
[![GitHub license](https://img.shields.io/github/license/bcochofel/k8s-gitops-manifests.svg)](https://github.com/bcochofel/k8s-gitops-manifests/blob/master/LICENSE)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/bcochofel/k8s-gitops-manifests)](https://github.com/bcochofel/k8s-gitops-manifests/tags)
[![GitHub issues](https://img.shields.io/github/issues/bcochofel/k8s-gitops-manifests.svg)](https://github.com/bcochofel/k8s-gitops-manifests/issues/)
[![GitHub forks](https://img.shields.io/github/forks/bcochofel/k8s-gitops-manifests.svg?style=social&label=Fork&maxAge=2592000)](https://github.com/bcochofel/k8s-gitops-manifests/network/)
[![GitHub stars](https://img.shields.io/github/stars/bcochofel/k8s-gitops-manifests.svg?style=social&label=Star&maxAge=2592000)](https://github.com/bcochofel/k8s-gitops-manifests/stargazers/)

Kubernetes manifests that can be used with GitOps.
Most of the manifests use Helm Operator, so you need to have that installed on your cluster.

## Requirements

The scenarios under `kustomize/` use [Kustomize](https://github.com/kubernetes-sigs/kustomize).

The directory `manifests/` uses [Helm Operator](https://github.com/fluxcd/helm-operator).
