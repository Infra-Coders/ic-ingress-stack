# ic-ingress-stack

NGINX Ingress Controller stack managed via Flux CD and HelmRelease.

Structure is compatible with:
- kustomize build clusters/base
- kustomize build clusters/dev
- Flux CD kustomize-controller

HelmRepository is placed under clusters/base to satisfy Kustomize load restrictions.
