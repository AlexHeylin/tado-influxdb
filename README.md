# tado-influxdb
A little helper script to get measurements from Tado to InfluxDB.

## Config
Before running the script you must create a config.py (see examples/config.py
for an example). The script will not work properly otherwise.

## Running on Docker / Kubernetes
This repo includes a Dockerfile (builds to cbeneke/tado-influxdb:latest) and a
Kubernetes Deployment yaml example. If you want to run on Kubernetes, change the
username/password secret and configure your influx-service in the
tado-influx-config configmap.
