# Challenge 03 - Introduction To Kubernetes

[< Previous Challenge](./Challenge-02.md) - **[Home](../README.md)** - [Next Challenge >](./Challenge-04.md)

## Introduction

Connect to your Kubernetes cluster and set the default namespace.

## Description

In this challenge we will connect to your pre-provisioned Azure Kubernetes Service (AKS) cluster and set the default namespace to the one allocated for your team. This will give us an opportunity to learn how to use the `kubectl` kubernetes command line tool, as well as using the Azure CLI to issue commands to AKS.

- Install the Kubernetes command line tool (`kubectl`).
	- **Hint:** This can be done easily with the Azure CLI
- Connect to your cluster and set your default namespace
    - **Hint:** your default namespace is your team name (e.g. "Team1")
Once connected:
- Use kubectl to view existing namespaces.
- Use kubectl to examine available nodes.
- **Optional:** Bring up the AKS "Workloads" screen in the Azure portal.
	- **Hint:** Again, the Azure CLI makes this very easy with one command.
	- **NOTE:** This will not work if you are using a Linux jump box to connect to your cluster.

## Success Criteria

1. The kubectl CLI is installed.
1. Show that a multi-node AKS kubernetes cluster exists.
1. Show that your context has the correct default namespace.

## Learning Resources

- [Azure CLI Reference](https://learn.microsoft.com/en-us/cli/azure/aks?view=azure-cli-latest)
- [kubectl Reference](https://kubernetes.io/docs/reference/generated/kubectl/kubectl-commands)
