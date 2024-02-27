# EFKP Stack on Kubernetes

## Overview
This project provides the necessary configuration files and instructions to deploy a bare-metal Elastic, Fluentd, Kibana, and Prometheus (EFKP) stack on Kubernetes. This stack is designed to offer a comprehensive monitoring and logging solution that can be used for gathering insights from your Kubernetes clusters.

## Features
- **Elasticsearch**: A distributed, RESTful search and analytics engine capable of addressing a growing number of use cases.
- **Fluentd**: An open-source data collector for unified logging layer, allowing you to unify data collection and consumption for better use and understanding of data.
- **Kibana**: A data visualization and exploration tool used for log and time-series analytics, application monitoring, and operational intelligence use cases.
- **Prometheus**: An open-source monitoring system with a dimensional data model, flexible query language, efficient time series database, and modern alerting approach.

## Prerequisites
- A Kubernetes cluster
- `kubectl` access configured for your cluster
- Basic knowledge of Kubernetes resource and network configurations
- Metrics/telemetry visualizer (to point at prometheus), I used Grafana for my testing

## Installation and Configuration
The setup process involves several steps, from initializing your cluster to deploying each component of the EFKP stack. 

## Usage
Once deployed, you can access Kibana and Prometheus web UIs to explore logs, metrics, and data visualizations. 

## Contributing
Contributions to the project are welcome! 

## License
This project is licensed under the [MIT License](./LICENSE).

## Acknowledgements
- Kubernetes and CNCF Projects
- Elastic.co for Elasticsearch and Kibana
- Fluentd contributors
- Prometheus project contributors
![image](https://github.com/thejerrod/efkpStack/assets/25254103/5b458773-636c-4096-a5db-eb92129996a1)
