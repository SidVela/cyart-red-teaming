# Kibana Installation and Configuration

## Objective
Install and configure Kibana dashboard for Elasticsearch monitoring and threat hunting.

## Configuration

```yaml
server.port: 5601
server.host: "localhost"
elasticsearch.hosts: ["https://localhost:9200"]
elasticsearch.username: "elastic"
elasticsearch.ssl.verificationMode: none
```

## Commands Used

```bash
sudo apt install kibana -y
sudo systemctl enable kibana
sudo systemctl start kibana
sudo systemctl status kibana
curl -I http://localhost:5601
```

## Result

Kibana dashboard installed and connected successfully with Elasticsearch.
