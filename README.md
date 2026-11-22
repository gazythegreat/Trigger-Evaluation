# Trigger Evaluation

**A framework for evaluating whether an AI crash trigger has fired** — built to
be imported by any AI agent (Muse, Claude, ChatGPT, Grok, Gemini) so that each
one evaluates the same question, against the same definitions, *afresh*: the
framework carries no statuses, no baselines and no other agent's conclusions.

## What this is

Raymond's framework for distinguishing a valuation correction in AI names from
a system-wide financial crash in the AI build-out. It defines four crash
triggers, the evidence standard a firing requires, and the cascade the
triggers are expected to follow — plus a neutral procedure for running the
evaluation. One trigger firing is warning / correction-level stress; two or
more firing together is an escalation. Monitoring only — the framework
produces assessments, never investment advice.

## The four triggers

1. **Financing flip** — Hyperscaler (Microsoft, Alphabet, Amazon, Meta, plus
   Oracle) capital expenditure overtakes operating cash flow AND the build-out
   shifts to large-scale debt funding, rather than being funded mainly from
   operating cash flow. Sub-indicators: the **neoclouds** (CoreWeave, Nebius,
   Lambda, Crusoe, IREN, Nscale — the most leveraged, purest-play part of the
   build-out, where stress should show first) and an **equity-pressure
   warning layer** (multiple compression, buybacks cut because capex consumes
   operating cash flow, dilutive equity funding returning at scale) — a
   warning layer, not the trigger firing.
2. **Utilisation fall** — GPU / data-centre utilisation falls materially,
   vacancy rises, or GPU rental prices fall materially: capacity stops being
   supply-constrained and starts sitting idle. Sub-indicator: **price per
   token**, read by cause — falls driven by discounting to fill idle capacity
   are the signature; efficiency-driven falls are not.
3. **Revenue conversion failure** — Lab run-rate revenue (ARR) fails to
   convert into recognised, gross-margin-positive revenue for 2–3 consecutive
   quarters, or recognised revenue growth stalls while capex guidance keeps
   rising. (ARR is an annualisation; recognised revenue is what the accounts
   book. The two are never interchangeable.)
4. **Backlog cancellation** — Cloud/AI backlog or committed capacity is
   cancelled or renegotiated down. Slower backlog growth does not count;
   slippage of unbuilt, uncommitted projects does not count.

## The evidence rule

An opinion, post, video or article alone **never** counts as a trigger
firing, however prominent its author. A firing requires corroborating
financial or market evidence: an earnings release, a regulatory filing, a
guidance change, a bond or CDS price move, published utilisation / vacancy /
rental-price data, or a backlog disclosure. Price-only market moves are
reported as price-only moves, with the absence of corroboration stated.

## The expected cascade

Demand-led: Trigger 2 → Trigger 1 → Trigger 3 → Trigger 4.
Financing-led: Trigger 1 → Trigger 2 → Trigger 3 → Trigger 4.
The observed order is diagnostic of the origin, and progression from one
stage to the next is itself an escalation.

## How to use it

Import `SKILL.md` and follow its evaluation procedure:

1. **Gather afresh** from primary sources (filings, earnings releases,
   official company releases, published market-data series). Do not import
   any prior assessment, status or conclusion from another agent's
   scoreboard or report — treat one, if encountered, as a claim to be
   tested, not a given.
2. **Test each trigger separately**: firing condition, evidence found (class,
   source, date), verdict — *firing*, *not firing*, or *not determinable on
   the evidence available* (naming what is missing). Assess company by
   company where the definition names companies.
3. **Classify price action honestly**: if only prices moved, say so, and say
   which corroborating evidence classes were checked and found absent.
4. **Read the cascade**: stages firing, observed order, demand-led or
   financing-led.
5. **Report** one block per trigger plus a closing summary: how many
   triggers firing, cascade stage if any, and the single new datum that
   would most change the assessment. Date every movement relied on; never
   re-report an already-assessed movement as new.

## What this repository deliberately does not contain

No trigger statuses. No company attributions. No figures or baselines. No
classifications of past episodes. No proposed amendments to the framework.
No other agent's reasoning. Those are exactly what each evaluating agent
must produce for itself. If you believe a definition is wrong or incomplete,
say so separately and explicitly — do not silently evaluate against a
different definition.

## Files

- `SKILL.md` — the skill itself: the definitions, the evidence rule, the
  cascade and the evaluation procedure, in importable form.
- `skill.yaml` — name, title and description metadata for the skill.

## Provenance

Trigger definitions set by Raymond on 31 Oct 2026, with the sub-indicators he
directed (neoclouds, the equity-pressure warning layer, price per token read
by cause), his evidence rule and his expected cascade. Formalised as a skill
on 23 Nov 2026 at his direction, deliberately stripped of the formalising
agent's own assessments so other agents approach the question without them.
