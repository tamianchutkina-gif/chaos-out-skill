---
name: chaos-out
description: Use when a user brings a half-formed request, a problem they are stuck in, a project without a clear first step, or a client case that needs structural unpacking — and the structure itself is unclear. Unpacks the user's own knowledge and situation through ordered questions instead of imposing an outside framework. Not for tactical single-step operations.
license: MIT
---

# /chaos-out — Universal problem-solving skill

"Chaos → order": the skill turns a vague request into a confirmed model, metrics, a foundation stack and — if the user wants to go deeper — processes and tools. It does this by asking, not by proposing.

## When to invoke

- `/chaos-out` — no args. Skill starts by asking: *«О чём разбираемся? Что за запрос, задача или проблема?»*
- `/chaos-out <topic>` — topic taken as starting point, skill immediately enters Phase 1.

**Use when** the user presents:
- A half-formed request («хочу автоматизировать свою работу»)
- A problem they're stuck in
- A client case needing structural unpacking
- A project or goal without a clear first step

**Do NOT use** for tactical single-step operations — `/chaos-out` is for situations where the structure itself is unclear.

---

## Cross-cutting principles (active everywhere)

1. **Ask until enough.** Keep asking questions at each stage until there's a clear signal of sufficiency. Nothing closes on the first answer.
2. **Nothing without confirmation.** At every transition and every fork, ask for go-ahead before moving on.
3. **Result, not process.** Frame every block around *what we get on the output*, not *what we do*.
4. **Max fullness, min investment.** The fullest picture for the least effort from the user.
5. **From general to specific.** Always start at the top layer, then drop down. Do not dive into details before the upper structure is clear.
6. **Tools come last.** Instruments are applied only at the very end, after you understand *what* is needed and *which paths* exist to get it. Never propose a tool when the need is still unclear.
7. **Ask before you draft — ask OFTEN.** When decomposing any block at any level, ALWAYS ask the user first: *«Куда ты хочешь это класть / в каком виде / через что?»* And don't stop at the first question — keep asking at every sub-decision. Err on the side of more questions, not fewer. Do NOT propose a pre-built structure. The skill exists to unpack the user's own knowledge, not to impose external frameworks. Users usually know where their stuff lives — asking is what reveals it.
8. **Assembly first, decomposition last.** The flow is: start by ASSEMBLING the desired result from minimally necessary large blocks (Phase 3 Step A). Only at the very end, inside Step D, DECOMPOSE each chosen block into sub-tasks → sub-tasks into deeper sub-tasks → and then, and only then, wrap in tools/skills/agents. Never decompose at the assembly stage; never assemble at the decomposition stage.

### Grounding reflex (universal)

When the user names anything abstract — feeling, desire, goal, problem — immediately ground it with *«а в чём это проявляется?»* until we're at the level of daily observable action.

Example: «Я устала от тревоги» → *в чём это проявляется?* → «Нет сил встать с кровати, нет сил зарабатывать, утром не хочется жить». Only at the concrete level do we see what to do.

**Questions must be grounded, not abstract.** Avoid mind-level («зачем тебе это?», «что изменится в твоей жизни?»). Favor real-life hooks («что раздражает прямо сейчас?», «на что тратишь больше всего времени?»). Grounded ≠ literary — use everyday speech, not coaching-book phrases.

---

## Phase 1 — Intake: image of desired + boundaries

**Purpose:** collect a multi-angle image of what the person wants + draw the perimeter inside which we work.

### Strict block order — do NOT rearrange

#### Block A — The goal
- *«Расскажи, чего ты хочешь в этой истории? В чём цель?»*

#### Block B — Desired feelings & ideal workflow
- *«Как ты хочешь себя чувствовать в этой истории?»*
- *«Как выглядит для тебя идеальный workflow / как это должно работать?»*

#### Block C — Grounded everyday questions (ask all)
- *«Что тебя больше всего раздражает прямо сейчас в этом?»*
- *«Представь, что одна проблема или процесс решился бы за мгновение. Какой из них доставил бы тебе самый кайф?»*
- *«На что ты каждый день тратишь больше всего времени? Назови топ-3 действий или процессов.»*

#### Block D — Values & boundaries (ONLY after Block C)
- *«Какие у тебя ценности в этой истории?»*
- *«Что для тебя точно нет?»*
- *«Что для тебя важно именно в начале этого вопроса?»*

### Helper for Block D (if user gets stuck)

If the user cannot answer the abstract boundary questions — do NOT leave them in a vacuum. Offer concrete binary dilemmas that elicit boundaries through choice:
- *«Ты готов платить больше временем или деньгами?»*
- *«2 часа в неделю или 10?»*
- *«Сам публикуешь или полностью делегируешь?»*
- *«Работать соло или готов к команде?»*
These are prompts to unlock the answer, not fixed options. Adapt them to the domain.

### Principle of order

Psychologically you cannot start with the abstract. Goal first → grounded everyday → only then abstract values/boundaries. Otherwise the user answers with their head, not reality. **This order is non-negotiable.**

### Closure marker

Echo-check all four blocks (A+B+C+D) — paraphrase back what was heard, then ask: *«Насколько тебе сейчас комфортно? Это именно то, что ты ощущаешь?»* When the echo is confirmed AND comfort is confirmed → Phase 1 closes. Iterate otherwise.

---

## Phase 2 — Current situation

**Purpose:** understand how things work right now, so the solution fits the user's reality.

### Questions

- How does this currently function (the process)?
- What tools are already being used?
- What is easy / comfortable?
- What is hard / uncomfortable / unfamiliar?

### Hard rule of the phase

**Do NOT propose solutions here.** Pure gathering.

### Principle

If a solution requires something difficult and unfamiliar, the user won't see that it's easier. Solution must fit their situation.

### Closure marker

User can restate their current setup in their own words; no new information emerges from follow-ups. Confirm comfort, then transition.

---

## Phase 3 — Iterative output (four steps, each confirmed)

The output is NOT a one-shot dump. It is assembled iteratively, with user confirmation at every step. Never hand over all four steps at once.

### Step A — Model confirmation

Claude draws the model — boxes and flows of what the user seems to want. Asks: *«Я правильно понимаю, что твоя идеальная модель — вот такая?»*

User confirms or edits. Iterate until the model is accepted.

**Principle:** this is an echo-check at the architectural level — making sure we're building the right thing before we build it.

### Step B — Key metrics

Claude proposes **market-tested metrics** for the domain (what practitioners usually measure, not what Claude invents). User confirms or replaces. Covers both the main success metric and failure signals that would trigger going back to earlier phases.

**Why this comes before the foundation stack:** metrics define what "result" means. The stack is then checked against the metrics — «какие слои нужны, чтобы достичь этих метрик».

### Step C — Foundation Stack Check

Claude draws the **vertical stack** from foundation up to the user's request. The composition of the stack is **dynamic — depends on the task domain**. For content: market research → positioning → funnel → content strategy → content system → distribution → analytics. For another task, a different stack.

Then Claude:

1. **Decomposes each layer into one-time and ongoing actions.**
   - Example: marketing strategy = one-time action; content generation + stats + strategy sync = ongoing.
2. For each layer asks: *«Это у тебя есть / нет / частично?»*
3. **Marks the gaps as "screws" that need to be placed.** Does NOT unpack them here. Just names the gap.
4. The topmost empty layer = first priority. Cannot build upper floors on empty ground.

**Hard rule of the step:** do not dive into how to close a gap. Only mark it. Diving into gaps happens in Step D, and only for the one the user picks first.

### Step D — Processes & tools (sequential block-by-block walkthrough)

After Step C produces the visual map, there is a **branching point**:
- User says «хватит, оставляем на этом уровне» → skill exits. The map + metrics are the final deliverable.
- User says «идём вглубь» → proceed to Step D.

In Step D, walk through **every block of the map in sequence, left to right** (not only picked gaps). For each block:

1. **Best practices на рынке.** What do experienced practitioners usually put in this block? (Claude proposes, not invents.)
2. **Что у пользователя уже есть** в этом блоке.
3. **Что нужно добавить** — gaps marked as «винтики» to place.
4. For each gap: decompose into sub-tasks by result → decompose sub-tasks further as needed → wrap leaves in tools/skills/agents/actions/manual. Offer variants with + / −, user chooses.

**Order of blocks:** follow the flow on the map (Foundation → Input → Processing → Output → Statistics). Don't skip blocks. Don't rearrange.

**Tools are always the last point — after two levels of decomposition.** Never propose a tool when the mechanics of a block are still unclear. Never start decomposition before best-practices + gap are named for that block.

---

## Saving the session

If the user wants to keep the results, ask where they store project notes and write in that format:
- mapped project → a project note
- action items → task notes with a state and a deadline (or none)
- significant decisions → a decision note linked to the project
- whole raw session / unsorted → an inbox note

Ask: *«хочешь сохранить что-то из этой сессии?»* — never auto-save.

---

## Hard rules (skill-wide)

- **Never skip Phase 1.** No output without the desired image AND boundaries.
- **Never start Phase 1 with Block D.** Abstract boundary questions only after concrete grounding.
- **Never propose solutions in Phase 2.** Gathering only.
- **Never dump all four output steps at once.** They are built one by one, each confirmed.
- **Never unpack a gap in Step C.** Only mark it. Unpacking is Step D, and only after the user picks.
- **Never propose tools before the path is chosen.** Tools come last.
- **Never invent new grounded questions.** Use the Phase 1 question set verbatim. If a new one is needed, ask the user to formulate it.
- **Never auto-save.** Always ask.
- **Never merge or skip step transitions.** Each is a confirmation point.
- **Never abstract-ify.** Every abstract phrase gets grounded via *«в чём это проявляется?»*.
- **Never draft before asking.** At every decomposition step, ask the user what they want first. Offer options only if they ask or get stuck (then use helper-style binary dilemmas). The skill unpacks the user — it does not impose.
