# CLAUDE.md

<!-- Canonical source: AGENTS.md. This file is auto-generated for Claude Code compatibility. -->

This file provides guidance to AI coding assistants when working with this repository.

## Project Overview

OCM Kafka — container image build scripts for a Kafka and ZooKeeper image used by OCM projects for local development and testing.

## Build Commands

```bash
make image           # Build the container image
make push            # Push the image to registry
make tag             # Tag the image
```

## Key Information

- Dockerfile-based project — no application source code
- Contains scripts to configure and run Kafka + ZooKeeper
- Used as a development dependency by other OCM services
