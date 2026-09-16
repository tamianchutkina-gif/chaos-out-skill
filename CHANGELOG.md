# Changelog

All notable changes to this project are documented here. Format follows
[Keep a Changelog](https://keepachangelog.com/en/1.1.0/); versions follow
[SemVer](https://semver.org/).

## [1.1.0] — 2026-09-16

Review pass (interview methodology, agent-executability, practitioner). Method
unchanged; the text now follows its own principles more consistently.

### Changed
- **Pacing**: one block per message (max 3 questions), a one-line reflection in
  the user's words before the next question, max two follow-ups; hurried users
  get one explanatory line, not skipped blocks.
- **Block B** asks for feelings and the ideal workflow through episodes
  («вспомни момент, когда было легко…», «обычный вторник, когда уже
  работает…») instead of direct reflection. Order A→B→C→D unchanged.
- **Block D** derives values from what was already said in Block C; third
  question reworded to the first step («чтобы не бросить через неделю»).
- **Helper dilemmas** built from Block C material, loss-framed, always with a
  third door; no execution-mode questions before Phase 2.
- **Grounding reflex**: separate forms for states vs. desires, user's word
  inside the question, max two rounds, never applied to Block D answers, stops
  on health/psyche answers. Example replaced with a business one.
- **Closure questions** ask for errors and omissions («что я переврал(а) или
  упустил(а)?») instead of comfort/agreement.
- **Phase 2** questions scripted verbatim in Russian; added «что уже пробовал,
  почему бросил» and an optional numbers question.
- **Step A / Step C** get fixed output frames (model ≤7 blocks; stack with
  есть/нет/частично, разово/постоянно, 🔩 винтики). First priority = the
  *lowest* empty layer.
- **Step B** starts from the user's own sign of success, then 2–3 countable
  metrics with a source label ([практика]/[поиск]/[гипотеза]); proposing here
  is an explicit exception to "ask before you draft".
- **Step C** lists four reference stacks as a checklist for missing layers.
- **Step D** goes bottom-up, one block per pass, decomposition only for the
  block the user picks, with a save-and-continue point.
- Gate before Phase 1 for single concrete actions; optional first-step
  question on exit; anchor line at transitions; ты/вы and gender follow the
  user; description gained Russian trigger phrases.
- Hard rules deduplicated against the principles; «gap in Step B» → Step C.

## [1.0.0] — 2026-09-15

First public release.

- Packaged as a Claude Code plugin (`.claude-plugin/plugin.json` +
  `marketplace.json`).
- Method as of the author's internal v2: strict A→B→C→D intake order, grounding
  reflex, four-step iterative output with a foundation-stack check, tools last.
- Personal storage conventions replaced with a generic "ask where to save"
  section.

### History (internal, before publication)

- 2026-04-23 — v1 (6 phases, one-shot deliverable) tested on a real case and
  redesigned into v2 the same day.
- 2026-05-29 — saving section made storage-agnostic.
