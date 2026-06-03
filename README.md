# Practical Quantum Research on IBM **Heron R2

This repository contains the code and resources for practical quantum research 
conducted on IBM's Heron R2 quantum computer. 

The research focuses on exploring various quantum algorithms, 
error mitigation techniques, and applications of quantum computing in different domains.

https://quantum.cloud.ibm.com/composer

** Work In Progress **

## Contents

- Pure Qiskit benchmark
- QDK QIR benchmark

** Work In Progress **

## Setup

We will use *UV* for package management this time. There are also `pip` compatible
`requirements.txt`. See https://docs.astral.sh/uv/getting-started/installation/ for details.

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```
or
```bash
pip install uv
```

After that the dependencies are synced and managed automatically from the `pyproject.toml` file.

```bash
uv sync
source .venv/bin/activate
uv run jupyter notebook 100-bell-to-ghz-on-ibm-heron.ipynb
```

