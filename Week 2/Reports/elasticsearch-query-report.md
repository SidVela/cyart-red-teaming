# Elasticsearch Query Conversion Report

## Objective
Convert Sigma PowerShell detection rule into Elasticsearch-compatible query format.

## Sigma Rule

```yaml
title: Suspicious PowerShell Activity

detection:
  selection:
    Image|endswith: '\powershell.exe'
    CommandLine|contains: '-Command'

condition: selection
```

## Simulated Elasticsearch Query

```json
{
  "query": {
    "bool": {
      "must": [
        {
          "wildcard": {
            "Image.keyword": "*\\powershell.exe"
          }
        },
        {
          "match": {
            "CommandLine": "-Command"
          }
        }
      ]
    }
  }
}
```

## Result

Sigma detection rule mapped successfully into Elasticsearch query logic.# Elasticsearch Query Conversion Report

## Objective
Convert Sigma PowerShell detection rule into Elasticsearch query format.

## Command Used

```bash
sigma convert -t elasticsearch powershell-detection.yml
```

## Generated Elasticsearch Query

PASTE_QUERY_OUTPUT_HERE

## Result

Sigma rule successfully converted into Elasticsearch-compatible query format.# Elasticsearch Query Conversion Report

## Objective
Convert Sigma PowerShell detection rule into Elasticsearch query format.

## Command Used

```bash
sigma convert -t elasticsearch powershell-detection.yml
```

## Generated Elasticsearch Query

PASTE_QUERY_OUTPUT_HERE

## Result

Sigma rule successfully converted into Elasticsearch-compatible query format.
