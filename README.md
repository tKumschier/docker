# Readme

This repository contains several folders with `docker-compose.yml` files and corresponding `.env` files for various applications.

## Applications
### heater_downloader
Docker image with a custom script to download heater data and store it in InfluxDB.

### iobroker
`ioBroker` is an open-source home automation platform that integrates various smart devices, protocols and services into a unified interface. With ioBroker, IOT devices can be monitored, controlled and automated, including lighting, heating, security systems and more, all from a single dashboard.

### nginx-proxy-manager
`nginx-proxy-manager` simplifies the management of nginx reverse proxies with a web interface. This allows various Docker services on a shared server to be accessed easily via the browser.

### pihole
Pi-hole is a network-wide ad blocker and thus blocks ads for all devices connected to the network. Security can be increased by blocking entire domains (such as `.zip`).

### registry
The Docker image `registry` provides a lightweight and scalable solution for hosting private Docker registries. It allows Docker images to be securely stored, distributed and managed in their own infrastructure, enabling efficient deployment and version control of containerized applications. With the help of `docker-registry-ui` a web interface is provided.

### tig-stack
This folder contains various docker images:
- `Telegraf`: Telegraf is an open-source agent for collecting and reporting metrics and data from various sources, making it easy to monitor and analyze system performance.
- `Grafana`: Grafana is a leading open-source platform for monitoring and observability, allowing users to visualize and analyze time-series data from multiple sources in customizable dashboards.
- `InfluxDB`: InfluxDB is a powerful time-series database designed to handle high volumes of time-stamped data, making it ideal for storing and querying metrics, events, and logs.

### youtube_analyzer
Docker image with a custom script to download metadata from youtube videos and store it in influxdb.
