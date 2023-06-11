kubectl port-forward deployment/grafana --namespace local-network-monitoring 3000:3000
kubectl port-forward statefulset/prometheus --namespace local-network-monitoring 9090:9090