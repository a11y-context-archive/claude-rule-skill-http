# Contributing

This repo is a consumption-side configuration for [A11y Context](https://a11y-context-project.vercel.app) — installable rule and skill files for using A11y Context inside an AI coding assistant. It packages one specific retrieval variant (skill + rule + HTTP retrieval from the public docs site).

## License

Apache 2.0 — see [LICENSE](LICENSE). By submitting a contribution, you agree to license it under Apache 2.0 and confirm that the contribution does not contain proprietary, confidential, or internal material from any employer, client, or third party that you do not have explicit permission to release publicly.

## Scope

Contributions to this repo should:

- Preserve the structure expected by the A11y Context skill/rule system (the `.claude/` layout, the skill name, the rule contract)
- Focus on the consumption / installation surface — configuration files, install steps, AI-tool integration
- Avoid duplicating corpus content; patterns are retrieved from the published docs site, not bundled here

## Where other contributions belong

- **New accessibility patterns, pattern revisions, foundational rules** → contribute to [a11y-context/accessibility-pattern-api](https://github.com/a11y-context/accessibility-pattern-api)
- **Organization-specific patterns or design-system component references** → keep them in your internal fork, not upstream
- **A different retrieval variant** (local, MCP, subagent flavors) → see the matching repo under the [a11y-context org](https://github.com/a11y-context)

For broader scope guidance and the WCAG-vs-organization-specific boundary, see the corpus repo's [CONTRIBUTING.md](https://github.com/a11y-context/accessibility-pattern-api/blob/main/CONTRIBUTING.md).
