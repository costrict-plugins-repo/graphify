# graphify — Claude Code Plugin

Turn any codebase into a navigable knowledge graph — code, docs, papers, images, videos — with community detection and query/path/explain tools.

## Installation

```bash
claude marketplace add https://github.com/xixingde/cos-graph
claude plugin install graphify
```

## What This Plugin Provides

### Skill: `/graphify`

Type `/graphify .` to build a knowledge graph from your codebase. Supports 30+ languages, incremental updates, and three output formats (HTML, JSON, Markdown).

### Hooks: PreToolUse Guards

When `graphify-out/graph.json` exists, automatically reminds Claude Code to query the graph before grepping or reading source files.

## License

MIT
