# Shapes

A structure-first design system where form emerges from content, space, and motion.

Shapes is not a library of components.
It is a grammar for composing interfaces that are clear, accessible, and consistent across any domain.

---

## How it works

Shapes is organized around two core levels:

| Level   | What it is                                          |
| ------- | --------------------------------------------------- |
| Objects | The nouns. What exists in a system.                 |
| Views   | The expressions. How objects take shape in context. |

Primitives support these levels. They are not building blocks for layout—they exist only to enable clarity and interaction.

Tenets govern how these levels compose. They are not aesthetic preferences. They are rules.

---

## Principles

Shapes is built on a few non-negotiable ideas:

- **Shape emerges from structure**
  Layout, spacing, and hierarchy create form—without relying on containers or decoration.

- **Content defines form**
  Interfaces adapt to content, not the other way around.

- **Typography is the primary material**
  Hierarchy is expressed through type, not UI elements.

- **Space is the only divider**
  Relationships are defined by proximity and rhythm.

- **Motion reveals structure**
  Movement explains how elements relate and change over time.

---

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
├── primitives/
└── views/
    ├── README.md
    ├── list/
    ├── card/
    ├── table/
    └── detail/
```

---

## Views

A view is how an object takes shape in a specific context.

Views are not containers—they are structured expressions of content.

Every object in the [Objects library](https://github.com/reshaped-studio/objects) has corresponding views in Shapes.

| View   | Purpose                                     |
| ------ | ------------------------------------------- |
| List   | Scannable rows, minimal attributes          |
| Card   | Structured grouping, moderate attributes    |
| Table  | Comparative, data-dense                     |
| Detail | Full object, all attributes and actions     |
| Inline | Object referenced within another object     |
| Empty  | Absence of content, expressed intentionally |

---

## Primitives

Primitives are minimal, functional elements used to support interaction and clarity.

They do not define layout or hierarchy.
They do not impose structure on content.

If a primitive begins to shape layout or compete with content, it should be reduced or removed.

---

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines on adding foundations, views, and primitives.

---

Work in this repo uses the shared [Many Hats](https://github.com/reshaped-studio/many-hats) team and the [Design Dash](https://github.com/reshaped-studio/design-dash) workflow, included as submodules. Clone with `--recurse-submodules`. Start at [AGENTS.md](./AGENTS.md).

Part of [Reshaped](https://reshaped.studio)
