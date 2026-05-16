# Filebeat Notes

## Purpose

Filebeat forwards logs into Elasticsearch.

## Monitored Logs

- /var/log/auth.log
- /var/log/syslog
- /tmp/powershell.log

## Validation Commands

```bash
sudo filebeat test config
sudo filebeat test output


---

# sigma-notes.md

```markdown
# Sigma Notes

## Sigma Purpose

Sigma rules are generic SIEM detection rules.

## Benefits

- Platform independent
- Detection engineering
- SOC automation
- Threat detection
