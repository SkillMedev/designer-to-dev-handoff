# Designer-to-Dev Handoff

**For designers handing off to engineers: specs so precise the build matches the design.** — built in-house by [Skill&nbsp;Me](https://skillme.dev).

Reach for this when you're handing a design to engineering and you're tired of the build coming back wrong. It gives you the full handoff toolkit — a single source-of-truth handoff doc, precise redline annotations, and dedicated specs for motion and responsive behavior — plus a QA checklist to verify the implementation before sign-off. The result: fewer Slack round-trips, no guesswork at the design-to-code boundary, and shipped UI that matches intent.

⭐ **If this is useful, star the repo** — it's how we gauge what to build next.

## Install

- **From the catalog:** [skillme.dev/pack/designer-to-dev-handoff](https://skillme.dev/pack/designer-to-dev-handoff) — install the whole pack into Claude in one step.
- **With the skills CLI:** `npx skills add SkillMedev/designer-to-dev-handoff`
- **Manually:** copy any `skills/<slug>/SKILL.md` into your Claude skills directory.

## Skills in this pack

- **[Design QA Checklist](skills/design-qa-checklist/SKILL.md)** — Runs an ordered design QA pass over an implemented UI — layout, type, color, states, motion, content — against the design spec, with concrete tolerances and a filed defect list.
- **[Redline Annotation](skills/redline-annotation/SKILL.md)** — Produces precise redline annotations — spacing, sizing, type, color, radius, z-order, and behavior notes in a consistent, scannable notation — that engineers can build from without asking questions.
- **[Motion Spec](skills/motion-spec/SKILL.md)** — Specifies animation and motion precisely — duration, easing curve, trigger, and intent — for accurate engineer implementation.
- **[Responsive Spec](skills/responsive-spec/SKILL.md)** — Specifies responsive behavior across breakpoints — layout reflow, content priority, touch targets, and fluid-versus-stepped scaling rules — precisely enough for engineers to implement directly.
- **[Design Handoff Doc](skills/design-handoff-doc/SKILL.md)** — Writes a complete design handoff document covering components, design tokens, interaction states, and edge cases for engineering implementation.
- **[Prototype Spec](skills/prototype-spec/SKILL.md)** — Turns a static design into a numbered, testable, dev-ready specification covering every state, interaction, breakpoint, motion detail, and edge case the mockup cannot show.
- **[Component API Design](https://skillme.dev/skill/component-api-design)** — Designs React/Vue component APIs — props, composition, event handling, accessibility. _(external — see source)_
- **[Color Accessibility](skills/color-accessibility/SKILL.md)** — Audits and repairs color palettes against WCAG contrast thresholds — 4.5:1 for body text, 3:1 for large text and UI components, 7:1 for AAA — and makes them safe for color-blind users, delivering a verified pairing table.

## License

MIT — see [LICENSE](LICENSE). Skills are portable `SKILL.md` files; the canonical
copies live in the [Skill&nbsp;Me catalog](https://skillme.dev).
