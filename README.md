# total-recall-marketplace

Claude Code marketplace registry for [total-recall](https://github.com/strvmarv/total-recall) — multi-tiered memory and knowledge base for TUI coding assistants.

## Usage

Register this marketplace and install the plugin:

```
/plugin marketplace add strvmarv/total-recall-marketplace
/plugin install total-recall@strvmarv-marketplace
```

## What Gets Installed

The [total-recall](https://github.com/strvmarv/total-recall) plugin, which provides:

- Multi-tiered memory (hot/warm/cold) with semantic search
- Hierarchical knowledge base ingestion
- Automated compaction with decay scoring
- Cross-platform support (Claude Code, Copilot CLI, OpenCode, Cline, Cursor)
- Built-in evaluation framework with synthetic benchmarks
- Zero external dependencies — local SQLite + ONNX embeddings
