# JSON Schemas for C-PAC

## Usage

### VSCode

1. Install [the VSCode YAML extension](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml) 

2. Add the following comment to the first line of your pipeline config:

```YAML
# yaml-language-server: $schema=https://childmindresearch.github.io/cpac-schemas/schemas/cpac.pipeline.1.8.6.dev.json
```

3. Write config with autocomplete, error detection, inline documentation, ...

```YAML
# yaml-language-server: $schema=https://childmindresearch.github.io/cpac-schemas/schemas/cpac.pipeline.1.8.6.dev.json
%YAML 1.1
---

pipeline_setup:
  pipeline_name: my-amazing-pipeline

# ...
```

### Schemas 

Pipeline config

```YAML
# yaml-language-server: $schema=https://childmindresearch.github.io/cpac-schemas/schemas/cpac.pipeline.1.8.6.dev.json
```

Data config

```YAML
# yaml-language-server: $schema=https://childmindresearch.github.io/cpac-schemas/schemas/cpac.data.1.8.6.dev.json
```