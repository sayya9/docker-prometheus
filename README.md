# Introduction
Here is a Docker Compose file that you can use to set up Prometheus and Grafana using Docker.

This Docker Compose file defines 6 services:
+ Prometheus
+ Grafana
+ Alertmanager
+ Node Exporter
+ Blackbox Exporter
+ prom2teams

# Prerequisites
Before getting started with installing Prometheus Stack. Please make sure you have installed docker and docker-compose on your Docker host machine.

# Installation
+ Replace the variable `PROM2TEAMS_CONNECTOR` with your connector URL in the docker-compose.yml.
+ Replace the IP and port 192.168.0.3:9115 with your blackbox exporter's real hostname:port in the prometheus/prometheus.yml.
```
docker-compose up -d
```
