# Measurement Framework Template

---

## Framework Header

| Field | Value |
|-------|-------|
| Service | [Service name] |
| Project / phase | [e.g., "Post-pilot evaluation" / "Live service monitoring"] |
| Framework owner | [Team or role responsible] |
| Review cadence | [How often will the framework be reviewed?] |
| Date created | [Date] |
| Date last updated | [Date] |

---

## Success Definition

Before selecting metrics, define what success looks like from each perspective:

### User success
> "Users will have successfully [achieved goal] and will feel [emotional outcome]."

Example: "Users will have successfully completed their application without needing to call for help, and will feel confident that they have done it correctly."

### Organisational success
> "The organisation will have [operational/business outcome]."

Example: "The organisation will have reduced the volume of incomplete applications by 40%, reducing processing time and error correction workload."

### Equity success
> "The service will achieve [outcome] equally across [user segments]."

Example: "The service will achieve task completion rates above 75% for all user segments, including those with lower digital confidence."

---

## Metrics Register

### User Experience Metrics

| Metric | What it measures | Target | Baseline | Collection method | Frequency | Owner |
|--------|-----------------|--------|----------|-----------------|-----------|-------|
| NPS | Loyalty and advocacy | [e.g., +40] | [Current score] | Post-interaction survey | Monthly | [Name] |
| CSAT | Satisfaction with service | [e.g., 80%] | [Current score] | Post-interaction survey | Monthly | [Name] |
| CES | Ease of completing task | [e.g., 5.5/7] | [Current score] | Post-transaction survey | Monthly | [Name] |
| Open text themes | Qualitative experience | [Themes to track] | [Current themes] | Survey free text, complaints | Monthly | [Name] |

### Task Performance Metrics

| Metric | What it measures | Target | Baseline | Collection method | Frequency | Owner |
|--------|-----------------|--------|----------|-----------------|-----------|-------|
| Task completion rate | % of users who successfully complete intended task | [e.g., 80%] | [Current rate] | Analytics | Weekly | [Name] |
| Error rate | % of submissions with errors requiring correction | [e.g., <10%] | [Current rate] | Operations data | Weekly | [Name] |
| Abandonment rate | % of users who start but don't complete | [e.g., <20%] | [Current rate] | Analytics | Weekly | [Name] |
| Self-service resolution rate | % resolved without human contact | [e.g., 70%] | [Current rate] | Contact centre data | Weekly | [Name] |

### Operational Metrics

| Metric | What it measures | Target | Baseline | Collection method | Frequency | Owner |
|--------|-----------------|--------|----------|-----------------|-----------|-------|
| Contact rate | Contacts per transaction | [e.g., <0.3] | [Current rate] | CRM / contact centre | Weekly | [Name] |
| Average handling time | Time per interaction | [e.g., <8 min] | [Current time] | Contact centre system | Weekly | [Name] |
| Cost per transaction | End-to-end cost | [e.g., <£12] | [Current cost] | Finance data | Monthly | [Name] |

### Outcome Metrics

| Metric | What it measures | Target | Baseline | Collection method | Frequency | Owner |
|--------|-----------------|--------|----------|-----------------|-----------|-------|
| Goal achievement rate | Did the user achieve their underlying goal? | [Target] | [Baseline] | Longitudinal tracking / survey | Quarterly | [Name] |
| Return / repeat contact rate | Unresolved issues leading to repeat contact | [Target] | [Baseline] | CRM data | Monthly | [Name] |

### Equity Metrics

| Segment | Metric | Target | Baseline | Notes |
|---------|--------|--------|----------|-------|
| Low digital confidence users | Task completion rate | ≥ 75% | [Current] | |
| Users aged 65+ | CSAT | ≥ 75% | [Current] | |
| Rural / non-online users | Self-service resolution rate | [Target] | [Current] | |
| Users with disabilities | Task completion rate | ≥ [same as overall target] | [Current] | |

---

## Data Collection Plan

### Survey Design

| Survey | Trigger | Channel | Length | Key questions |
|--------|---------|---------|--------|---------------|
| Post-transaction | Immediately after completing transaction | Email / SMS / in-product | Max 3 questions | NPS, CES, open text |
| Post-support interaction | 24 hours after contact | Email | Max 5 questions | CSAT, resolution confirmation, open text |
| Longitudinal | 30 / 90 days post-service | Email | Max 8 questions | Goal achievement, NPS trend |

### Analytics Setup

| Metric | Tool | Event to track | Notes |
|--------|------|----------------|-------|
| Task completion | [Analytics platform] | [Event name] | Define "completion" explicitly |
| Abandonment | [Analytics platform] | [Event name] | Track at each step |
| Error rate | [Form / CRM system] | [Event name] | |

### Qualitative Review

| Activity | Frequency | Sample size | Owner |
|----------|-----------|-------------|-------|
| Open text analysis | Monthly | All responses | [Name] |
| Complaint review | Monthly | All complaints + sample | [Name] |
| User interviews | Quarterly | 6–8 users | [Name] |
| Staff insight session | Monthly | Front-line team | [Name] |

---

## Review Cadence

| Review | Frequency | Attendees | Output |
|--------|-----------|-----------|--------|
| Metrics review | Monthly | Design + product + operations lead | Dashboard update, action log |
| Deeper analysis | Quarterly | Full team + stakeholders | Insight report, roadmap review |
| Annual evaluation | Annual | Senior stakeholders | Strategic review, framework update |

---

## Alert Thresholds

Define when a metric triggers immediate attention:

| Metric | Alert threshold | Response |
|--------|----------------|---------|
| NPS | Drops > 10 points in one period | Qualitative investigation within 2 weeks |
| Task completion | Falls below [X]% | UX review within 1 week |
| Complaint volume | Increases > 30% in one period | Operational review within 3 days |
| Equity gap | Any segment > 15% below overall average | Targeted investigation within 4 weeks |

---

## Closing the Loop

| Finding type | Process | Owner | Timeline |
|-------------|---------|-------|---------|
| Friction in digital journey | UX review → backlog item | Product | Within 2 sprints |
| Process failure identified | Operations review → process improvement | Operations | Within 1 month |
| Unmet user need identified | Design investigation → prototype and test | Design | Within 1 quarter |
| Equity gap identified | Targeted research → specific intervention | Design + operations | Within 1 quarter |
