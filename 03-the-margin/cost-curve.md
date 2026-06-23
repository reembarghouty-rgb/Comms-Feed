# Cost Curve & Pricing Strategy

## Cost Model

| Cost Category | Per-User/Month | Notes |
|--------------|----------------|-------|
| Inference (primary model) |$0.08|Covers Self-Service Agent, AI Overview, Frontline Agent shift logic, LLM calls for generation and reasoning |
| Inference (cascading/triage) |$0.02|Lightweight classifier that routes simple requests (shift claim, reaction) away from the expensive model |
| Infrastructure |$0.03 |API hosting, compute, latency optimization, decreases per user as MAU scales |
| Data/storage |$0.01|Feed posts, audit logs, conversation history, golden dataset, low per user but compounds at scale |
| Human-in-the-loop |$0.10|Estimated at ~5% escalation rate; each escalation routed to manager, HR, or support |
| **Total AI COGS** |$0.24 |Target: offset by $15+ in HR ticket deflection per user per month |

## Cascading Strategy
<!-- Cheap model → frontier model routing logic -->

**Triage model:**
**Frontier model:**
**Routing rule:**
**Expected cascade ratio:**

## Pricing Model

**Current pricing:**
**Proposed AI pricing:**
**Model:** seat-based / usage-based / outcome-based / hybrid

## Stress Tests

| Scenario | Impact on Margin | Response |
|----------|-----------------|----------|
| Inference costs 3x | | |
| Heaviest segment doubles | | |
| Model provider raises prices 50% | | |

## Board One-Pager
<!-- Before/After: Old SaaS revenue vs. AI usage revenue for your product -->

**Before (traditional SaaS):**
**After (AI-enabled):**
**Net margin shift:**
