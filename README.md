# 🚀 System Monitoring using Prometheus & Grafana

## 📌 Project Overview

This project demonstrates system monitoring using Prometheus and Grafana.

## 🛠️ Tools Used

* Prometheus
* Grafana
* Node Exporter

## ⚙️ Setup Steps

### 1. Install Node Exporter

```bash
wget https://github.com/prometheus/node_exporter/releases/download/v1.10.2/node_exporter-1.10.2.linux-amd64.tar.gz
tar -xvf node_exporter-1.10.2.linux-amd64.tar.gz
cd node_exporter-1.10.2.linux-amd64
./node_exporter
```

### 2. Install Prometheus

```bash
wget https://github.com/prometheus/prometheus/releases/download/v2.53.0/prometheus-2.53.0.linux-amd64.tar.gz
tar -xvf prometheus-2.53.0.linux-amd64.tar.gz
cd prometheus-2.53.0.linux-amd64
./prometheus --config.file=prometheus.yml
```

### 3. Install Grafana

```bash
sudo apt update
sudo apt install grafana
sudo systemctl start grafana-server
```

## 📊 Dashboard

Imported Grafana dashboard ID: 1860 (Node Exporter Full)

## 🎯 Outcome

* Monitored CPU, Memory, Disk, Network
* Visualized real-time metrics using Grafana

## 💼 Use Case

Useful for DevOps monitoring and alerting systems.
