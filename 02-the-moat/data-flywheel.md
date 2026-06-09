# Data Flywheel Map

> Score each loop 1-5. Your weakest loop is where competitors attack first.
> The four loops below are the M2 starting point - adapt if your product has 2 or 6 loops instead of 4.

## Flywheel Loops

| Loop | What It Measures | Score 1 | Score 5 | Score |
|------|------------------|---------|---------|-------|
| **Correction** | Do users fix AI outputs? Is that signal captured and reused? | No capture | Automated retraining | 2/5 |
| **Preference** | Does the product learn individual / team preferences over time? | Stateless | Deep personalization | 3/5 |
| **Domain Context** | Does usage in one area improve quality in adjacent areas? | Siloed | Cross-domain transfer | 5/5 |
| **Network** | Does each new user / team make the product better for everyone? | Isolated | Strong network effects | 4/5 |

### Correction Loop - 2/5
**What you capture today:**
No explicit correction mechanism in the feed yet. But Workday already captures timecard corrections, absence disputes, and schedule change requests those are proxy signals for when the system got something wrong.
**How it compounds:**
As the feed surfaces agent driven actions, worker acceptance or rejection of those actions becomes the correction signal. Every ignored nudge or manually overridden suggestion trains the model.

### Preference Loop - 3/5
**What you capture today:**
Workday already holds historical behavior which shifts workers took, when they clocked in, what learning they completed, how fast they responded to open shift alerts. 

**How it compounds:**
Every tap, skip, and timing pattern in the feed adds a personalization layer on top of the existing behavioral history. Over time the feed learns the individual, not just the role.

### Domain Context Loop - 5/5
**What you capture today:**
All of it; pay, time, scheduling, compliance, learning, performance, team structure. This is the full workforce system of record. No competitor starts with this. The feed inherits it on day one.

**How it compounds:**
A worker's scheduling pattern informs their pay modeling. Their compliance status informs their task prioritization. The data is already cross-domain, the feed just surfaces it.

### Network Loop - 4/5
**What you capture today:**
Team-level data already exists; team rosters, shift coverage patterns, group compliance rates. 

**How it compounds:**
As more workers use the feed, shift claim patterns improve open shift recommendations for the whole team. Manager posts reach more workers. Coverage intelligence gets sharper with every interaction.

**Total Flywheel Score: 14/20**

**Weakest Loop:**
Correction Loop: workers have no way to tell the system when it got something wrong, so the agent never learns from its mistakes.
**Fix for weakest loop:**
Build lightweight rejection signals directly into the feed. A dismissed nudge, a skipped action, or a "this isn't relevant" tap feeds back into the model automatically.

---

## Encroachment Threat Assessment

### 1. Platform Encroachment
**Attacker:**
**Vector:**
**Time-to-threat:**
**% of value at risk:**

### 2. Vertical Competitor
**Attacker:**
**Vector:**
**Time-to-threat:**
**% of value at risk:**

### 3. Adjacent Expansion
**Attacker:**
**Vector:**
**Time-to-threat:**
**% of value at risk:**

---

## 90-Day Encroachment Plan

*Your partner played the Big Tech attacker. What was their plan to kill you?*

**Attacker:**
**Attack vector (target the weakest loop):**
**Weeks 1-4 - what they ship:**
**Weeks 5-8 - how they poach users:**
**Weeks 9-12 - why users don't come back:**
**Your defense:**
