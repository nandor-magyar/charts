# Whoogle-search

All the credit for the underlying container image goes to:
https://github.com/benbusby/whoogle-search

I have just created a helm chart to make the deployment easier for others and to
get to know Helm a bit more.

**!!WIP:** Packaging is not solved yet.

In order to use this chart: Clone the repository and install with helm using local folder.

## Prerequisites

- Kubernetes 1.16+ (tested only on version 1.19)
- Helm 3+

## Adding a repository

```
helm repo add nandormagyar https://github.com/nandor-magyar/my-charts
```

## Install

```
helm install [RELEASE_NAME] nandormagyar/whoogle
```

## Information

Use helm to get more information about possible configuration values.

```
helm show values nandormagyar/whoogle
```

## Contribute

Any advice or request is appriciated, consider opening submitting an issue or opening a PR.
