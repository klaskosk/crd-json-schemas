# CRD JSON Schemas 🤖

## Usage

Welcome! 👋 These schemas help you validate your Kubernetes Custom Resource Definitions (CRDs) with tools like the [YAML Language Server extension for VS Code](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml). Just point your `$schema` to the appropriate CRD file in this repository, like so:

```yaml
# yaml-language-server: $schema=https://raw.githubusercontent.com/klaskosk/crd-json-schemas/main/your-crd-name.json
```

Replace `your-crd-name.json` with the actual name of the CRD you're working with!

## Copyright

Copyright 2025 Red Hat. Licensed under [Apache-2.0](./LICENSE).
