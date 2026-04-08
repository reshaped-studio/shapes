# Shapes

The Reshaped design system. A grammar for composing interfaces that are intuitive, accessible, and consistent across any domain.

## How it works

Shapes is organized around three levels:

| Level | What it is |
|---|---|
| Objects | The nouns. What exists in a system. |
| Components | The vocabulary. Visual building blocks. |
| Views | The sentences. How objects express in context. |

Tenets govern how these levels compose. They are not aesthetic preferences. They are rules.

## Structure

```
shapes/
├── tenets/
│   └── tenets.md
├── foundations/
│   ├── typography.md
│   ├── color.md
│   ├── spacing.md
│   ├── accessibility.md
│   └── motion.md
├── components/
└── views/
    ├── README.md
    ├── list/
    ├── card/
    ├── table/
    └── detail/
```

## Views

A view is how an object expresses itself in a specific context. Every object in the [Objects library](https://github.com/reshaped-studio/objects) has corresponding views in Shapes.

| View | Purpose |
|---|---|
| List | Scannable rows, minimal attributes |
| Card | Visual hierarchy, moderate attributes |
| Table | Comparative, data-dense |
| Detail | Full object, all attributes and CTAs |
| Inline | Object referenced inside another object |
| Empty | Absence state |

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines on adding components and views.

---

Part of [Reshaped](https://reshaped.studio)
