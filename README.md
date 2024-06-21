[![tests](https://github.com/kyletaylored/ddev-datadog/actions/workflows/tests.yml/badge.svg)](https://github.com/kyletaylored/ddev-datadog/actions/workflows/tests.yml) ![project is maintained](https://img.shields.io/maintenance/yes/2024.svg)

# ddev-datadog

## What is this?
This repository allows you to quickly install the Datadog agent into a DDEV project using just `ddev get kyletaylored/ddev-datadog`.

## Installation
```
ddev get kyletaylored/ddev-redis
ddev restart
```

## Explanation
This recipe for DDEV installs a `.ddev/docker-compose.datadog.yaml` using the Datadog agent Docker image.

## Interacting with the agent
- The agent is running as a sidecar container along the other services.
- The APM instrumentation is automated, so no need to install other libraries.
- You can also run agent commands directly on the command-line, e.g., `ddev datadog status`.

**Contributed and maintained by [@kyletaylored](https://github.com/kyletaylored)**
