# Thingsboard MCP Server

## Setup environment using uv

```
# Install uv
curl -LsSf https://astral.sh/uv/install.sh | sh

# Create virtual environment
uv venv

# Activate virtual environment
source .venv/bin/activate
```

## Add environment variables

Create .env file: `cp .env.example .env`

Add the environment variables to allow the MCP server to connect to Thingsboard.


## Install dependencies
```
uv pip install -r pyproject.toml
```

## Run server
```
uv run src/thingsboard.py
```