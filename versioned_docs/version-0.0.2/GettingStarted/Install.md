---
title: Installation
type: docs
weight: 1
---

## Python Package
Install via pip, then use as [documented here](./Python.md)
```
pip install lingodb
```

## Docker Image
You can build the docker image yourself using `make build-docker`

## Building from source
1. Ensure you have a machine with sufficient compute power and space
1. Make sure that you have the following build dependencies installed:
    1. Python3.10 or higher
    1. standard build tools, including `cmake` and `Ninja`
1. Build LingoDB
    * Debug Version : `make build-debug` (will create binaries under `build/lingodb-debug`)
    * Release Version : `make build-release` (will create binaries under `build/lingodb-release`)
1. Run test: `make run-test`

