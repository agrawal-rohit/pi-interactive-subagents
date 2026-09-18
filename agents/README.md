# Agents

This package ships **no** built-in agent profiles.

Define agents as `.md` files with YAML frontmatter in:

- **Project:** `.pi/agents/`
- **Global:** `~/.pi/agent/agents/`

Discovery priority: **project > global > package** (this folder). Drop optional package-level agents here only if you intentionally want them available to every consumer of a fork.

See the root README for the frontmatter reference.
