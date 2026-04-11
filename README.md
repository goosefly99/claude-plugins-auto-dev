# claude-plugins-auto-dev

Auto-dev branch marketplace for [goosefly99](https://github.com/goosefly99) Claude Code plugins. Mirrors [`claude-plugins`](https://github.com/goosefly99/claude-plugins) but pins every plugin source to its `auto_dev` branch so autonomous development runs can iterate without affecting the stable `main` marketplace.

## Install

```
/plugin marketplace add goosefly99/claude-plugins-auto-dev
/plugin install dev-automation@goosefly99-plugins-auto-dev
/plugin install youtube-mcp@goosefly99-plugins-auto-dev
/plugin install x-api-mcp@goosefly99-plugins-auto-dev
/plugin install synth-mcp@goosefly99-plugins-auto-dev
/plugin install feature-request@goosefly99-plugins-auto-dev
/plugin install concepts-collector@goosefly99-plugins-auto-dev
/plugin install caveman-mode@goosefly99-plugins-auto-dev
/plugin install pipeline-orchestrator@goosefly99-plugins-auto-dev
```

## Plugins

| Name | Description | Source (branch `auto_dev`) |
|---|---|---|
| `dev-automation` | Project design, documentation scaffolding, and autonomous scheduled development tasks | [dev-automation-claude-plugin](https://github.com/goosefly99/dev-automation-claude-plugin/tree/auto_dev) |
| `youtube-mcp` | YouTube search, transcripts, and video analysis | [youtube-mcp-claude-plugin](https://github.com/goosefly99/youtube-mcp-claude-plugin/tree/auto_dev) |
| `x-api-mcp` | X (Twitter) API authenticated crawler/client/query tools | [x-api-mcp-claude-plugin](https://github.com/goosefly99/x-api-mcp-claude-plugin/tree/auto_dev) |
| `synth-mcp` | Research synthesis — load collections, query items, generate design specs | [synth-mcp-claude-plugin](https://github.com/goosefly99/synth-mcp-claude-plugin/tree/auto_dev) |
| `feature-request` | Record feature suggestions into feature_requests.toml | [feature-request-claude-plugin](https://github.com/goosefly99/feature-request-claude-plugin/tree/auto_dev) |
| `concepts-collector` | Load collections, extract key concepts, generate knowledge base overviews | [concepts-collector-claude-plugin](https://github.com/goosefly99/concepts-collector-claude-plugin/tree/auto_dev) |
| `caveman-mode` | Terse-response skill distilled from the viral caveman prompt | [caveman-mode-claude-plugin](https://github.com/goosefly99/caveman-mode-claude-plugin/tree/auto_dev) |
| `pipeline-orchestrator` | Reads pipeline.toml, resolves DAG, manages run state, coordinates research/debate/synth phases | [pipeline-orchestrator-claude-plugin](https://github.com/goosefly99/pipeline-orchestrator-claude-plugin/tree/auto_dev) |
