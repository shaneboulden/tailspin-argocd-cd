# OpenShift configuration

ArgoCD provides the `Application` spec required for this workflow. Install OpenShift-GitOps into the cluster to create the custom resource definition.

A manifest has been provided, the cluster will need access to Red Hat Operator Hub.

```
oc apply -f manifests/openshift-gitops.yaml
```