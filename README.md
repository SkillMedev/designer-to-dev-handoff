# Designer-to-Dev Handoff

**For designers handing off to engineers: specs so precise the build matches the design.** — built in-house by [Skill&nbsp;Me](https://skillme.dev).

Reach for this when you're handing a design to engineering and you're tired of the build coming back wrong. It gives you the full handoff toolkit — a single source-of-truth handoff doc, precise redline annotations, and dedicated specs for motion and responsive behavior — plus a QA checklist to verify the implementation before sign-off. The result: fewer Slack round-trips, no guesswork at the design-to-code boundary, and shipped UI that matches intent.

⭐ **If this is useful, star the repo** — it's how we gauge what to build next.

## Install

- **From the catalog:** [skillme.dev/pack/designer-to-dev-handoff](https://skillme.dev/pack/designer-to-dev-handoff) — install the whole pack into Claude in one step.
- **With the skills CLI:** `npx skills add SkillMedev/designer-to-dev-handoff`
- **Manually:** copy any `skills/<slug>/SKILL.md` into your Claude skills directory.

## Skills in this pack

- **[Design QA Checklist](skills/design-qa-checklist/SKILL.md)** — QA an implemented UI against the design spec — spacing, interactive states, typography, color tokens, and responsiveness.
- **[Redline Annotation](skills/redline-annotation/SKILL.md)** — Produce precise redline and spec annotations — spacing, sizes, behavior notes — that engineers can build from without guessing.
- **[Motion Spec](skills/motion-spec/SKILL.md)** — Specify animation and motion precisely — duration, easing, trigger, and intent — so engineers implement exactly what was designed.
- **[Responsive Spec](skills/responsive-spec/SKILL.md)** — Specify responsive behavior across breakpoints — reflow rules, content priority, touch targets, and layout logic.
- **[Design Handoff Doc](skills/design-handoff-doc/SKILL.md)** — Write a complete design handoff document covering components, tokens, states, and edge cases.
- **[Prototype Spec](skills/prototype-spec/SKILL.md)** — Writes detailed prototype specs: interactions, transitions, states, and edge cases.
- **[Component API Design](aouellets)** — Designs React/Vue component APIs — props, composition, event handling, accessibility. _(external — see source)_
- **[Color Accessibility](skills/color-accessibility/SKILL.md)** — WCAG 2.2 contrast compliance, accessible palettes, and color choices that survive color blindness.

## License

MIT — see [LICENSE](LICENSE). Skills are portable `SKILL.md` files; the canonical
copies live in the [Skill&nbsp;Me catalog](https://skillme.dev).
