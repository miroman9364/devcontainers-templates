# Development Container Templates

This repository contains a set of dev container templates which are source files packaged together that encode configuration for a complete development environment. A Template can be used in a new or existing project, and a [supporting tool](https://containers.dev/supporting) will use the configuration from the template to build a development container.

## Contents

- [`src`](./src) -- A collection of subfolders, each declaring a template. Each subfolder contains at least a `devcontainer-template.json` and a [devcontainer.json](https://containers.dev/implementors/json_reference/).
- [`test`](test) -- Mirroring `src`, a folder-per-template with at least a `test.sh` script. These tests are executed by the [CI](https://github.com/devcontainers/templates/blob/main/.github/workflows/test-pr.yaml).

## Templates

### .NET, TypeScript, and Node

This template combines the official [.NET (dotnet)](https://github.com/devcontainers/templates/tree/main/src/dotnet) template, with the official [Node.js & TypeScript (typescript-node)](https://github.com/devcontainers/templates/tree/main/src/typescript-node) template.

**Note:** The dev container from this template is currently only fully setup for .NET development.
