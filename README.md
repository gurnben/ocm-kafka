# Kafka image for OCM projects

This project contains scripts to build the a image that contains _Kafka_ and
_Debezium_.  This is intended for use in the OCM development environments.

## Installation

Build the container image:

```bash
make image
```

## Usage

Run the Kafka + ZooKeeper container for local development:

```bash
podman run -d --name ocm-kafka -p 9092:9092 quay.io/openshift-online/ocm-kafka:latest
```

Connect to it from your OCM service using `localhost:9092` as the broker address.
