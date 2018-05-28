# grafana-dashboards

Our grafana dashboards for Kubernetes

## dashboards

- elasticsearch-dashboard (https://grafana.com/dashboards/4358) v3.4
- mongodb-dashboard (https://grafana.com/dashboards/2583)
- webapp-dashboard (https://grafana.com/dashboards/3816)
- k8s-workers-resource-requests-dashboard
  - Shows the resource requests vs. the actual available resources in the cluster worker nodes
  - Based on the Kubernetes resource requests [official dashboard from the Grafana Helm chart](https://github.com/coreos/prometheus-operator/blob/master/helm/grafana/dashboards/kubernetes-resource-requests-dashboard.json)
  - [Example](./images/k8s-workers-resource-requests-dashboard.png)
