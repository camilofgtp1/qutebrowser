# AI Feature: Natural-Language Command Translator

A natural-language layer on top of qutebrowser's `:` command system.
Triggered via `:ai-do`, it retrieves relevant commands, translates the
query via an LLM, and confirms before executing.

For full documentation see:

- **[`qutebrowser/misc/ai/README.md`](qutebrowser/misc/ai/README.md)**
  — Architecture, retrieval, provider strategies, setup, env vars,
    hardware requirements, tradeoffs, and future work.
- **[`qutebrowser/misc/ai/RFC.md`](qutebrowser/misc/ai/RFC.md)**
  — Design history, key challenges, and implementation decisions.
