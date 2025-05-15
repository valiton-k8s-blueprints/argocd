# ArgoCD Application(Set) Definitions for Blueprint

This repository contains application set definitions and configuration for 
the applications that can be installed by the blueprint.

Metadata from the cloud infrastructure is supplied via the GitOps bridge
cluster secret metadata.

Application definitions can be found in the ```applications``` directory with cloud 
provider specific applications in the respective sub folder.

The ```config``` directory contains helm value files for different configurations, 
namely environments and cloud provider. We first apply the ```values.yaml```, then the 
environment specific file and lastly the cloud provider specific file.
