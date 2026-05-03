# City Governance Dashboard

A real-time City Governance Dashboard hosted on AWS EC2 using Nginx, with Firebase Firestore as the backend database.

## Features

- Real-time issue reporting
- Username-based issue creation
- Delete issue functionality
- Open/Resolved status toggle
- Green tick for resolved issues
- Hosted on AWS EC2
- Served using Nginx
- Infrastructure monitoring using Node Exporter, Prometheus, and Grafana

## Tech Stack

- HTML
- JavaScript
- Firebase Firestore
- AWS EC2
- Nginx
- Prometheus
- Grafana
- Node Exporter

## Monitoring Setup

A separate EC2 instance was configured as a monitoring server.

- Node Exporter exposes Linux system metrics on port 9100
- Prometheus scrapes metrics from Node Exporter on port 9090
- Grafana visualizes CPU, memory, disk, network, and uptime metrics on port 3000

## Verification

- Website verified using browser access
- Nginx access logs checked using `/var/log/nginx/access.log`
- HTTP response verified using `curl -I`
- Prometheus target verified as `UP`
- Grafana dashboard configured successfully

## Project Summary

This project demonstrates cloud hosting, real-time database integration, CRUD functionality, Linux server deployment, Nginx configuration, and infrastructure monitoring.# City Governance Dashboard

A real-time City Governance Dashboard hosted on AWS EC2 using Nginx, with Firebase Firestore as the backend database.

## Features

- Real-time issue reporting
- Username-based issue creation
- Delete issue functionality
- Open/Resolved status toggle
- Green tick for resolved issues
- Hosted on AWS EC2
- Served using Nginx
- Infrastructure monitoring using Node Exporter, Prometheus, and Grafana

## Tech Stack

- HTML
- JavaScript
- Firebase Firestore
- AWS EC2
- Nginx
- Prometheus
- Grafana
- Node Exporter

## Monitoring Setup

A separate EC2 instance was configured as a monitoring server.

- Node Exporter exposes Linux system metrics on port 9100
- Prometheus scrapes metrics from Node Exporter on port 9090
- Grafana visualizes CPU, memory, disk, network, and uptime metrics on port 3000

## Verification

- Website verified using browser access
- Nginx access logs checked using `/var/log/nginx/access.log`
- HTTP response verified using `curl -I`
- Prometheus target verified as `UP`
- Grafana dashboard configured successfully

## Project Summary

This project demonstrates cloud hosting, real-time database integration, CRUD functionality, Linux server deployment, Nginx configuration, and infrastructure monitoring.
