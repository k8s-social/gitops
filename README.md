![](https://avatars.githubusercontent.com/k8s-social)

# k8s.social - gitops

Collections of app manifests to install k8s.social via gitops

---

Infrastructure kindly provided by [Civo](https://civo.com). 

💙 Thank you Civo!

---

## Includes

- Mastodon
- Monitoring - Prometheus Operator, kube-state-metrics, metrics-server, node-exporter, Alert Manager, Grafana
- Logging - Loki & Promtail
- coredns
- ingress-nginx
- cluster-autoscaler
- redis
- external-dns (currently waiting on the next release that will support Civo)

## Info

ArgoCD is installed into the cluster as part of the [infra](https://github.com/k8s-social/infra) automation which then picks up Apps from [`./manifests/_apps`](./manifests/_apps)
