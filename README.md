# selfhost-stack

This repository contains the Docker Compose files, configuration files, and supporting resources for the services running in my self-hosted environment. It acts as a central place to maintain infrastructure, keep configurations version-controlled, and document changes as the stack evolves.

The repository is organized by service, with each directory containing everything required for that particular deployment. While some services are independent, others are intended to work together as part of a larger ecosystem for media management, AI workloads, monitoring, dashboards, and other self-hosted applications.

Configurations are updated over time as services are added, migrated, or reconfigured. Keeping everything in a single repository makes it easier to track changes, experiment with new deployments, and maintain consistency across different hosts and environments.

The stack currently includes services such as the ARR suite, Ollama, Prometheus, and Glance, with additional services and infrastructure components being added as the homelab continues to grow.
