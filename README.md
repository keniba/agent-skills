# Agent skills

A small selection of skills from my personal AI workspace, built for Claude Code and Codex.

I use these to work through a problem, pressure-test an approach, and define the goal before asking an agent to execute. That applies to code and to my work as an operator: research, financial modelling and data analysis.

These skills help me find what I haven't thought through. The agent explores options, challenges assumptions and asks questions that expose blind spots or decisions I've left undefined. We work through those gaps before execution starts.

[Matt Pocock's skills](https://github.com/mattpocock/skills) inspired me to build and share my own. `pressure-test` borrows from his grilling approach to working through decisions. `brainstorm` borrows from [Superpowers' brainstorming skill](https://github.com/obra/superpowers/tree/main/skills/brainstorming).

## How to use these skills

The skills are designed to work in sequence, but that's not an explicit requirement. You can jump straight from brainstorm to set-goal if stress-testing the approach isn't needed.

![Brainstorm: define the objective and explore options. Pressure-test: challenge the approach and its assumptions. Set-goal: define scope, exclusions, sequence, helper agents, workflow and success criteria before execution.](assets/how-it-works.svg)

## How these skills work

- **The agent reads first.** It checks the available sources before asking questions the evidence can answer.
- **It brings in other perspectives.** When useful and supported, it uses separate agents to develop alternatives or challenge a proposal.
- **It works through decisions in order.** It resolves the choices that affect later questions before moving on.
- **It keeps you involved.** It asks you to make the judgement calls, incorporates your answers and preserves decisions you've already made.

More detail on the underlying patterns is in [this document](docs/agentic-patterns.md).

## Installation

### Claude Code

In a Claude Code session:

```text
/plugin marketplace add keniba/agent-skills
/plugin install agent-skills@agent-skills
```

### Codex

In your terminal:

```sh
codex plugin marketplace add keniba/agent-skills
codex plugin add agent-skills@agent-skills
```

## Licence

[MIT](LICENSE). See [NOTICE.md](NOTICE.md) for attribution and upstream licences.
