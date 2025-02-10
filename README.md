# DEPRECATED
The static deploymet YAML is deprecated and will be removed from future versions of Instana. Deploy Instana monitoring via [Agent operator](https://github.com/instana/instana-agent-operator) or [Agent Helm chart](https://github.com/instana/helm-charts/tree/main/instana-agent).

## Static Instana Agent Kubernetes deployment YAML

Static deployment YAML for Kubernetes and OpenShift with common defaults, rendered from the [Instana Agent Helm chart](https://github.com/instana/helm-charts/tree/main/instana-agent).
For more details on installing Instana agents into your cluster, visit the [official documentation](https://www.ibm.com/docs/en/obi/current?topic=agent-installation-requirements).

### Kubernetes

When deploying on Kubernetes or cloud hosted Kubernetes solutions, use `instana-agent.yaml`.

### OpenShift

When deploying on OpenShift or cloud hosted OpenShift, use `instana-agent-openshift.yaml`.