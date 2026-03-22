---
name: Service Metrics
description: This skill should be used when the user asks about "service metrics", "measuring service quality", "NPS", "net promoter score", "CSAT", "customer satisfaction", "CES", "customer effort score", "experience metrics", "service KPIs", "measuring design impact", "how to measure a service", "service performance", "qualitative metrics", "quantitative metrics", "measurement framework", "baseline measurement", "service evaluation", or needs help designing or implementing a framework for measuring service quality and user experience outcomes.
version: 1.0.0
---

# Service Metrics

Measuring a service answers the question: "Is this working?" Without measurement, improvements are invisible, failures go undetected, and design claims are untestable. Measurement is not a post-launch activity — it should be designed alongside the service itself.

Good service measurement combines quantitative data (what is happening, at scale) with qualitative understanding (why it is happening, and what it means). Neither alone is sufficient.

---

## The Measurement Challenge in Service Design

Services are harder to measure than products because:
- The "product" is partly co-produced by the user
- Value is often experienced over time, not at a single moment
- Multiple touchpoints and channels contribute to overall experience
- Outcomes often depend on user behaviour after the service interaction

Good measurement acknowledges this complexity rather than reducing it to a single number.

---

## Core Experience Metrics

### Net Promoter Score (NPS)

**What it measures:** Loyalty and advocacy. The degree to which users would recommend the service.

**How it works:**
> "On a scale of 0–10, how likely are you to recommend [service] to a friend or colleague?"

- Promoters (9–10): Loyal enthusiasts
- Passives (7–8): Satisfied but not enthusiastic
- Detractors (0–6): Unhappy and potentially harmful to reputation

**NPS = % Promoters − % Detractors**

Score ranges from -100 to +100. Positive is good. Above +50 is excellent.

**Follow-up question:** Always include an open text question: "What is the main reason for your score?" Without this, NPS is a number without explanation.

**Limitations:**
- Measures intention, not behaviour — people who say they'd recommend often don't
- Not actionable without qualitative context
- Not comparable across industries or contexts
- Can be gamed by timing (ask immediately after a good moment)

**Best for:** Tracking overall loyalty trend over time; identifying detractor segments.

---

### Customer Satisfaction Score (CSAT)

**What it measures:** Satisfaction with a specific interaction or overall service.

**How it works:**
> "How satisfied were you with [interaction/service]?"
Response scale: 1–5 (Very dissatisfied to Very satisfied) or 1–10.

**CSAT % = (Positive responses / Total responses) × 100**

Typically: responses of 4 or 5 on a 5-point scale are counted as "satisfied."

**When to use:** After a specific service interaction (post-call, post-appointment, post-purchase). Good for interaction-level measurement.

**Limitations:**
- High satisfaction at individual touchpoints does not equal good overall experience
- Satisfaction bias — people are more likely to complete satisfaction surveys after positive experiences
- CSAT does not distinguish between "fine" and "excellent"

---

### Customer Effort Score (CES)

**What it measures:** How easy or difficult it was for the user to accomplish their goal.

**How it works:**
> "The organisation made it easy for me to handle my issue."
Response: 1–7 (Strongly disagree to Strongly agree)

Or: "How much effort did you have to put in to [complete task]?"
Response: 1–5 (Very low effort to Very high effort)

**Why it matters:** Research consistently shows that reducing effort is more strongly correlated with loyalty than improving satisfaction. Customers who experience high-effort interactions are more likely to churn, complain, and disengage.

**Best for:** Measuring self-service channels; identifying friction in key tasks; evaluating process improvements.

---

### Task Completion Rate

**What it measures:** The proportion of users who successfully complete the intended task.

Used primarily for digital services and online forms. Measured through analytics (completion vs. abandonment) or usability testing (observed task success).

**Variants:**
- Form/application completion rate
- Self-service resolution rate (did the user resolve their issue without human contact?)
- Error rate (how often do users submit incorrect or incomplete information?)

---

## Qualitative Measurement

Quantitative metrics tell you what is happening. Qualitative research tells you why — and what it means for users.

### Qualitative indicators

- **Themes in open text responses:** What words and topics appear most frequently in free-text survey responses?
- **Complaint analysis:** What are the most common complaints? What is the underlying experience they describe?
- **Compliment analysis:** What do users praise? What are the moments of delight?
- **Staff observation:** What do frontline staff report hearing from users?
- **Longitudinal interviews:** Follow a cohort of users over time to understand how experience evolves.

### Combining quantitative and qualitative

| Quantitative question | Qualitative follow-up |
|----------------------|----------------------|
| NPS dropped 8 points | Why? Interview detractors |
| Task completion rate fell to 62% | Where do users drop off? Run usability testing |
| High CSAT despite long wait times | What compensates for the wait? Explore in interviews |
| 30% of users contact support after digital journey | What question couldn't they answer themselves? |

---

## Designing a Measurement Framework

### 1. Define what success looks like

Before measuring anything, answer: "What would success look like for users? For the organisation? For delivery staff?"

Success should be multi-dimensional:
- **User outcomes:** Did users achieve their goal? How did it feel? What changed for them?
- **Service outcomes:** Efficiency, error rates, staff time, cost per transaction
- **Business outcomes:** Retention, satisfaction, complaint reduction, revenue
- **Equity outcomes:** Are outcomes equal across user segments? Who is the service not serving?

### 2. Choose metrics that reflect your goals

Match metrics to outcomes:

| Goal | Relevant metric |
|------|----------------|
| Improve ease of use | CES, task completion rate, error rate |
| Build loyalty | NPS, retention rate, repeat usage |
| Improve satisfaction | CSAT, complaint rate, open-text themes |
| Reduce staff burden | Contact rate, escalation rate, call volume |
| Improve equity | Disaggregated metrics by user segment |

### 3. Establish a baseline

Measure before you change anything. A baseline is essential for demonstrating impact. Without it, you cannot claim that an improvement caused a change.

### 4. Set targets

Targets should be:
- Specific: "Increase task completion rate from 62% to 80%"
- Time-bound: "By end of Q4"
- Evidence-based: Based on sector benchmarks or past performance

Avoid targets without a rationale — they are arbitrary and undermine measurement culture.

### 5. Define collection method and frequency

For each metric:
- How will the data be collected? (Survey, analytics, observation, complaints system)
- Who will collect it?
- How frequently? (Real-time, weekly, monthly, quarterly)
- Who will review it and act on it?

### 6. Close the loop

Measurement without action is vanity. Define a review cadence and a process for turning measurement insights into design or operational improvements.

---

## Disaggregation and Equity

Aggregate metrics hide inequalities. An overall NPS of +35 may look healthy until you disaggregate by user segment and discover that elderly users score -12 while digitally confident users score +60.

**Always disaggregate by dimensions relevant to your service:**
- Digital capability / channel preference
- Geography (urban vs. rural)
- Age
- Disability or health status
- Language and literacy
- Prior service experience (new vs. returning user)
- Outcome (successful vs. failed service interaction)

**Make equity a named design goal, not a secondary consideration.**

---

## Service Measurement Dashboard

A measurement dashboard makes performance visible to the team and stakeholders.

### What to include

| Layer | Metrics | Refresh rate |
|-------|---------|-------------|
| User experience | NPS, CSAT, CES, open-text themes | Monthly |
| Task performance | Completion rate, error rate, abandonment | Weekly |
| Operational | Contact volume, handle time, error correction | Weekly |
| Outcomes | Goal completion, downstream behaviour change | Quarterly |
| Equity | Disaggregated experience metrics by segment | Quarterly |

### Design principles for dashboards

- Show trends, not just snapshots (a single data point means nothing)
- Highlight outliers and alerts — not just average performance
- Link metrics to actions: when [metric] crosses [threshold], review [process]
- Make it visible to the team, not just management

---

## Common Mistakes

**Measuring satisfaction, not outcomes.** A user can be satisfied with a service that did not help them achieve their goal. Satisfaction is a perception, not a proxy for impact.

**Choosing metrics because they are easy to collect.** The easiest metric is not always the most useful. Design the measurement framework around your goals, then find collection methods.

**Treating the metric as the goal.** Goodhart's Law: "When a measure becomes a target, it ceases to be a good measure." NPS can be inflated by timing surveys after positive moments. Task completion can be inflated by simplifying tasks to the point of uselessness.

**Measuring but not acting.** If insights from measurement don't feed back into design or operations, measurement is performance, not practice.

**Not disaggregating.** Aggregate metrics hide the experiences of the users who need the most attention.

---

## Level Guidance

**Junior:** Understand the difference between what each metric measures. NPS measures advocacy. CSAT measures satisfaction. CES measures effort. They are not interchangeable. Know which to recommend for which purpose.

**Mid-weight:** Design measurement frameworks from first principles rather than defaulting to standard metrics. Start with: "What does success look like?" Work backwards to metrics that evidence that success.

**Senior / Lead:** Advocate for equity metrics alongside experience metrics. "Average" performance figures often mask significant inequalities in outcomes across user segments. Push for disaggregated reporting and make equity outcomes a visible part of service performance.

---

## Additional Resources

- **`references/measurement-framework-template.md`** — Template for designing a complete service measurement framework
- **`references/metrics-by-service-type.md`** — Recommended metric sets for common service types (healthcare, government, digital self-service, retail)
