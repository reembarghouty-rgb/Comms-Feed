# Golden Dataset & Reliability Contract

## Golden Dataset Spec

| # | Input | Expected Output | Edge Case? | Judge Type |
|---|-------|----------------|-----------|-----------|
| 1 | Frontline Agent posts an open Saturday shift to the team feed|Shift is visible to all eligible team members simultaneously; first qualified worker to tap claims it, and the card updates to 'claimed' for everyone else in real time| N | Rule |
| 2 |Jordan approves a drafted 1-year anniversary post for Maya |Post appears in the team feed within 5 seconds of approval, tagged with Maya's name and visible to all team members | N | Rule|
| 3 |A new policy update on bonus structure is posted; Maya asks 'Does this apply to this month's earnings? |Agent's response correctly states whether the policy is retroactive, in a way that's clear and specific to Maya's situation, without contradicting the source policy document | N |LLM |
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
Agent does not surface a card or take action at all. Instead, it either stays silent or redirects to a human path e.g., "This question needs a closer look. Want me to connect you with your manager or HR?"

**User control surface:**

## Reliability Contract

| Metric | Target | Measurement | Alert Threshold |
|--------|--------|-------------|-----------------|
| Accuracy |90%|Run golden dataset weekly; compare agent output to verified correct answers |Alert if accuracy drops below 85% on any run |
| Hallucination rate |<2% |Run red-team and golden dataset prompts; flag any response not grounded in actual Workday data |Alert if hallucination rate exceeds 3%|
| Latency (p95) |<3 seconds |Measure response time from user action (e.g., tap to claim, ask a question) to agent response, for 95% of requests |Alert if p95 latency exceeds 5 seconds|
| Drift velocity |<5% change month over month |Compare current month's accuracy/hallucination rate against the prior month's baseline|Alert if any metric shifts more than 10% in a single month without a known cause (e.g., model update) |

## HITL Architecture
<!-- When does a human step in? What's the escalation path? -->

## Red-Team Findings
*What failure mode did your partner find that you missed?*
