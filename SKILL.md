---
name: research-rizz
description: Research RIZZ is a self-contained skill using TRIZ and cross-disciplinary mechanism transfer to develop practical alternatives or explore new research questions. Use for Research RIZZ, cross-disciplinary research, or requests to adapt mechanisms from other fields. Recovers the active problem or question from the session; separates conventional options, evidenced transfers, and credible speculative ideas.
---

# Research RIZZ

Find an approach worth trying or a better research question. Research how other fields handle the underlying mechanism, adapt what survives the change of context, and show what the connection adds. `/research-rizz` or `$research-rizz` alone is sufficient when the session contains a problem or question. The playful name is branding; use plain technical language in the work.

All required method instructions, including the TRIZ foundation, are in this file. Use one shared set of candidates and one recommendation and testing cycle. No other skill, plugin, script, package, API key or service is required. Work with the conversation, supplied sources and tools already available in the host. Browsing and additional agents are optional. Invocation preserves the session's discussion or execution scope; proposed experiments require existing authorization before execution.

## Establish what a new idea needs to change

Recover the user's current objective, latest steering, constraints, existing evidence and previously tried approaches from the conversation and relevant supplied material. Prefer the user's desired outcome over the agent's latest proposed solution. When several tasks exist, choose the one most directly blocking that outcome. State the inferred target and proceed. Ask one targeted question only when the session supplies no identifiable problem or research question, or a material ambiguity prevents useful work.

For exploratory requests, the target may be an open question or uncertain framing. Keep the baseline and proposed mechanism provisional through initial discovery, then assess what the findings add. A source-supported reframing can be a useful result before a practical improvement is identifiable.

Write a compact starting point:

- **Useful function and conflict:** what must happen, what must remain true, and what mechanism appears to prevent both. When a contradiction fits, express it as: “Improving X by doing Y makes Z worse because of this mechanism.” Distinguish observed conflicts from hypotheses and physical limits from architecture or assumptions. When no contradiction fits, identify a missing, harmful or excessive function instead.
- **Conventional baseline:** the strongest ordinary approach and its known limits. Use the user's actual prior attempts where available; label a proposed baseline rather than pretending it was tested.
- **Unresolved need:** the specific requirement the baseline leaves unmet. If it meets the need, acknowledge that and scale further exploration to the user's appetite for alternatives.

Translate the need into actors, operations, feedback, timing and resource constraints. When the cause is uncertain, keep a credible rival explanation and seek an observation that distinguishes them. Revise this starting point when evidence changes it.

Use TRIZ's **ideal final result** as a search direction: the useful function occurs with minimal added machinery, effort, cost and harm. It is not a promised outcome. Inventory resources already available, such as information, components, idle capacity, timing, by-products and surrounding systems.

## Search where the constraint changes meaning

Choose a small set of fields because they may offer different mechanisms. Adjacent-first is a default for practical problem solving. Exploratory work can begin with distant fields to discover vocabulary, relationships or a better question; investigate a tentative connection before requiring a complete mapping. Use these questions to direct search, without filling a quota:

- Who performs this function under a more severe version of our limiting constraint?
- Who makes productive use of the thing we regard as waste, delay, noise or interference?
- Where has a similar approach failed, and what assumption broke?

Search in each field's native vocabulary. A famous domain or unusual metaphor earns no preference by itself. Group findings by operation and causal relationship; several disciplines recommending the same operation are one candidate family. Distinct domains need not provide independent evidence.

Use supplied primary material and any browsing tools already available. Read retained sources far enough to explain their actual procedure, assumptions, comparison and limitations. Search snippets and abstracts remain leads when the claim concerns an implementation or experiment. Separate theory, simulation, laboratory results and deployment. Inspect later outcomes for historical approaches and verify current implementations before recommending them. Keep queries abstract enough to avoid exposing private project details. If browsing or sources are unavailable, continue with clearly labeled hypotheses and identify what evidence would be needed; remembered leads are not completed research. This workflow does not require installing tools or connecting an external account.

## Make the transfer explicit

For each promising candidate, retain a compact record of the following. Develop a few distinct candidates in depth; use prose or a table as appropriate.

| Element | What to establish |
| --- | --- |
| Source mechanism | The operation and causal relationship the source actually supports, with its conditions and a direct citation. |
| Target mapping | Which target actors, signals, operations and resources take the corresponding roles; preserve causal direction and relevant units, timing and scale. |
| Adaptation | What must change to make the mechanism work here, and which source assumptions cease to hold. A partial mapping can still be useful. |
| Added value | The unmet need addressed beyond the baseline, or the new question or reframing supported after initial discovery; identify what is already familiar. |
| New burden | Required information, setup, maintenance, incentives, interfaces or other costs introduced by the transfer. |
| Breakpoint | A concrete target condition under which the mechanism loses its advantage or fails. |

Classify the transfer as **direct**, **partial**, or **heuristic**. Keep demonstrated source results separate from proposed target behavior. Novelty to this user, to the target field, and to published knowledge are different claims; only make the claim the search supports.

### Apply the embedded TRIZ tools

Use the few principles that explain a concrete adaptation. These are selected starting points, with questions adapted for workflows and software, rather than a complete TRIZ reference.

| Principle | Adaptation question |
| --- | --- |
| 1 — Segmentation | Can independent parts handle different needs? |
| 2 — Taking out | Can the interfering part be separated while preserving the useful function? |
| 3 — Local quality | Can different parts operate differently? |
| 5 — Merging | Can related operations share work? |
| 6 — Universality | Can an existing component perform another needed function? |
| 10 — Preliminary action | Can preparation happen before the critical moment? |
| 13 — The other way round | Can the direction, order or active role be reversed? |
| 15 — Dynamics | Can behavior adapt to changing conditions? |
| 22 — Blessing in disguise | Can an unwanted output become a useful input? |
| 23 — Feedback | Can a measured signal change the process at the right point? |
| 24 — Intermediary | Can an intermediate component mediate the interaction? |
| 26 — Copying | Can a simpler representation supply the needed function? |

When the same element appears to need opposite properties, check whether those requirements must hold at the same time and place. Explore separation in time, location, condition, or between the whole and its parts. Label uses in nonphysical systems as adaptations. Evaluate whether a proposal removes a conflict, reduces it or shifts work to setup, maintenance, other people or adjacent systems.

A contradiction matrix is optional and is not included or needed for this workflow. If a matrix lookup is claimed, identify the improving and worsening parameters and verify the actual cell from an available source. Without that evidence, describe a principle-based proposal without claiming a lookup. Avoid forced engineering-parameter mappings for software or organizational problems.

If two borrowed mechanisms combine, specify their handoff and why each is needed; keep them as alternatives if their assumptions conflict. A principle name alone does not explain a solution or prove effectiveness.

## Challenge the mechanism while preserving exploration

For the leading transfer, name the outcome and conditions under which the borrowed operation is expected to matter. Compare its presence and removal while keeping other factors comparable. If removal makes no difference there, narrow the claimed incremental benefit under those conditions. Consider redundancy, benefits under other conditions and interactions before attributing the result; preserve uncertainty when the operation cannot be removed cleanly. Assess novelty separately using prior work. Where an ablation is feasible, include it in the experiment; otherwise state the counterfactual's limits.

Construct a plausible boundary case in which the source mechanism works but this transfer fails. Use the difference to repair the adaptation or narrow its applicable conditions. An invented counterexample is a hypothesis, not observed evidence. Reject causal contradictions and established constraint violations; unresolved performance is a reason to test, not automatic rejection.

When the task benefits from exploration, preserve one **credible wildcard** through this challenge: a materially different mechanism with a coherent mapping but unresolved evidence or feasibility. Name the uncertainty and the cheapest way to reduce it. Its justification can be the evidence for the underlying mechanism plus an explicit speculative adaptation; it need not already have a successful application in the target field. Omit the wildcard when none is credible. Preserve disagreement rather than averaging distinct mechanisms into a generic recommendation.

## Make the next experiment informative

Recommend the strongest practical candidate and, when justified, the wildcard. If the useful result is a new question or reframing, recommend the smallest investigation that could distinguish it from the previous understanding. For a proposed improvement, state:

- The baseline and proposed change, with comparable information and resources.
- A directional prediction that distinguishes them, plus a measurable or observable result that would weaken the explanation.
- The relevant breakpoint or ablation, and the smallest authorized experiment or investigation that could decide the next step.

Separate an appealing idea, source-supported mechanism, locally tested improvement and replicated result. Recommending the conventional baseline is valid. Claim improvement only from actual comparative evidence; do not invent measured baselines, success probabilities or creativity scores.

Stop when the leading transfer or reframing has enough support to explain its contribution, limits and informative next investigation, and further search is unlikely to change that decision. Retained transfers need an explicit mapping. Report a precise unresolved question if the evidence cannot support a recommendation. A failed search can be useful; a fixed source or discipline count is not completion evidence.

## Deliver a decision the user can inspect

Lead with the problem or question and the best next move. For practical proposals, explain the conventional approach's remaining gap, the borrowed operation and its adaptation, the strongest challenge, and the experiment. For exploratory results, explain how the framing changed, what supports that change and what to investigate next. Include the wildcard when warranted and one rejected connection if its failure teaches something consequential. Cite source claims beside the explanation and identify reading limitations where they matter. Scale the output to the task; the internal candidate record is not a mandatory long report.

Return the result in the conversation. If file access is available and useful for substantial research, save an artifact in the user's chosen workspace. Respect existing budgets; optional additional agents must have distinct research questions, and their agreement does not validate an idea. The full workflow remains usable with one agent and this file.

## Method lineage

Research RIZZ combines TRIZ, Function-Oriented Search and analogical reasoning. The links below provide optional background and attribution. All instructions needed to use the skill are included above.

- [TRIZ40 — method and inventive principles](https://www.triz40.com/triz-method.php)
- [TRIZ Function-Oriented Search — MATRIZ](https://wiki.matriz.org/docs/triz/problem-solving-tools-5890/function-oriented-search-fos/)
- [ccTOPP — Function-Oriented Search prompt](https://github.com/jenson500/triz-prompt-engineering/blob/main/prompts/technical_triz/function_oriented_search/function_oriented_search.xml)
- [Analogical Reasoning — source-to-target structure and search](https://github.com/andrew7shen/ar_science)
- [Yogsoth — abstraction, mapping and instantiation](https://github.com/yogsoth-ai/de-anthropocentric-research-engine/blob/main/skills/analogical-discovery/SKILL.md)
