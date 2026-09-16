---
name: chaos-out
description: Long, question-led session that turns a half-formed request, a stuck problem, a project without a first step, or a client case into a confirmed model, metrics and a foundation stack — by unpacking what the user already knows and feels, never by proposing a framework. Use when the structure itself is unclear, or on «разложи по полочкам», «не знаю с чего начать», «хаос в голове», «распакуй». Not for single concrete actions with a known result.
license: MIT
---

# /chaos-out — Universal problem-solving skill

"Chaos → order": from the user's tangle of feelings, thoughts and half-decisions the skill pulls out what actually matters and brings it into the open — as a confirmed model, metrics and a foundation stack. It does this by asking and reflecting, not by proposing. The skill exists so that the person understands themselves — whether they need this and whether they want it — not to hand them a right or wrong answer. The output is clarity, not a plan.

## When to invoke

- `/chaos-out` — no args. Skill starts by asking: *«О чём разбираемся? Что за запрос, задача или проблема?»*
- `/chaos-out <topic>` — topic taken as starting point.

**Gate before Phase 1 (one line, no questions).** If the topic is a single concrete action with a known result («переименовать 40 файлов по дате», «поправить формулу») — say so and offer to just do it. Enter Phase 1 only if the user confirms the structure is unclear, or the topic is a project / problem / situation.

**Use when** the user presents:
- A half-formed request («хочу автоматизировать свою работу»)
- A problem they're stuck in
- A client case needing structural unpacking
- A project or goal without a clear first step

---

## Cross-cutting principles (active everywhere)

1. **Ask until enough.** Keep asking at each stage until there's a clear signal of sufficiency. Nothing closes on the first answer.
2. **Nothing without confirmation.** At every transition and every fork, ask for go-ahead before moving on.
3. **Result, not process.** Frame every block around *what we get on the output*, not *what we do*.
4. **Max fullness, min investment.** The fullest picture for the least effort from the user.
5. **From general to specific.** Start at the top layer, then drop down. No details before the upper structure is clear.
6. **Tools come last.** Instruments are applied only at the very end, after you understand *what* is needed and *which paths* exist. Never propose a tool when the need is still unclear.
7. **Ask before you draft.** In Steps A–C the draft is built only from the user's confirmed words (that is not proposing). At every other fork of Phase 3 — where to put it, in what form, through what — ask the user first: *«Куда ты хочешь это класть / в каком виде / через что?»* Do NOT propose a pre-built structure. The skill unpacks the user's own knowledge, not external frameworks. Users usually know where their stuff lives — asking is what reveals it.
8. **Assembly first, decomposition last.** Start by ASSEMBLING the desired result from minimally necessary large blocks (Step A). Only inside Step D DECOMPOSE a chosen block into sub-tasks → deeper sub-tasks → and only then wrap in tools/skills/agents. Never decompose at the assembly stage; never assemble at the decomposition stage.
9. **Pacing: conversation, not a form.**
   - One block per message, max 3 questions in it. In Phase 1 prefer one question per message.
   - Before the next question — one line reflecting the previous answer in the user's own words (not a summary, not an evaluation).
   - Max two follow-ups to one answer.
   - With `<topic>`, the first message has a fixed shape: one line *«Уже понятно: [what the topic already said, in their words]»*, then the first scripted question the topic did NOT answer. Questions the topic answered in full are never asked again — their answers are carried into the echo. A partial answer (one process named where the question asks for three) gets only the missing part: *«Какие ещё два?»*
   - After a bare confirmation («да», «так», «оставляем») no reflection is needed — go straight on.
   - If the user hurries («давай к делу», «короче») — say ONE line: *«Дам структуру после двух коротких блоков, иначе она будет моя, а не твоя»* — and continue one question at a time. Adjust tempo by shortening reflections, never by skipping blocks.
10. **Their words.** The meaning and everyday register of every scripted question is fixed; the subject is substituted from the user's own phrasing («в этой истории» → «в [его формулировка]»). Do not add new topics — if a new one is needed, ask the user to name it. Address form (ты/вы) and grammatical gender follow the user's first message. Scripted questions in this file are written in one gender — conjugate them to the user's; never write both forms («сделал(а)») in a reply.

### Grounding reflex — one move, always the same

Whatever the user names — a wish or an irritation — repeat their word and ask how it shows up on an ordinary day: something you could see or hear. An action, an event, a number, a file. Then ask what they feel when that happens. Then we know what to build.

The move:
1. *«Когда [его слово] — в чём это проявляется? Что ты делаешь, чего не делаешь?»* For something they want and don't have yet: *«Как ты поймёшь, что [его слово] есть? Что будет по-другому в обычный день?»*
2. Answer still foggy? Ask once more the same way. Still foggy after that: *«Приведи один случай за последнюю неделю.»*
3. Once the answer is something you could watch happen: *«И когда это происходит, что ты чувствуешь?»* Take the feeling as it is, reflect it, do not ground it further.

Example: «Хочу больше свободы» → *как ты поймёшь, что свобода есть?* → «Не отвечаю клиентам после семи, не открываю ноутбук в субботу» → *и когда так, что ты чувствуешь?* → «Что вечер мой». Now it is clear what to build and why.

Not this: «зачем тебе это?», «что изменится в твоей жизни?» — head-level, no picture. Everyday speech, not coaching-book phrases.

The reflex lives inside the current block: it does not change block order and does not replace the block's question. But it is not optional: after a wish or an irritation, do not move to the next scripted question until the answer is visible and the feeling is asked.

### Progress line

At every transition — Phase 1 closed, Phase 2 closed, model accepted, metrics chosen, stack confirmed — the next message starts with one plain line: what is already clear, and what comes next: *«Уже понятно: [его подтверждённые слова]. Дальше — [одно слово о следующем шаге].»* Do not name phases or blocks unless the user asks.

---

## Phase 1 — Intake: image of desired + boundaries

**Purpose:** collect a multi-angle image of what the person wants + draw the perimeter inside which we work.

### Strict block order A → B → C → D — do NOT rearrange

#### Block A — The goal
- *«Расскажи, чего ты хочешь в [этой истории]? В чём цель?»*

#### Block B — Desired feelings & ideal workflow
- *«Как ты хочешь себя чувствовать в [этой истории]?»*
- *«Как выглядит для тебя идеальный workflow / как это должно работать?»*

#### Block C — Grounded everyday questions (ask all, one per message)
- *«Что тебя больше всего раздражает прямо сейчас в [этом]?»*
- *«Представь, что одна проблема или процесс решился бы за мгновение. Какой из них доставил бы тебе самый кайф?»*
- *«На что ты каждый день тратишь больше всего времени? Назови топ-3 действий или процессов.»*

#### Block D — Values & boundaries (ONLY after Block C)
- *«Что для тебя очень важно, чтобы было именно так — и что точно нет?»* If the user stalls, give one example from their own Block C answers («например: правки — не больше двух кругов, а вечером — точно не работать»).
- *«Что тебе важно в самом первом шаге, чтобы не бросить через неделю?»*

### Helper for Block D (if the user gets stuck)

Do NOT leave them in a vacuum. Offer dilemmas built from the material of Block C — always with a third door, always through loss:
- *«Что хуже: потерять 5 часов в неделю или 5 тысяч — или что-то третье?»*
- *«2 часа в неделю, 10 — или сколько на самом деле?»*
These are prompts to unlock the answer, not fixed options. Adapt them to the domain. Do not ask about the mode of execution (сам / делегировать, соло / команда) — that is Phase 2 material.

### Principle of order

Psychologically you cannot start with the abstract. Goal first → feelings → grounded everyday → only then values and boundaries. Otherwise the user answers with their head, not reality. **This order is non-negotiable.**

### Closure marker

Echo all four blocks (A+B+C+D) — paraphrase back what was heard — then two short steps:
1. *«Так? Что поправить?»* — the user corrects or says «так».
2. Then: *«Что-то добавить?»*
When both are answered → Phase 1 closes.

---

## Phase 2 — Current situation

**Purpose:** understand how things work right now, so the solution fits the user's reality.

### Questions — one per message, each preceded by one line confirming the previous answer in the user's words (same rhythm as Phase 1)

- *«Как это сейчас работает — по шагам, как есть?»*
- *«Какие инструменты уже в ходу?»*
- *«Что тут легко и привычно?»*
- *«Что тяжело, неудобно или незнакомо?»*
- *«Что уже пробовал для этого? Что вышло, почему бросил?»*
- Optional, if numbers exist: *«Какие цифры ты знаешь прямо сейчас? Что есть, то и называй; „не знаю“ — тоже ответ.»*

### Hard rule of the phase

**Do NOT propose solutions here.** Pure gathering.

### Principle

If a solution requires something difficult and unfamiliar, the user won't see that it's easier. Solution must fit their situation.

### Closure marker

Claude restates the current setup in 3–5 lines; user corrects or confirms — one round: *«Так? Чего не хватает?»* «Ничего» → transition.

---

## Phase 3 — Iterative output (four steps, each confirmed)

The output is NOT a one-shot dump. It is assembled iteratively, with user confirmation at every step. Never hand over all four steps at once.

### Step A — Model confirmation

Claude draws the model from the user's own material — no tools, ≤7 blocks, in this frame. Every line must point to something the user said — their words, not a plausible extension («дальше — автомат», «инструменты, которые остаются» are inventions). A line with nothing said behind it says «— не обсуждали». Before sending, check each line: can you quote where the user said it? If not — «— не обсуждали».

```
**Модель — черновик N**
Фундамент:                 <на чём всё стоит>
Вход → Обработка → Выход:  <…> → <…> → <…>
Обратная связь:            <что возвращается назад: цифры, реакции, статистика>
Кто делает:                <ты / делегат / автомат, или «— не обсуждали»>
```

Introduce it in one line: *«Вот картинка из твоих слов — проверь.»* Then: *«Так? Что убрать, что добавить?»* Iterate until accepted.

**Principle:** this is an echo-check at the architectural level — making sure we're building the right thing before we build it.

### Step B — Key metrics

First, as its own message: *«Что для тебя будет знаком, что это сработало?»* If the sign already sounded earlier («первые 20 оплат») — reflect it and ask *«Верно, это и будет знаком?»* instead. Wait for the answer, confirm it in their words.

Only then, in the next message, propose **2–3 metrics** that make that sign countable — one main success metric, one failure signal that sends us back to earlier phases, optionally one speed metric. Here proposing is required (an explicit exception to principle 7). Rules:
- Each metric must be countable with what the user already has (Phase 2). If it can't be counted today — do not drop it: mark «нечем мерить» as a gap for Step C.
- Label the source of each: **[практика]** — commonly measured in this domain; **[поиск]** — verified with web search this session; **[гипотеза]** — my assumption. Never quote numeric benchmarks unless [поиск].
- Ask: *«Что оставить, что заменить?»*

Internal reference for the agent (not a menu to show): automation / solo — hours per week on routine, days from brief to first result, revision rounds; local service / more clients — occupancy, new trials per month, trial → subscription %, renewals %; content — reach → subscription → request, requests per month; launch — requests, payments, refunds.

**Why this comes before the foundation stack:** metrics define what "result" means. The stack is then checked against them — «какие слои нужны, чтобы достичь этих метрик».

### Step C — Foundation Stack Check

Build the **vertical stack** from foundation up to the user's request out of the user's own material (Phase 1–2). Composition is dynamic — it depends on the domain. Use this frame:

```
**Фундамент-стек** (1 = фундамент, верх = твой запрос)
5. <запрос>          — есть / нет / частично
4. <…>               — …
3. <…>               — …
2. <…>               — …
1. <фундамент>       — …
Разово: <…>   |   Постоянно: <…>
🔩 Винтики: <пустые слои, по одной строке, без «как закрыть»>
```

Then:
1. **Decompose each layer into one-time and ongoing actions.** (Example: marketing strategy = one-time; content generation + stats + strategy sync = ongoing.)
2. For each layer ask: *«Это у тебя есть / нет / частично?»* — one layer per message; the status comes from the user's answer, never from the agent's guess.
3. Show the filled stack and ask: *«Так? Что исправить?»* Only after confirmation:
4. **Mark the gaps as «винтики».** Do NOT unpack them here. Just name the gap.
5. **The lowest empty layer = first priority.** Upper floors can't stand on empty ground. Empty = «нет». «Частично» counts as empty only when there is no «нет» below it.

Reference stacks — internal to the agent, never shown as a list. Build from the user's material first, then compare to find a layer they may have skipped, and ask about it in their words: *«А [слой] — это у тебя есть, или его нет?»*
- content / personal brand: market research → positioning → funnel → content strategy → content system → distribution → analytics
- more clients / local service: кто клиент и зачем приходит → оффер и цена → каналы → первое касание и пробное → продажа → удержание → учёт
- automation / solo operations: инвентарь процессов → шаблоны и стандарты → приём заказа (бриф) → производство → сдача и правки → счета и оплата → учёт времени
- product launch: аудитория → оффер → MVP → цена → воронка запуска → выдача → обратная связь

**Hard rule of the step:** do not dive into how to close a gap. Only mark it.

### Branching point after Step C

- User says «хватит, оставляем на этом уровне» → say: *«На этом можно закончить: есть твоя карта и признаки результата. Сохранить её — или на сегодня достаточно?»* Then the skill exits; the map + metrics are the deliverable.
- User says «идём вглубь» → Step D.

### Step D — Processes & tools (one block per pass)

Start with the **lowest empty layer** from Step C. Go bottom-up along the stack. For each block:

1. **Best practices на рынке.** What experienced practitioners usually put here (propose, don't invent; label [практика]/[поиск]/[гипотеза] as in Step B).
2. **Что у пользователя уже есть** в этом блоке.
3. **Что нужно добавить** — the «винтики».
4. **Only for the block the user picks:** decompose into sub-tasks by result → deeper as needed → wrap leaves in tools/skills/agents/actions/manual. Offer variants with + / −, the user chooses.

Rules:
- One block per message; steps 1–3 for the block, then *«Копаем этот или идём к следующему?»* Step 4 runs only after the user picks.
- After a block is closed: *«Идём в следующий блок или сохраняем и продолжаем в другой раз?»* If «сохраняем» → go to «Saving the session»: write the map, the closed blocks and the name of the next block, so the next session starts from it.
- Never open a new block without the user's «идём дальше».
- **Tools are always the last point — after two levels of decomposition.** No tool, service or AI is named until two levels of sub-tasks are shown and the user has confirmed them. Never propose a tool when the mechanics of a block are still unclear.

---

## Saving the session

Ask: *«Хочешь сохранить что-то из этой сессии? Если да — где ты обычно держишь такие заметки?»* Save only the confirmed wording, in that place and format: the model, the stack with its gaps, the metrics, and — if Step D was opened — the closed blocks and the name of the next one. No place exists → offer plain text to copy. Never auto-save.

---

## Hard rules (skill-wide)

- **Never skip Phase 1.** No output without the desired image AND boundaries.
- **Never rearrange Phase 1.** A → B → C → D; values and boundaries only after Block C.
- **Never propose solutions in Phase 2.** Gathering only.
- **Never dump all four output steps at once.** One by one, each confirmed.
- **Never unpack a gap in Step C.** Only mark it. Unpacking is Step D, and only for the block the user picks.
- **Never propose tools before the path is chosen.** (Principle 6.)
- **Never invent new scripted questions.** Meaning fixed, subject substituted (principle 10). If a new one is needed, ask the user to formulate it.
- **Never auto-save.** Always ask.
- **Never merge or skip step transitions.** Each is a confirmation point.
- **Never draft before asking** at a Phase 3 fork (principle 7). Offer options only if the user asks or gets stuck — then helper-style dilemmas.
