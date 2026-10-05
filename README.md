# premium-luxury-cursor-rules

A Cursor rule for premium / luxury / immersive frontend design. Drop the `.cursor/` directory into any project and the rule becomes available to Cursor's agent.

## What's here

```
.cursor/rules/
  premium-luxury-ui.mdc
```

## Activation

The rule uses `alwaysApply: false` with a `description`, so Cursor's agent loads it when your prompt signals **premium / luxury / immersive frontend** work — and stays out of unrelated tasks. To force it always-on, set `alwaysApply: true`; to scope by file type, add a `globs:` list.

## Source & license

- **Original source:** the `premium-frontend-ui` skill in [github/awesome-copilot](https://github.com/github/awesome-copilot/tree/main/skills/premium-frontend-ui).
- **Original listed author:** Utkarsh Patrikar.
- **This rule:** first converted for Cursor from that skill, then substantially modified by Michael McCollough ([Sciontut](https://github.com/Sciontut)): narrowed to a single luxury voice, standardized on GSAP + Lenis, with named motion values and scope rules added.
- **License:** the upstream project is MIT licensed. Its license and copyright notice are preserved in [LICENSE](LICENSE).
