---
name: set-goal
description: "On explicit request, clarify a task and draft a goal, success criteria, boundaries and execution approach for approval. Scoping only; does not create native goal state or start execution."
disable-model-invocation: true
---

# Set goal

Turn a loosely defined task and its existing context into an explicit brief the user can approve or edit. Use the supplied task or the conversation leading up to the invocation. Preserve decisions already made and authorization already given.

The brief stays in the conversation unless the user separately requests a file. This skill does not create native platform goal state, schedule work, launch helpers or execute the task. A separate execution instruction may authorize subsequent work after the scope is settled.

## Choose the right entry point

- Options are unknown: suggest brainstorm.
- A proposal needs examination and its questions depend on further decisions: suggest pressure-test.
- The direction is known and the task needs definition: set-goal.

Each skill works independently. Do not invoke a sibling automatically, require earlier stages or re-scope a plan merely because it is multi-step.

## 1. Gather the existing brief

Read the task, supplied material, prior decisions and current relevant source files. When a project is available, follow its applicable instructions, naming and confidentiality requirements. Do not require a particular directory structure, memory system or companion skill.

Find facts the available sources can answer. Preserve user edits and deliberate omissions. Keep verified facts, assumptions and open decisions distinct. Do not invent owners, dates, figures or outcomes.

## 2. Separate decisions from defaults

A material decision changes what you will produce: purpose, audience, scope, output, authoritative source, success criteria or a consequential constraint.

Resolve routine choices using the user's settled instructions, relevant evidence and reasonable defaults. State consequential assumptions. Ask only for choices that genuinely need the user's judgement; your recommendation is not their answer.

## 3. Clarify, then wait

If material choices remain, ask a concise batch of questions, usually one to four. Each offers concrete alternatives and explains what the output would contain under each. Recommend one where justified.

Use the host's structured question tool when available, permitted and suitable; otherwise ask in chat. Wait for required answers before drafting the dependent goal, including when the question tool is asynchronous. Do not put an assumed goal below unanswered questions.

When the task is already clear, proceed directly to the draft. Do not ask the user to approve settled choices again.

## 4. Draft the brief

Present:

1. **Goal:** one clear statement of the objective.
2. **Success criteria:** three to five observable checks tied to the actual task, useful during execution as well as at completion. For analytical work, these might concern evidence, completeness and decision usefulness; use code tests only when appropriate.
3. **Boundaries:** included and excluded work, relevant source and confidentiality limits, and any permitted external actions.
4. **Execution approach:** who produces the result, how evidence is gathered and how consequential claims are checked. State dependencies and a stopping condition. Keep tightly coupled or small work in one context.
5. **Approve or edit:** ask the user to accept or amend this newly drafted brief. If they already approved the same substantive brief and nothing material changed, identify it as settled without requesting another approval.

## Select the approach by the work

| Task shape | Approach to propose |
|---|---|
| Independently answerable evidence questions | Parallel research followed by synthesis, grouping questions that share sources or dependencies. |
| Consequential claims or a proposal needing challenge | Independent verification against sources and explicit criteria. |
| Unmapped options | Independent candidate generation, followed by comparison and human selection. |
| Competing complete solutions with a useful rubric | Compare independent approaches; use a tournament only when extra attempts improve the decision. |
| An audit with unknown work remaining | Iterative passes until criteria are met or no new material findings emerge, with a limit appropriate to the task. |
| Small or tightly connected work | One producer with proportionate checks. |

Separate producing from checking. Plan a fresh critic for consequential factual and analytical judgements when available; name the limitation when independent review is unavailable. A single author can preserve coherence while helpers gather evidence or challenge those judgements. Mechanical checks can self-verify; subjective preferences remain the user's decision.

When proposing helpers, give each a self-contained assignment: task, relevant sources, settled constraints, permitted actions, required return and completion test. Specify dependencies. Independent generators should not see peer answers; critics should receive the proposal and evidence without the producer's persuasive discussion or preferred verdict. Use fresh contexts when supported. If independent review is unavailable, name that limit rather than calling self-review independent.

This selects a method for later execution. Do not launch the proposed helpers during scoping.

## 5. Resolve and hand off

Wait for approval of a new brief. Incorporate edits without restoring rejected wording, and return only changed decisions for further review when needed. Approval of a broad task does not settle a material scope question that remains open.

Once approved, return the brief and end a scoping-only request. If execution was separately and explicitly authorized, the executor can proceed without another permission round, subject to the host's tools and permissions.

The execution handoff carries the objective, remaining success criteria, boundaries, helper assignments, dependencies and stopping condition. Check work against that agreement rather than reconstructing it. If context loss makes the agreement unrecoverable, ask for the missing portion; chat history is not guaranteed persistent state.
