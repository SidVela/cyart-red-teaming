# Detection Engineering Notes

## Objective
Create detection rules and alerts using Kibana and Elasticsearch.

## Environment
- Elasticsearch
- Kibana
- Filebeat
- Linux Syslog Monitoring

## Detection Goals
- Failed login detection
- Suspicious command execution
- Reconnaissance activity
- IOC monitoring

## Workflow
Logs → Filebeat → Elasticsearch → Kibana → Detection Rules → Alerts
