# ArgoCD Application(Set) Definitions for Blueprint

This repository contains application set definitions for the addons of 
the blueprint.

Metadata from the cloud infrastructure is supplied via the GitOps bridge
cluster secret metadata.

Application definitions that apply only to a certain cloud provider a placed in 
sub directories.

The ```config``` directory contains helm yaml files for different configuration, 
namely environments and cloud provider.
