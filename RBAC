# Kubernetes Role Definition

This document contains the YAML definition for a Kubernetes Role that grants specific permissions in the `webapps` namespace.

## Role Definition

```yaml
apiVersion: rbac.authorization.k8s.io/v1
kind: Role
metadata:
  name: app-role
  namespace: webapps
rules:
  - apiGroups:
      - ""
      - apps
      - autoscaling
      - batch
      - extensions
      - policy
      - rbac.authorization.k8s.io
    resources:
      - pods
      - secrets
      - configmaps
      - deployments
      - services
    verbs: ["get", "list", "watch", "create", "update", "patch", "delete"]


