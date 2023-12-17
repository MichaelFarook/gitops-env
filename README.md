# GitOps Repository for ArgoCD

This is the example of my GitOps repository! This repository servers as an illustration of GitOps practices for managing ArgoCD applications.

## Overview

This repository is structured as follows:

- 'applications/': Contains Kubernetes manifests in Helm Chart structure for ArgoCD applications Namespace and SecretsManager. Have unified structure for two environments.
- 'enivornments/': Environment folder with all provided files and manifests for my environments.
- 'environments/production/': The two folders of environments is the same by the structure and files. Here is the applications manifest of ArgoCD app_of_apps - "app.yaml" and "values.yaml" file with global values and values of branc and version of applications.
- 'environments/produciton/environments-values': Folder with values file for application to make orverwride from GitOps repo.

## Prerequisites

Before getting started, make sure you have the following tools installed:

- [kubectl]:(https://kubernetes.io/docs/tasks/tools/install-kubectl/): Kubernetes command-line tool.
- [ArgoCD]:(https://argo-cd.readthedocs.io/en/stable/cli_installation/): Argocd, need to use version >2.5.0
