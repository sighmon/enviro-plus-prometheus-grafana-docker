# Enviro+, Prometheus, Grafana docker-compose

An enviro+ air quality sensor, Prometheus &amp; Grafana multi-container using Docker compose.

## Based on these projects

* [Enviro+ on Docker](https://github.com/sighmon/balena-enviro-plus)
* [Prometheus/Grafana on Docker for Arm](https://github.com/sighmon/prometheus-grafana-raspberry-pi)

## Run

* Build and run `docker-compose up --build`
* Or run in the background `docker-compose up -d`

## TODO

- [x] Submodule Enviro+
- [x] Setup docker-compose.yml with Prometheus/Grafana
- [ ] Modify storage location for Balena (/data)
- [ ] Test multi-deployments & environment variable setting
