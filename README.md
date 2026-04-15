# vlt

A personal query vault. Store, search, and retrieve reusable queries from your terminal.

## Install

```bash
go install github.com/JeremyCurmi/vlt/cmd/vlt@latest
```

## Usage

```bash
# Interactive fuzzy search
vlt

# Add a query
vlt add --name "My query" --body "SELECT * FROM users" --tags mysql,users

# List all queries
vlt list
```

## Storage

Queries are stored in `~/.vlt/queries.yaml`. Override with `VLT_STORE` environment variable.
