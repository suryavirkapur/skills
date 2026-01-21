# Skills Collection

A collection of [Amp](https://ampcode.com) skills for development.

## Available Skills

| Skill | Description |
|-------|-------------|
| [solidjs](skills/solidjs/) | Complete SolidJS framework skill covering reactivity, components, stores, routing, and SolidStart |

## Installation

### Using npx (Recommended)

```bash
npx skills add suryavirkapur/skills --skill "solidjs"
```

### Manual Installation

```bash
# Clone and copy
git clone https://github.com/suryavirkapur/skills.git
cp -r skills/skills/solidjs ~/.agents/skills/

# Or symlink
ln -s $(pwd)/skills/solidjs ~/.agents/skills/solidjs
```

## Skill Structure

```
skills/
└── solidjs/
    ├── SKILL.md              # Core: signals, effects, memos, stores, components, control flow
    └── references/
        ├── api_reference.md  # Complete API reference
        ├── patterns.md       # Best practices, custom hooks, testing
        ├── routing.md        # Solid Router guide
        └── solidstart.md     # SolidStart (SSR/SSG/API routes)
```

## What's Included

The **solidjs** skill covers:

- **Reactivity**: Signals, effects, memos, resources
- **Stores**: createStore, produce, reconcile for complex state
- **Components**: Props handling, children, refs, lifecycle
- **Control Flow**: Show, For, Index, Switch/Match, Dynamic, Portal
- **Context API**: Sharing state across components
- **Routing**: Complete Solid Router reference
- **SolidStart**: SSR, SSG, API routes, server functions, middleware
- **Patterns**: Custom hooks, forms, performance, testing, accessibility

## License

MIT
