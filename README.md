# corploc/claude-code-plugins

Claude Code plugins maintained by corploc.

## Plugins

| Plugin | Category | Description |
|--------|----------|-------------|
| `corploc-skills` | security | Pentest workflows (Exegol), diagram generation (FossFLOW) |
| `glm-plugin` | ai | GLM companion — delegate tasks, reviews, and rescue operations to ZhipuAI models |

## Usage

```bash
# Add the marketplace
/plugin marketplace add corploc/claude-code-plugins

# Install a plugin
/plugin install corploc-skills@corploc
/plugin install glm-plugin@corploc
```

## Contributing

PRs welcome.

- **Lightweight plugin** (skills, commands only) → add to `plugins/` in this repo
- **Complex plugin** (hooks, scripts, runtime) → keep in its own repo, reference via GitHub source in `marketplace.json`
