# ansible-grafana

An Ansible role for installing [Grafana](http://grafana.org/).

## Role Variables

- `grafana_version` - Grafana version to install (default: `1.9.1`)
- `grafana_prefix` - Directory prefix for Grafana installation (default: `/opt`)
- `grafana_graphite_url` - HTTP endpoint for Graphite (default: `http://localhost:8080`)
- `grafana_elasticsearch_url` - HTTP endpoint for ElasticSearch (default: `http://localhost:9200`)
- `grafana_elasticsearch_index` - ElasticSearch index for Grafana dashboards (default: `grafana-dash`)
- `grafana_search_max_results` - Maximum search results (default: `100`)

## Example Playbook

See the [examples](./examples/) directory.
