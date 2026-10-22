# Maintaining this library

This repository is a prompt library. Keep entries useful to a first-time user and clear about the work the prompt can and cannot do.

## Add an assistant

1. Add a new entry to `data/assistants.json` with a stable unique `number` and `slug`, a truthful task category and summary, reviewed English and Arabic setup guidance, concrete fictional first-message examples, model/tool guidance, expected output, and the complete original prompt.
2. Preserve the prompt in its original language. Do not claim that prompts run a model, connect to accounts, or produce media unless the project actually includes those capabilities.
3. Use fictional example details; do not add customer names, private data, invented performance metrics, or unsupported claims.
4. Regenerate the human-readable guides and indexes with `python tools/build_catalog.py`.
5. Review changed guides, prompt files, catalog links, and portfolio links before publishing.

For a different kind of project, create a focused repository rather than adding unrelated material here.
