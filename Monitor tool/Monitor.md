# Install Devops Monitoring Tool
install Prometheous:
```bash
wget https://github.com/prometheus/prometheus/releases/download/v3.1.0/prometheus-3.1.0.linux-amd64.tar.gz

tar xvfz -f prometheus-3.1.0.linux-amd64.tar.gz

cd prometheus

./prometheus &
```
install Node Exporter:
```bash
wget https://github.com/prometheus/node_exporter/releases/download/v1.8.2/node_exporter-1.8.2.linux-amd64.tar.gz

tar xvfz -f node_exporter-1.8.2.linux-amd64.tar.gz
cd node_exporter
./node_exporter &
```
install Black Box:
```bash
wget https://github.com/prometheus/blackbox_exporter/releases/download/v0.25.0/blackbox_exporter-0.25.0.linux-amd64.tar.gz

tar xvfz -f blackbox_exporter-0.25.0.linux-amd64.tar.gz
cd blackbox_exporter
./blackbox_exporter &
```
install Grafana:
```bash
wget https://dl.grafana.com/enterprise/release/grafana-enterprise-11.4.0.linux-amd64.tar.gz

tar -zxvf grafana-enterprise-11.4.0.linux-amd64.tar.gz
cd grafana-enterprise
./grafana-server &
```
### Links to download Prometheus, Node_Exporter & black Box exporter https://prometheus.io/download/
### Links to download Grafana https://grafana.com/grafana/download
### Other link from video https://github.com/prometheus/blackbox_exporter

