# My AI Product Strategy

> A living strategy built across 6 sessions. Each module adds one component. By Module 6, this repo IS your strategy — version-controlled, board-ready, portable.

---

## Strategy at a Glance

| Component | Module | Status | Key Artifact |
|-----------|--------|--------|-------------|
| **The Bet** | M1 | [ ] | `01-the-bet/` |
| **The Moat** | M2 | [ ] | `02-the-moat/` |
| **The Margin** | M3 | [ ] | `03-the-margin/` |
| **The Contract** | M4 | [ ] | `04-the-contract/` |
| **The Guardrails** | M5 | [ ] | `05-the-guardrails/` |
| **The Pitch** | M6 | [ ] | `06-the-pitch/` |

---

## The Bet (M1)

**What we're building, for whom, why now.**

- **Product:** Communication Feed: a dedicated engagement tab in Workday Mobile where AI agents surface the right information, at the right time, to the right frontline team, turning passive communication into proactive action.
- **AI Value Archetype:** Ambient intelligence — agents show up proactively in the team's shared space without being asked, rather than responding to individual queries.
- **Vulnerability Scores:** Moat 4/5 · Data 5/5 · Platform 3/5
- **Top Risk:** Sana API architecture not confirmed for mobile, late changes could force significant rework and delay the agent integration layer the entire feed depends on.
- **Confidence:** H
- **Prototype:**
- **Kill Criteria:** If Mobile App MAU drops below 9M, if Sana confirms a separate mobile app strategy that fragments the user base, or if cross-functional teams cannot commit to the dependency work needed for Phase 1 by end of Q2.

→ Details: [`01-the-bet/`](01-the-bet/)

---

## The Moat (M2)

**Why this won't get copied in 6 months.**

- **Data Flywheel Score:** 16/20
- **Weakest Loop:** Recursive Learning — worker corrections and team engagement signals are not yet systematically feeding back into model improvement. The feedback pipeline exists in theory (HITL escalations, thumbs-down signals) but is not yet wired into retraining or golden dataset updates.
- **Competitive Position:** Workday sits in the high-data/high-integration quadrant. UKG Talk sits in the high-breadth/low-intelligence quadrant. Blink and Zipline sit in the high-UX/low-data quadrant. No competitor occupies the high-data/high-intelligence/native-agent quadrant, that is the space Workday is building toward.
- **Encroachment Defense:** The moat is the data, not the surface. Competitors can copy the feed UI. They cannot copy the schedule, compliance status, training gaps, compensation history, and recognition data that make the agents smart. That data only exists inside Workday.
- **Vendor Portability:** Partial, the feed surface is Workday-native, but agent intelligence currently depends on Sana API (unconfirmed for mobile) and AIX/Agent-Forge (inconsistent adoption across agent teams). Full lock-in requires resolving both dependencies.

→ Details: [`02-the-moat/`](02-the-moat/)

---

## The Margin (M3)

**Will this make money or bleed it?**

- **Gross Margin (current):** Not yet measured - feed is pre-revenue, in prototype stage.
- **Gross Margin (AI-adjusted):** Target 70%+ at scale, assuming cascading strategy keeps frontier model calls to 30% of total interactions and HR ticket deflection generates $15+ in cost savings per user per month against $0.24 AI COGS.
- **Pricing Model:** Usage-based via flex credits — every agent interaction in the feed is a flex credit event. Feed drives daily engagement which drives credit consumption which drives revenue. SKU attach (Expense Management, Frontline Agent, Learning modules) accelerates as feed MAU grows.
- **Cascading Strategy:**  70/30 — 70% of feed interactions handled by triage model or rule-based logic (shift claims, reactions, acknowledgments). 30% escalate to frontier model (AI Overview generation, policy explanations, multi-turn agent conversations)
- **Break-even at:** Approximately 500K daily active feed users assuming $0.24 AI COGS per user per month and $15 average HR ticket deflection value per user per month. Actual break-even subject to validation with Finance.

→ Details: [`03-the-margin/`](03-the-margin/)

---

## The Contract (M4)

**Why users will trust a probabilistic system.**

- **Reliability Target:**
- **Golden Dataset:** __ rows, __ adversarial
- **Confidence UX:** [approach]
- **HITL Architecture:**
- **Failure Mode Coverage:**

→ Details: [`04-the-contract/`](04-the-contract/)

---

## The Guardrails (M5)

**What breaks when this scales — and what compounds.**

- **Compounding System:** [describe feedback loops]
- **Governance Posture:** [approach]
- **Shadow AI Status:** __ tools found, __ triaged
- **Agent Boundaries:**
- **Regulatory Exposure:**

→ Details: [`05-the-guardrails/`](05-the-guardrails/)

---

## The Pitch (M6)

**How you get this funded, shipped, and adopted.**

- **Horizon 1 (Now):**
- **Horizon 2 (Next):**
- **Horizon 3 (Bet):**
- **Board Narrative:** [1-sentence thesis]
- **Key Metric:**

→ Details: [`06-the-pitch/`](06-the-pitch/)
