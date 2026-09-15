# Security Policy

## What this repository contains

This repository is a **prompt-only Claude Code skill**: Markdown instructions
that an AI agent reads. It ships no executable code, no scripts, no hooks, no
MCP servers, and requests no tool permissions (`allowed-tools` is not set).

Installing it adds text to the agent's context and nothing else. Still, treat
any skill as you would treat a dependency: read `skills/chaos-out/SKILL.md`
before installing.

## Reporting a vulnerability

If you find something in this repository that could cause an agent to act
unsafely — prompt-injection vectors, instructions that could leak data, or
guidance that pushes an agent to run destructive commands — please **do not
open a public issue**.

Use GitHub's private vulnerability reporting for this repository
(**Security → Report a vulnerability**). You will get an acknowledgement
within 7 days.

## Scope

In scope:
- Content of `SKILL.md` and reference files that could be abused to make an
  agent misbehave.
- Metadata files (`.claude-plugin/*.json`) pointing at untrusted sources.

Out of scope:
- Behaviour of Claude Code itself — report that to Anthropic.
- Misuse of the skill on the user's own data by the user.

## Supported versions

Only the latest tagged release and the `main` branch receive fixes.
