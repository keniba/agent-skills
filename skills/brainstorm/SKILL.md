---
name: brainstorm
description: "On explicit request, develop and iterate concrete alternatives until the user chooses a direction. For an unmapped option space; use pressure-test when a candidate already needs examination."
disable-model-invocation: true
---

# Brainstorm

Develop alternatives before the user commits to a direction. Read the relevant sources, test the framing, produce concrete candidates, and iterate with the user. Keep the work in the conversation; this invocation does not authorize file changes or implementation.

Use the supplied question, or the conversation leading up to the invocation. Honour the user's current instructions, constraints, deliberate edits and settled decisions. When a project is available, read its applicable instructions and relevant source material. Do not require a particular folder structure, memory system or companion skill.

## Choose the right entry point

- No credible options yet: brainstorm.
- A candidate exists and its assumptions or consequences need examination: suggest pressure-test.
- The direction is known and the work needs a brief: suggest set-goal.

These are optional handoffs. Each skill works independently. Do not invoke a sibling automatically or require the user to complete earlier stages. If they prefer to continue here, help within the requested scope.

## 1. Read before generating

Open the material the question concerns: the current passage, proposed product, source evidence or relevant project records. Read enough surrounding context to understand the constraints and qualifications. Search results locate evidence; they do not replace reading it.

Distinguish verified facts, the user's decisions and your assumptions. Find facts that available sources can answer instead of asking the user to repeat them. Never invent missing facts or treat a recommendation as an accepted choice.

## 2. Test the framing once

Briefly assess whether the stated question is the one that matters. Take a position with evidence. For example, a request to change a meeting's cadence might depend on first deciding which decisions the meeting owns.

If a different framing would materially change the task, explain it and wait for the user's direction before developing dependent alternatives. If the original framing holds, proceed without an extra confirmation round. Avoid repeatedly reopening the same framing without new evidence.

## 3. Develop concrete alternatives

For substantial, materially different approaches, use a fresh helper when the host supports delegation and the user's scope permits it. Give the helper the problem, relevant evidence, settled constraints, permitted actions and required return. Ask it to develop a distinct plausible approach while you develop another or verify constraints. Keep it independent of your preferred answer and other candidates; do not pass inherited conversation when a fresh context is available.

Use helpers where independence can improve the options, not to inflate the agent count. Small variations stay in one context. If independent generation is unavailable, develop the alternatives yourself and say so; do not describe self-generation as an independent check.

Present two to four materially different candidates, fewer if the task genuinely needs fewer. Each contains:

- **The actual proposal:** the sentence, agenda, design, table rows or other concrete output. A category label is insufficient.
- **The trade-off:** what it improves, what it costs, and where it breaks.
- **The relevant assumptions:** especially anything that would change the choice.

Verify helper claims against the sources and remove duplicates or infeasible suggestions. Lead with your recommendation when you have one, while leaving the choice to the user. Follow their requested tone and format for any drafted communication; no separate writing plugin is required.

## 4. Iterate until the user chooses

Ask for the user's pick or correction, then wait. Do not select a winner on their behalf.

Fold feedback into the next round. Read newly supplied material before generating dependent revisions. Preserve compatible user edits and deletions. State what carried forward, what changed and why so that the alternatives improve instead of simply changing names.

Continue until the user chooses a direction or ends the exploration. Do not keep generating after the choice is settled, or treat silence as acceptance.

## 5. Close and hand off

State the chosen direction and its reason. Briefly name material uncertainties and directions left unexplored. If useful, suggest pressure-test for consequential unresolved assumptions or set-goal for remaining task definition.

Stop after the requested exploration. A separate, explicit execution instruction can authorize subsequent work; this skill does not add a new permission step or a mandatory pipeline.
