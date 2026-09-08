# IT Infrastructure Monitoring and Alerting System

A containerized infrastructure monitoring project built with Prometheus, Grafana, Alertmanager and related monitoring tools.

The project is developed as part of an IT infrastructure internship study and runs entirely in a local lab environment without using any company production systems or confidential data.

## Project Goals

* Monitor Linux system metrics such as CPU, memory, disk and network usage
* Visualize infrastructure metrics through Grafana dashboards
* Monitor application and service availability
* Define infrastructure alert rules
* Generate alerts for abnormal system conditions
* Simulate common infrastructure failure scenarios

## Technologies

* Linux Mint
* Docker
* Docker Compose
* Prometheus
* Grafana
* Alertmanager
* Node Exporter
* Blackbox Exporter

## Current Progress

Prometheus has been deployed successfully using Docker Compose.

Current monitoring target:

* Prometheus self-monitoring

The Prometheus service is available locally on port `9090`.

## Planned Architecture

```text
Linux Host
    |
    +-- Node Exporter
    |
    +-- Docker
         |
         +-- Prometheus
         +-- Grafana
         +-- Alertmanager
         +-- Blackbox Exporter
         +-- Test Services
```

## Project Status

Work in progress.
