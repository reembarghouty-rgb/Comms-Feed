# Golden Dataset & Reliability Contract

## Golden Dataset Spec

| # | Input | Expected Output | Edge Case? | Judge Type |
|---|-------|----------------|-----------|-----------|
| 1 | | | Y/N | rule / LLM |
| 2 | | | Y/N | rule / LLM |
| 3 | | | Y/N | rule / LLM |
| 4 | | | Y/N | rule / LLM |
| 5 | | | Y/N | rule / LLM |

**Adversarial rows included:** __
**Coverage gaps identified by partner:**

## Confidence UX Design

**Approach:** 
Tiered confidence with human-in-loop trigger

**High confidence (>90%):**
Agent takes the action automatically and surfaces it in the feed with no extra friction e.g., shift claimed, training card shown, recognition post drafted and ready for one-tap approval. 

**Medium confidence (70-90%):**
Agent surfaces the suggestion but frames it as a recommendation rather than a fact, and requires explicit confirmation before acting e.g., "Based on your hours, you may be eligible for the new bonus tier. Want me to walk you through it?".

**Low confidence (<70%):**
Agent does not surface a card or take action at all. Instead, it either stays silent or redirects to a human path — e.g., "This question needs a closer look. Want me to connect you with your manager or HR?"

**User control surface:**

## Reliability Contract

| Metric | Target | Measurement | Alert Threshold |
|--------|--------|-------------|-----------------|
| Accuracy | | | |
| Hallucination rate | | | |
| Latency (p95) | | | |
| Drift velocity | | | |

## HITL Architecture
<!-- When does a human step in? What's the escalation path? -->

## Red-Team Findings
*What failure mode did your partner find that you missed?*
