# MeshInfo

Realtime web UI to run against a Meshtastic regional or private mesh network.

## Overview

MeshInfo is written in Python and connects to an MQTT server that is receiving Meshtastic messages for the purpose of visualizing and inspecting traffic. It (currently) uses a filesystem to persist content, such as node info and telemetry. There are plans to optionally support Postgres and SQLite3 as optional persistance storage methods.

To make deployment to run an instance for your mesh easy, Docker support is included. We recommend using Docker Compose using a personalized version of the `docker-compose.yml` file to most easily deploy it, but any seasoned Docker user can also use the Docker image alone.

## Supported Meshtastic Message Types

- neighborinfo
- nodeinfo
- position
- telemetry
- text
- traceroute

## Features

### Current

- Chat
- Map
- Nodes
- Node Neighbors
- Mesh Messages
- MQTT Messages
- Telemetry
- Traceroutes

### Upcoming

- Statistics
- Overview of Routes
