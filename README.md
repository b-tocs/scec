# SAP Cloud Edge Connector

Simple IoT Stack for Docker Conpose to connect an edge scenario to SAP BTP.

Status ALPHA

# Variants and Components

## Available variants

| variant | description                                     |
| ------- | ----------------------------------------------- |
| default | Default: scc + mosquitto + nodered              |


## Used components matrix

| Component | default |  scco  | 
| --------- | ------- | ------ |
| traefik   |   (X)   |        |
| nodered   |    X    |        |
| mosquitto |    X    |        |
| scc       |    X    |        |
| influxdb  |         |        |
| kafka     |         |        |
| kafka-ui  |         |        |


# Documentation

- Templates
    - [SAP Cloud Connector](templates/scc/README.md)


# Prereqisites

The following tools are used:
- Docker
- Make

Install the required tools for your platform.


# Thank You!

This repository was inspired by:
- Christian Drumm: [Simple IoT Stack](https://github.com/ceedee666/simple-iot-stack)
- Nabi Zamani: [Docker Image for SAP Cloud Connector](https://github.com/nzamani/sap-cloud-connector-docker)

Thank You!