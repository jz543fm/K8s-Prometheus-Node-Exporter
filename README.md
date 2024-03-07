# Prometheus Node Exporter for K8s

Repository contains `DaemonSet` and `ServiceAccount`.

Daemonset will deploy on your node/s in K8s cluster prometheus/node-exporter pod/s that will export metrics on port `9600`

Do not forget to update `namespace, name`, because I have default name `prometheus-node-exporter-example` and namespace: `node-exporter`, update also args in DaemonSet by your demands what you want to collect by Prometheus Node Exporter, and do not forget also update `serviceAccount` and `serviceAccountName` or port!

# Docs

[Github prometheus/node-exporter](https://github.com/prometheus/node_exporter)

# Docker Hub

[Node Exporter Releases](https://hub.docker.com/r/prom/node-exporter/tags)