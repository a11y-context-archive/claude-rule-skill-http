# claude-rule-skill-http

> **Superseded.** This repo is preserved as a historical artifact from the 9-variant A11y Context evaluation. The canonical, maintained skill source is now [a11y-context/a11y-context-skills](https://github.com/a11y-context/a11y-context-skills) (see `skills/web-react/http/`).
>
> **The `SKILL.md` `description` field in this repo is the ORIGINAL.** It does not include the updated rule-like invocation phrasing used in the consolidated monorepo. The newer description was designed to improve the AI coding assistant's invocation rate without depending on a separate rule file (since rule files are hard to enforce at the org level).

## What this was

Variant **B** in the 9-variant A11y Context evaluation: **rule + skill + HTTP retrieval**. The agent is told via an enforcement rule (`.claude/rules/a11y-policy.md`) to invoke the skill (`.claude/skills/a11y-context-web-react/`) before generating React UI code; the skill fetches accessibility patterns over HTTP from the published docs site.

Use the canonical source instead unless you specifically want the rule + skill + HTTP combination as it ran in the original evaluation.
