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
- sqs-dashbboard
  - Shows the SQS metics from Cloudwatch that are exported from the [cloudwatch-exporter](https://github.com/skyscrapers/charts/tree/master/cloudwatch-monitoring)
  - Based on [the SQS grafana dashboard](https://grafana.com/dashboards/584) 
  - [Example](./images/sqs-dashboard.png)
