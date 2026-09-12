# prompt-shelf

Prompt collection: review, SQL, explain, rewrite

## Examples

```bash
# copy a prompt into your system message
cat prompts/senior-reviewer.md
```

## Getting started

```bash
# no dependencies - browse the prompts/ folder
```

## Highlights

- Tested against GPT and Claude models
- Each prompt has usage notes and known failure modes
- One prompt per file, easy to diff and review
- index.json for programmatic access

## Project structure

```text
├── docs/
│   ├── configuration.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── prompts/
│   ├── eli-junior.md
│   ├── rewrite-pass.md
│   ├── senior-reviewer.md
│   └── sql-helper.md
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
└── index.json
```

## Changelog

- `0.1.1` - fix edge case in argument parsing
- `0.1.0` - first working version
