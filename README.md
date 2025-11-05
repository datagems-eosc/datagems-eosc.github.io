# DataGEMS Documentation Router

This repository contains the links to the documentation for all DataGEMS components.

[https://datagems-eosc.github.io/](https://datagems-eosc.github.io/)

## Setup

1. Create a virtual environment:
   ```bash
   python3 -m venv .venv
   ```

2. Activate the virtual environment:
   ```bash
   source .venv/bin/activate
   ```

3. Install dependencies:
   ```bash
   pip install mkdocs mkdocs-material mike neoteroi-mkdocs pymdown-extensions
   ```

## Serve Documentation

To serve the documentation locally on port 8002:
```bash
cd docs;
mkdocs serve -a localhost:8002
```

