# Skills Collection

A collection of [Amp](https://ampcode.com) skills for development.

## Available Skills

| Skill | Description |
|-------|-------------|
| [solidjs](solidjs/) | Complete SolidJS framework skill covering reactivity, components, stores, routing, and SolidStart |

## Installation

```bash
# Copy to Amp skills directory
cp -r solidjs ~/.agents/skills/

# Or symlink
ln -s $(pwd)/solidjs ~/.agents/skills/solidjs
```

## Skill Structure

```
solidjs/
├── SKILL.md              # Main skill (signals, effects, stores, components)
└── references/
    ├── api_reference.md  # Complete API reference
    ├── routing.md        # Solid Router guide
    ├── solidstart.md     # SolidStart (SSR/SSG) guide
    └── patterns.md       # Best practices & patterns
```

## License

MIT
