# claude-plugins-auto-dev

Auto-dev branch marketplace for [goosefly99](https://github.com/goosefly99) Claude Code plugins. Mirrors [`claude-plugins`](https://github.com/goosefly99/claude-plugins) but pins every plugin source to its `auto_dev` branch so autonomous development runs can iterate without affecting the stable `main` marketplace. Plugin names are suffixed with `-auto-dev` so they can be installed alongside their stable counterparts.

## Install

```
/plugin marketplace add goosefly99/claude-plugins-auto-dev
/plugin install dev-automation-auto-dev@goosefly99-plugins-auto-dev
/plugin install youtube-mcp-auto-dev@goosefly99-plugins-auto-dev
/plugin install x-api-mcp-auto-dev@goosefly99-plugins-auto-dev
/plugin install synth-mcp-auto-dev@goosefly99-plugins-auto-dev
/plugin install feature-request-auto-dev@goosefly99-plugins-auto-dev
/plugin install concepts-collector-auto-dev@goosefly99-plugins-auto-dev
/plugin install caveman-mode-auto-dev@goosefly99-plugins-auto-dev
/plugin install pipeline-orchestrator-auto-dev@goosefly99-plugins-auto-dev
/plugin install agent-knowledgebase-auto-dev@goosefly99-plugins-auto-dev
```

## Plugins

| Name | Description | Source (branch `auto_dev`) |
|---|---|---|
| `dev-automation-auto-dev` | Project design, documentation scaffolding, and autonomous scheduled development tasks | [dev-automation-claude-plugin](https://github.com/goosefly99/dev-automation-claude-plugin/tree/auto_dev) |
| `youtube-mcp-auto-dev` | YouTube search, transcripts, and video analysis | [youtube-mcp-claude-plugin](https://github.com/goosefly99/youtube-mcp-claude-plugin/tree/auto_dev) |
| `x-api-mcp-auto-dev` | X (Twitter) API authenticated crawler/client/query tools | [x-api-mcp-claude-plugin](https://github.com/goosefly99/x-api-mcp-claude-plugin/tree/auto_dev) |
| `synth-mcp-auto-dev` | Research synthesis — load collections, query items, generate design specs | [synth-mcp-claude-plugin](https://github.com/goosefly99/synth-mcp-claude-plugin/tree/auto_dev) |
| `feature-request-auto-dev` | Record feature suggestions into feature_requests.toml | [feature-request-claude-plugin](https://github.com/goosefly99/feature-request-claude-plugin/tree/auto_dev) |
| `concepts-collector-auto-dev` | Load collections, extract key concepts, generate knowledge base overviews | [concepts-collector-claude-plugin](https://github.com/goosefly99/concepts-collector-claude-plugin/tree/auto_dev) |
| `caveman-mode-auto-dev` | Terse-response skill distilled from the viral caveman prompt | [caveman-mode-claude-plugin](https://github.com/goosefly99/caveman-mode-claude-plugin/tree/auto_dev) |
| `pipeline-orchestrator-auto-dev` | Reads pipeline.toml, resolves DAG, manages run state, coordinates research/debate/synth phases | [pipeline-orchestrator-claude-plugin](https://github.com/goosefly99/pipeline-orchestrator-claude-plugin/tree/auto_dev) |
| `agent-knowledgebase-auto-dev` | Ingest sources, build wiki artifacts, query with vector search | [agent-knowledgebase-claude-plugin](https://github.com/goosefly99/agent-knowledgebase-claude-plugin/tree/auto_dev) |
