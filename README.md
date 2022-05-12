# eniworks-kubernetes
A repository to hold kubernetes manifests deployed by argo

## argo-research

This is where I am testing apps that aren't "prod" ready.

## argo

This is where all the argo app manifests live. They function as an abstract deployment spec and point to the real deployment.

### apps

This is where I deploy projects to my cluster that are separate from the infrastructure.

### infra

This holds all the deployments that make up my infrastructure. We have a little bit of everything prom, elk, nfs, ingress, you name it.

## kubernetes

This is where the real deployment manifests live.
