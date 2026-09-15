# Contributing

Thanks for taking the time. This is a small, opinionated skill; contributions
are welcome when they keep it that way.

## Ground rules

- **Keep the method intact.** The order of steps and the hard rules are the
  product. Changes that soften or reorder them need a written rationale and a
  real session where the current version failed.
- **No personal data.** No client names, no local paths, no credentials, no
  private notes. CI scans for secrets, but the rule is broader than that.
- **Prompt-only.** This repository does not ship scripts, hooks, or MCP
  servers. If you think one is needed, open an issue first.
- **Language.** The skill mixes English structure with Russian question
  phrasing where the exact wording matters. Keep the verbatim questions as
  they are; translate only around them.

## How to propose a change

1. Open an issue describing what went wrong in a real run (what the agent
   did, what it should have done).
2. Fork, branch, edit `skills/chaos-out/SKILL.md` (and `references/` if present).
3. Test locally: `claude --plugin-dir .` then run the skill on the case from
   the issue.
4. Run `claude plugin validate .` — it must pass.
5. Open a pull request that links the issue and summarises the before/after
   behaviour.

## Versioning

We follow [Semantic Versioning](https://semver.org/). Bump `version` in
`.claude-plugin/plugin.json` and `.claude-plugin/marketplace.json`, add an
entry to `CHANGELOG.md`.
