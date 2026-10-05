# Views

A view is how an object expresses itself in a specific context. Every view maps to one or more objects in the [Objects library](https://github.com/reshaped-studio/objects).

Views are not generic layouts. Each view is defined for a specific object in a specific context.

## View types

| View | Purpose |
|---|---|
| List | Scannable rows. The user is looking across many instances. Minimal attributes. |
| Card | Visual hierarchy. Moderate attributes. Suitable for grid or mixed-density layouts. |
| Table | Comparative, data-dense. Suitable when users need to scan across attributes. |
| Detail | Full object. All relevant attributes and available actions. |

## Structure

Each view directory contains one file per object-context pair.

```
views/
├── list/
├── card/
├── table/
└── detail/
```

## Creating a view

A view must have a corresponding object definition in the Objects library before it can be designed. Do not design a view for an object that has not been defined.
