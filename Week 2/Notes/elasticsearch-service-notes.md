# Elasticsearch Service Configuration

## Objective
Configure and start Elasticsearch service for threat hunting setup.

## Configuration Changes

### Elasticsearch Network Configuration

```yaml
network.host: localhost
http.port: 9200
```

### JVM Memory Configuration

```text
-Xms2g
-Xmx2g
```

## Commands Used

```bash
sudo systemctl daemon-reload
sudo systemctl enable elasticsearch
sudo systemctl start elasticsearch
sudo systemctl status elasticsearch
curl -X GET "localhost:9200"
```

## Result

Elasticsearch service started successfully and responded on localhost port 9200.
