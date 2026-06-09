# Three-Axis Vulnerability Diagnostic

## Product

**Product:** Communication Feed

**Your Role:** PM

---

## Scores

### Contextual Moat
- Mobile is underused as a daily surface. If Workday remains a place people visit only for administrative tasks, we leave value on the table. Communication Feed gives frontline workers a reason to come back every day because it helps them run the shift, not just update records.
- It sits on top of the workforce system of record. The feed can be personalized by schedule, role, training status, compliance context, and manager relationship in ways a generic communication tool cannot

And because it sits directly on top of the workforce system of record, it can do something no generic communication tool can: personalize every item by shift, role, compliance status, and team context. A message in Teams is the same for everyone. A feed item in Workday knows you clock in at 2pm, your food safety certification expires Friday, and your manager posted a video this morning. That's the moat.


**Score rationale:** - 4.5 


**Named attacker (from partner challenge):**
Blink and Zipline, they're growing fast but don't have the workforce data underneath

---

### Data Advantage

Workday doesn't just know what a worker needs to hear. It knows why, when, and what they should do about it.


**Score rationale:** - 4 

**Named attacker (from partner challenge):**

TBD — to be confirmed with partner/competitive team before doc is finalized

---

### Platform Exposure 

Workday's frontline advantage depends on workers and managers choosing our surface over the tools they already have open Teams, WhatsApp, a scheduling app their company has used for years. The risk is not that a single competitor out-features us. It is that the frontline experience remains fragmented across platforms we don't control, and workers never develop the habit of opening Workday first.

The mitigation is the feed and the agent layer, if Workday is the place where things get done, not just communicated, the platform stickiness follows. But that only holds if execution stays inside Workday and doesn't route workers back out to third-party surfaces to complete the action.

**Score rationale:** - 4 

**Named attacker (from partner challenge):**

- Competitors like UKG, Blink, and Zipline are filling that gap, but the deeper exposure is that workers are already using WhatsApp groups, manager texts, and printed schedules to get by. Those habits harden fast, and a better enterprise app is rarely enough to break them.
---

## Top Vulnerability
 - Workers still use WhatsApp, text threads, or side channels to coordinate shifts and urgent updates. Once that habit is established it's very hard to displace.


## Confidence Level
H
