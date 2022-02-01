# compose-examples
Bunch of simple docker-compose files and bash scripts

## Quick Start
- Clone this repo
```bash
git clone https://github.com/VorobevPavel-dev/compose-examples.git
```
- ```cd``` to project
- Run ```docker-compose up -d```

## Versions
| Application | Image Version / Tag |
| :----: | :----: |
| Grafana | [8.3.4](https://grafana.com/docs/grafana/next/release-notes/release-notes-8-3-4/) |
| InfluxDB | [2.1.1](https://docs.influxdata.com/influxdb/v2.1/reference/release-notes/influxdb/) |
| Jenkins | latest |

## influx-monitoring
Allows you to setup [InfluxDB](https://www.influxdata.com/) and [Grafana](https://grafana.com/) in a single network. Will create directories for persisent data.

## jenkins
Will create jenkins-master (blueocean version) container.