# Grafana Influxdb and Telegraf(TIG stuck setup using docker)
> Short blurb about what your product does.

[![Grafana Version][grafana-image]][grafana-url]
[![InfluxDB Version][influx-image]][influxdb-url]
[![Telexgraf Version][telegraf-image]][telegraf-url]

Installation for grafana telegraf and influxdb using docker docker-compose.

![](header.png)

## Installation

Docker docker-compose:

```sh
git clone https://github.com/natty98282/tig_stuck_docker_compose.git
```

```sh
cd tig_stuck_docker_compose
```

```sh
docker compose up
```

## Usage example

access grfana using http://localhost:3000
access influxdb using http://localhost:8086

configure telegraf conf based on ur influxdb credential, to check ur influxdb container ip use [docker inspect influxdb]


## Meta

Natnael Tadesse – natty98282@gmail.com


<!-- Markdown link & img dfn's -->
[grafana-image]: http://www.w3.org/2000/svg
[grafana-url]: https://hub.docker.com/r/grafana/grafana
[influxdb-url]: https://hub.docker.com/_/influxdb
[wiki]: https://github.com/yourname/yourproject/wiki

