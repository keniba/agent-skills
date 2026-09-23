---
name: pressure-test
description: "On explicit request, examine an unsettled proposal using evidence, dependency-ordered questions and concrete alternatives. For a candidate that needs challenge; use brainstorm when options do not yet exist."
disable-model-invocation: true
---

# Pressure-test

Examine a decision before it is made. Test the framing, identify the decisions that depend on one another, and work through the material questions until the user understands the choice and its consequences. Keep the work in the conversation. Do not implement the decision or write files as part of this invocation.

Use the supplied proposal, or the conversation leading up to the invocation. Honour the user's current instructions, settled decisions and deliberate edits. Read applicable project instructions and actual source material when available; do not depend on a particular workspace layout or companion skill.

## Choose the right entry point

- Options do not yet exist: suggest brainstorm.
- A candidate exists and answering one question exposes further consequential questions: pressure-test.
- The direction is settled and a short clarification would define the task: suggest set-goal.

These are optional handoffs, not prerequisites. Do not invoke a sibling automatically. If the user declines a redirect, continue helpfully within scope, including generating a small set of concrete options when needed.

## 1. Establish the facts

Read the relevant sources before building questions. Distinguish what the user has decided, what evidence establishes and what remains unknown. Find available facts yourself rather than making the user repeat them.

A search returning no matches does not establish absence. Before using a negative result to dismiss an option, check the search scope and confirm that the same search method finds a known-present item. Read the relevant sources when the conclusion matters.

## 2. Test the root question

Before decomposing the proposal, ask whether the stated decision is the real one or depends on an upstream choice. Take a position in one short paragraph with evidence.

If the root should change, explain why, offer the framing choice and end the response there. You may list deferred questions, but do not answer them, close choices or present the next question round until the user directs the framing. If the original root holds, name the strongest alternative framing you considered and briefly explain why it changes less. Do not manufacture a counterproposal just to fill a template.

Once the root is settled, use a fresh critic when independent challenge could change a consequential commitment or expose an assumption that invalidates the proposal, especially if you helped develop it. Give the critic the proposal, evidence, settled constraints, permitted actions and review criteria, without your persuasive case, preferred verdict or inherited conversation. Ask for supported failure conditions, unsupported assumptions and material omitted alternatives. No material finding is a valid result.

Start the critic while you continue source verification and questions that do not depend on its return. Use separate fact-finding helpers for independently answerable evidence questions when useful. Check their claims before using them. If helpers are unavailable, say that the review is your own; do not imply independent verification. Do not repeat a review without changed evidence or a changed proposal.

## 3. Map dependencies

Keep an explicit account of the root decision and the decisions beneath it. A question depends on another when its answer could change with the earlier answer. Independent questions can be considered together.

Example: decide which decisions an operating review owns before choosing its attendees. Meeting cadence may also depend on how quickly those decisions must be made.

This is a reasoning aid, not a requirement to write a diagram or create an execution graph.

## 4. Identify what can be decided now

Consider the questions whose prerequisites are settled. Close only those that:

- Applicable instructions or the user's existing decisions already answer.
- Available evidence can resolve, after you verify it.
- Cannot materially change the decision, scope or next action under any plausible answer.

Briefly show these closures and their reasons so the user can correct them. Evidence can settle a factual question; it does not supply consent to a course of action. A change shared by all your proposed options is still a proposal unless the user has chosen it. Label recommended defaults as proposed, not closed. A missing fact blocks only the questions that depend on it, not the entire discussion.

## 5. Ask the material questions together

Present all currently answerable material questions in one numbered round. Do not impose an arbitrary question quota, suppress a consequential choice, or force dependent questions into an early round.

For each question, include:

1. What needs deciding and what depends on it.
2. The live options, each with a concrete consequence or example.
3. Your recommendation and its trade-off. Say when the evidence does not support a preference.

Use the host's structured question tool when available and suitable for the complete round; otherwise use chat. If options are missing, develop the minimum useful alternatives or offer brainstorm at that point. Do not hand the user an empty question.

Then wait for the answers. Silence, a preselected option or your own recommendation does not settle a choice.

## 6. Recompute after each round

Incorporate answers, check new sources and identify which questions become answerable next. Carry forward actual decisions unless new evidence creates a material conflict; name that conflict rather than quietly reopening the choice.

End each round with a compact list of remaining questions, including those deferred while the conversation explores a side issue. Keep that list in the conversation. It does not guarantee retention after a context reset; ask for missing decisions if they cannot be recovered.

Continue until no material question remains or the user calls an end. Do not invent more questions merely to prolong the process.

## 7. Close without acting

Summarize the settled decisions, the reasons that matter and anything left unresolved or unexplored. The user decides; a helper supplies evidence and challenge.

If task definition remains useful, suggest set-goal. If the candidates themselves proved inadequate, suggest returning to brainstorm. Do not create a competing execution brief here, implement the proposal or persist the discussion without a separate request. An existing explicit execution instruction remains valid; do not add redundant approval steps.
