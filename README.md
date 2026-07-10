## Description
...

## Usage
### General Usage
...
## Installation

To install project dependencies, and install the CLI globally in editable mode:
```bash
make install
```

or

Install the project dependencies:

```bash
uv sync
```

and install the CLI:

```bash
uv tool install -e .
```

Verify the installation:

```bash
cli-name --help
```

To uninstall:

```bash
uv tool uninstall cli-name
```