# Changelog

All notable changes to this project are documented here. Format follows
[Keep a Changelog](https://keepachangelog.com/en/1.1.0/); versions follow
[SemVer](https://semver.org/).

## [1.2.1] — 2026-09-16

Independent review pass (GPT). Six wording fixes, no method change:
- Intro states the purpose in the author's words: the person understands
  themselves — whether they need this and want it — not a right/wrong answer.
- Principle 7 no longer conflicts with Steps A–C (a draft from confirmed
  words is not proposing).
- Grounding is mandatory before the next scripted question.
- Step A: source check per line before sending.
- Step C: one layer per message, statuses from the user, stack confirmed
  («Так? Что исправить?») before gaps are named.
- Partially answered topic questions get only the missing part.
- Step B: a sign of success that already sounded is reflected and confirmed
  before metrics.

## [1.2.0] — 2026-09-16

Simulation pass: 8 scripted personas × 3 runs (Claude plays the dialogue,
GPT evaluates against 13 checks). Text tightened where the agent drifted;
method unchanged. Run 3: 91% of checks green, no failures on order,
grounding, closures or exit.

### Changed
- **Grounding** rewritten as one move: repeat the user's word → ask how it
  shows up on an ordinary day → once visible, ask what they feel. No
  exceptions, no stops.
- **Block B** back to the original two questions (feelings, ideal workflow).
- **Block D**: «Что для тебя очень важно, чтобы было именно так — и что точно
  нет?» (with an example from their own Block C answers if they stall) +
  «Что тебе важно в самом первом шаге, чтобы не бросить через неделю?».
- **Phase 1 closure**: echo → «Так? Что поправить?» → «Что-то добавить?».
- **Phase 2**: one question per message with a confirming line, same rhythm
  as Phase 1; closure «Так? Чего не хватает?».
- **First message with a topic** has a fixed shape: «Уже понятно: …» + the
  first unanswered scripted question; nothing already said is asked again.
- **Step A**: every line must point to the user's words; otherwise
  «— не обсуждали». Intro «Вот картинка из твоих слов — проверь».
- **Step B**: the "sign of success" question is its own message; metrics
  come only after the answer.
- **Step C**: «частично» counts as empty only when nothing below is «нет»;
  reference stacks are internal to the agent, never shown as a list.
- **Step D**: no tool, service or AI named until two levels of sub-tasks
  are shown and confirmed.
- **Exit after Step C**: «На этом можно закончить … Сохранить — или на
  сегодня достаточно?» (no first-step question).
- **Progress line** replaces the phase anchor: «Уже понятно: … Дальше — …»
  as the first line after each confirmed transition; phases are never named.
- **Saving** simplified to one question and the confirmed wording only.
- Scripted questions written in one gender; the agent conjugates and never
  emits «сделал(а)» forms.

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
