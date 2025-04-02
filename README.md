# Algorand - Grafana Community Dashboard

## Overview
This repository contains a Grafana dashboard template (JSON format) designed for monitoring Algorand nodes.
The dashboard provides real-time metrics and performance data visualisations for node operators.

![Template Screenshot](images/Template-Screenshot.png)

## Technical Details
The dashboard template utilises Prometheus as its data source, the Prometheus server needs to be setup to target port 9100 on the Algorand node and collect metrics from the `/metrics` endpoint.

## Prerequisites
- Grafana (v11.3.0+)
- Prometheus server configured to scrape metrics from your Algorand node
- Algorand node with metrics enabled

## Installation
1. Download or copy the JSON template from this repository
2. Import the template into your Grafana instance:
   - Navigate to Dashboards -> New -> Import
   - Upload the JSON file or paste its contents
   - Configure the Prometheus data source connection
   - Save the dashboard

## Configuration
The dashboard is designed to work with minimal configuration, but you may need to adjust:
- Prometheus data source settings
- Time ranges for historical data display
