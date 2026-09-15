# chaos-out

**Chaos → order.** A Claude Code skill that turns a vague request into a
confirmed model, metrics, a foundation stack and — if you want to go deeper —
processes and tools. It works by *asking*, not by proposing: the skill unpacks
what the user already knows instead of imposing an outside framework.

> Навык для Claude Code: «хаос → порядок». Распаковывает размытый запрос
> в подтверждённую модель, метрики и стек фундамента через вопросы, а не через
> готовую структуру. Описание на русском — ниже.

## Install

```
/plugin marketplace add tamianchutkina-gif/chaos-out-skill
/plugin install chaos-out@chaos-out-skill
```

Then, in any session:

```
/chaos-out:chaos-out
/chaos-out:chaos-out хочу автоматизировать свою работу
```

Or copy `skills/chaos-out/` into `~/.claude/skills/` and call it as `/chaos-out`.

## When to use it

- A half-formed request («хочу автоматизировать свою работу»)
- A problem you are stuck in
- A client case that needs structural unpacking
- A project or goal without a clear first step

Not for tactical single-step tasks — only when the *structure itself* is unclear.

## How it works

```
Phase 1  Intake        goal → feelings & ideal workflow → grounded everyday
                       questions → values & boundaries (order is fixed)
Phase 2  Current state how it works now, what tools, what is easy / hard
                       (no solutions here)
Phase 3  Output        A model → B metrics → C foundation stack → D processes
                       & tools — one step at a time, each confirmed
```

Every abstraction gets grounded with *«а в чём это проявляется?»* until it is
an observable daily action. Tools are proposed last, after the path is chosen.

Full protocol: [`skills/chaos-out/SKILL.md`](skills/chaos-out/SKILL.md).

## What it does not do

- Does not propose a structure before asking.
- Does not skip intake or start with abstract questions.
- Does not save anything without asking where.

## Security

Prompt-only: Markdown instructions, no scripts, no hooks, no tool grants. See
[SECURITY.md](SECURITY.md).

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). Method changes need a real failing
session as evidence.

## License

[MIT](LICENSE).

---

## По-русски

`/chaos-out` — универсальный алгоритм разбора: запрос, проблема или задача,
у которых непонятна сама структура. Навык **спрашивает, а не предлагает**:
достаёт знания и ситуацию самого пользователя, а не навязывает чужую архитектуру.

**Когда:** размытый запрос, застрявшая проблема, клиентский кейс, проект без
первого шага. **Не для** тактических операций в один шаг.

**Как:**
1. **Интейк** — цель → желаемые ощущения и идеальный workflow → заземлённые
   бытовые вопросы → ценности и границы. Порядок жёсткий: с абстрактного
   начинать нельзя.
2. **Текущая ситуация** — как устроено сейчас, какие инструменты, что легко,
   что тяжело. Решений на этом этапе нет.
3. **Итеративный выход** — модель → метрики → стек фундамента → процессы
   и инструменты. По одному шагу, каждый подтверждается.

Любая абстракция заземляется вопросом *«а в чём это проявляется?»*.
Инструменты — в самом конце, когда путь выбран.
