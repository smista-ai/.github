# smista.ai

<p align="center">
  <img src="https://smista.ai/logo-150.png" alt="smista.ai logo" width="150" />
</p>

<p align="center">
  <strong>One workflow. Every model. The right one, every time.</strong>
</p>

<p align="center">
  <a href="https://smista.ai">Website</a> &middot;
  <a href="https://smista.ai/blog">Blog</a> &middot;
  <a href="https://docs.smista.ai">Documentation</a> &middot;
  <a href="https://x.com/smista_ai">X.com</a> &middot;
  <a href="https://discord.gg/TSnkhM4fvg">Discord</a> &middot;
  <a href="mailto:info@smista.ai">Email</a>
</p>

## What is smista.ai?

smista.ai is a **local-first agent and CLI** that routes each phase of an AI
workflow to the model best suited for it. Using deterministic, configurable
policies instead of guesswork.

In 2026, most developers juggle several models and providers. Switching between
CLIs and web apps, copying context around, and remembering which model fits each
task is slow and error-prone. smista.ai keeps **one coherent workflow** while
letting different models handle different phases.

## Why it's different

- **Deterministic routing.** Which model runs a task never depends on an LLM's
  judgment. Every decision follows rules you control.
- **Fully explainable.** Inspect any routing decision through a trace: detected
  task, selected model, matched rule, included context, estimated cost.
- **Local-first.** Your workflow runs on your machine, under your config.
- **Safe by default.** Before any write, smista.ai shows a diff and asks for
  confirmation.

It's not a clone of Claude Code or Codex. It gives you the core primitives of a
modern coding agent — prompt templates, plan mode, skills, tool permissions,
context management, diff and review, traceability — on top of deterministic
routing.

## Try it

```sh
# Run a task — smista picks the model and shows its reasoning
smista "refactor the auth middleware"

# Preview a route without running it
smista route "review this PR"

# Inspect the full routing decision afterwards
smista trace
```

## Explore the project

| Project                                               | What it is                                          |
| ----------------------------------------------------- | --------------------------------------------------- |
| [`smista.ai`](https://github.com/smista-ai/smista.ai) | The main monorepo: agent, CLI, router, SDKs         |
| [Blog](https://smista.ai/blog)                        | Updates, news, and insights from the smista.ai team |
| [Documentation](https://docs.smista.ai)               | Guides, configuration, API and SDK docs             |

## Get involved

Contributions are welcome. Start with the
[contributing guide](https://github.com/smista-ai/smista.ai/blob/main/CONTRIBUTING.md)
and the
[code of conduct](https://github.com/smista-ai/smista.ai/blob/main/CODE_OF_CONDUCT.md).

> **Using AI tools to contribute?** Read our
> [AI policy](https://github.com/smista-ai/smista.ai/blob/main/AI_POLICY.md)
> first — we expect every contribution to come from a human who understands it.

## License

smista.ai is open source under the [MIT License](https://opensource.org/licenses/MIT).
