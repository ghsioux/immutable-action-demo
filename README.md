# Immutable Action Demo

A simple GitHub Immutable Action that prints shinobi messages to the standard output, and associated workflow to use it.

## Usage

```yaml
name: Hello Shinobi Workflow
on: [push]
jobs:
  hello_shinobi_job:
    runs-on: ubuntu-latest
    steps:
      - name: Hello Shinobi
        uses: ghsioux/immutable-action-demo@1.0.0
```