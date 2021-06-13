# Data

Monitor all the things, but in a consistent way.

## Motivation

I want to monitor the following things,

* Cluster
* Pihole
* Unbound
* NAS
* Weather
* Environmental conditions of our house (temperature, door lock state, etc...)

I want to understand,

* How to prevent Johnny drop tables, what permission does Grafana need to do display, what permission does telegraf need and how to implement these in a consistent manner
* How to add new data sources in a consistent manner across namespaces
* How to import existing dashboards into grafana as part of the setup process
* How to develop dashboard for displaying the data that I care about

## References

* (Pihole)<https://jorgedelacruz.uk/2021/01/06/looking-for-the-perfect-dashboard-influxdb-telegraf-and-grafana-part-xxix-monitoring-pi-hole/>
* (Synology)<https://mike-greene.com/blog/2018/6/25/configuring-telegraf-on-a-synology-virtual-machine>
* (influxdata)<https://github.com/influxdata/helm-charts>
* (k8s dashboard)<https://github.com/kubernetes/dashboard>
* (unbound)<https://github.com/influxdata/telegraf/tree/master/plugins/inputs/unbound>
* (K8s InfluxDB Grafana dashboard)<https://medium.com/starschema-blog/monitor-your-infrastructure-with-influxdb-and-grafana-on-kubernetes-a299a0afe3d2>
* (Telegraf: system dashboard)<https://grafana.com/grafana/dashboards/928>
* (K8s Aggregated Container Stats)<https://grafana.com/grafana/dashboards/9111>
