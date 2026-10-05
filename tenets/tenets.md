# Tenets

These are not preferences. They are rules that govern all design decisions in Shapes.

They are applied in order.

---

## Inclusive

Design for the hardest case first.

If it works for someone with low literacy, limited vision, low bandwidth, or low trust, it works for everyone.

This means:

- accessible markup by default
- readable type at all sizes
- clear hierarchy without reliance on color or decoration
- plain language with no assumed familiarity

If a decision improves clarity for most users but reduces accessibility for some, it is rejected.

---

## Structural

Clarity comes from structure, not components.

Hierarchy must be expressed through:

- typography
- spacing
- alignment

Not through containers, borders, or visual decoration.

If structure cannot be understood without added UI, the structure is wrong.

---

## Intuitive

Understanding should be immediate, not learned.

No feature earns its place without a clear user need.
No pattern earns its place if it requires explanation.

When multiple solutions exist:

- prefer the one that reduces cognitive effort
- prefer the one that relies on recognition over recall

Hidden complexity is acceptable.
Visible complexity is not.

---

## Iterative

Everything ships at the smallest size that can produce learning.

No system is designed in the abstract.
No pattern is finalized without real use.

Ship:

- the minimum structure needed
- with real content
- to answer a real question

Then revise based on evidence.

Completeness is not a goal. Clarity is.

---

These tenets apply in order.

If a decision improves structure but reduces accessibility, it is rejected.
If a decision improves intuition but breaks structure, it is rejected.

Inclusivity always wins.
