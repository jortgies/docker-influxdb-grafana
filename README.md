# Docker-compose files for a simple uptodate
# InfluxDB
# + Grafana stack
# + chronograf

Get the stack (only once):

```
git clone https://github.com/jortgies/docker-influxdb-grafana.git
cd docker-influxdb-grafana
docker pull grafana/grafana
docker pull influxdb
docker pull chronograf
```

Run your stack:

```
docker-compose up -d

```

Show me the logs:

```
docker-compose logs
```

Stop it:

```
docker-compose stop
docker-compose rm
```

Update it:

```
git pull
docker pull grafana/grafana
docker pull influxdb
docker pull chronograf
```
