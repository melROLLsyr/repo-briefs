# repo-briefs

My CLAUDE.md and agent instruction files, versioned

Built for my own use; public in case it helps someone.

## What it does

- Global coding-style rules in rules/
- Per-archetype CLAUDE.md templates (api / cli / lib)
- Kept short: agents read every token every time
- Review checklist baked into instructions

## Installation

```bash
# pick a template
cp templates/CLAUDE.api.md your-project/CLAUDE.md
```

## How to use

```bash
# Claude Code reads CLAUDE.md from the repo root automatically
```

## Project structure

```text
├── .github/
│   ├── dependabot.yml
│   └── pull_request_template.md
├── docs/
│   ├── development.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── rules/
│   ├── review.md
│   └── style.md
├── templates/
│   ├── CLAUDE.api.md
│   └── CLAUDE.cli.md
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── Makefile
└── SECURITY.md
```

## Acknowledgments

- README structure inspired by popular OSS templates
- Thanks to everyone opening issues with ideas

## License

MIT licensed, see LICENSE.
