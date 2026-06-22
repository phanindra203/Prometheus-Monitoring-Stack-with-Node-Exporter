# Setup Guide

## Download Prometheus

Download Prometheus and extract the archive.

## Start Prometheus

```bash
./prometheus --config.file=prometheus.yml

Prometheus UI:
http://localhost:9090
Download Node Exporter
Download Node Exporter and extract the archive.
Start Node Exporter
./node_exporter
Node Exporter metrics endpoint:
http://localhost:9100/metrics
Verify Connectivity
Open:
http://localhost:9090/targets
Expected Result:
prometheus = UP
node-exporter = UP
Test Queries
up
node_cpu_seconds_total
node_memory_MemAvailable_bytes

---

# 4. .gitignore

```text
.DS_Store
*.log
*.db
