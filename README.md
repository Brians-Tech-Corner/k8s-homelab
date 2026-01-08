# K8s Homelab

GitOps repository for my Kubernetes homelab cluster.

## Structure

- `apps/` - Application deployments
  - `production/` - Production applications
  - `staging/` - Staging/test applications
- `infrastructure/` - Infrastructure components (cert-manager, monitoring, etc.)
- `argocd/applications/` - ArgoCD Application definitions

## Workflow

1. Make changes in this repo
2. Commit and push to GitHub
3. ArgoCD automatically syncs changes to the cluster
