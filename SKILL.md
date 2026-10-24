---
name: brain-get
description: >-
  Retrieves the full, untruncated content and metadata of a specific Second Brain
  memory by its unique ID. Use when the user types /brain-get <id> or when a recall
  result shows [truncated ...] and the full content is needed. Executes immediately,
  no approval needed.
---

# Brain Get — Retrieve Full Memory (`/brain-get`)

Execute **immediately** by calling the `second-brain` MCP `get` tool. No approval needed.

## Syntax

```
/brain-get <id>
```

- `id`: The unique memory ID (e.g. `mem_8f93a1`, shown in recall/recent results)

## Execution

Call `get(id: "<id>")` and display the full untruncated content with all metadata:
- Title, content, tags, volatility, source, created_at, updated_at, status

## Examples

```
/brain-get mem_8f93a1
/brain-get mem_abc123
```
