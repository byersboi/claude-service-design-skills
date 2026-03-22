# Service Blueprint Template

Use this template as a starting scaffold. Adapt columns (stages/steps) and rows to your specific service.

---

## Blueprint Header

| Field | Value |
|-------|-------|
| Service | [Name of the service] |
| Scope | [Start point → End point, e.g., "First awareness → 30 days post-purchase"] |
| Customer segment | [Which persona this blueprint represents] |
| State | [Current state / Future state / Concept] |
| Date | [Date created or last updated] |
| Owner | [Team or individual responsible] |
| Version | [v1.0] |

---

## Blueprint Rows — Prompts Per Layer

### Physical Evidence
*Everything the customer can see, hear, touch, or interact with at this stage.*

Questions to ask:
- What does the customer receive or encounter here?
- What digital or physical artefact is present?
- What does the environment look like?
- What is the quality and consistency of this evidence?

Examples: Website homepage, confirmation email, waiting room, uniform, receipt, packaging, app notification, signage

---

### Customer Actions
*What does the customer actually do at this stage? Grounded in research.*

Questions to ask:
- What specific steps does the customer take?
- What decisions do they make?
- What workarounds do they use?
- What do they do when the intended path doesn't work?

Format: Action verbs — "Searches online", "Calls helpline", "Waits in queue", "Completes form", "Receives confirmation"

---

### ──── LINE OF INTERACTION ────

*Above this line: customer. Below this line: service provider visible to customer.*

---

### Frontstage Actions
*What does the employee or automated system do that the customer can directly experience?*

Questions to ask:
- What does the customer-facing employee say or do?
- What does the system show or respond?
- What automated communications are triggered?
- How does this vary by channel?

Format: "Greets customer", "Verifies identity", "Processes payment", "Sends SMS confirmation", "Provides advice"

---

### ──── LINE OF VISIBILITY ────

*Above this line: visible to customer. Below this line: happens out of customer sight.*

---

### Backstage Actions
*What do employees do behind the scenes to make the frontstage action possible?*

Questions to ask:
- What preparation happened before this customer interaction?
- What does the employee do after the customer interaction?
- What data retrieval or updating is required?
- What quality checks happen?

Format: "Updates CRM record", "Retrieves patient notes", "Prepares order for dispatch", "Escalates to supervisor", "Checks availability"

---

### ──── LINE OF INTERNAL INTERACTION ────

*Above this line: customer-facing teams. Below this line: internal support functions.*

---

### Support Processes
*What internal systems, tools, teams, and third parties are required to support the service at this stage?*

Questions to ask:
- What systems does the employee rely on?
- Which internal teams need to be involved?
- Which third parties are involved?
- What data flows between systems?

Format: "CRM system", "Payment gateway", "Logistics partner", "IT infrastructure", "Finance approval workflow", "Legal review"

---

## Stage Column Template

For each stage, capture:

```
STAGE: [Stage name, e.g., "Awareness", "Booking", "Service delivery", "Follow-up"]

Physical evidence: [What is visible/tangible]

Customer action: [What the customer does]

Frontstage action: [What employee/system does, visible to customer]

Backstage action: [What happens behind the scenes]

Support process: [Systems and internal functions involved]

Pain points: [What breaks down or frustrates at this stage]
Wait time: [Customer-facing wait | Internal processing time]
Opportunity: [What could be improved or redesigned]
```

---

## Annotation Key

Use consistent visual language across blueprints:

| Symbol / Colour | Meaning |
|----------------|---------|
| Red border / ⚡ | Fail point — where things break down |
| Orange border / ⏱ | Wait time — customer or internal delay |
| Green border / 💡 | Opportunity for improvement |
| Blue border / 📎 | Evidence from research |
| Yellow border / ❓ | Assumption — needs validation |
| Dashed border | Automated / system action |
| Solid border | Human action |

---

## Example: Coffee Shop Order (Abbreviated)

| | Awareness | Order | Payment | Wait | Receive | Depart |
|---|---|---|---|---|---|---|
| **Physical evidence** | Menu board, shop window | Menu, till, staff | Receipt, card terminal | Counter, queue display | Cup with name, packaging | Receipt |
| **Customer actions** | Reads menu | States order | Taps card | Waits at end of counter | Collects drink | Leaves |
| LINE OF INTERACTION |||||||
| **Frontstage** | — | Takes order verbally | Processes payment | Calls name | Hands over drink | Thanks customer |
| LINE OF VISIBILITY |||||||
| **Backstage** | — | Writes on cup, passes to barista | Reconciles till | Prepares drink | Quality checks drink | — |
| LINE OF INTERNAL INTERACTION |||||||
| **Support processes** | — | EPOS system | Payment terminal, bank gateway | Espresso machine, stock | — | Waste disposal |
| **Pain points** | Menu is confusing | Noisy — mishears order | — | No way to tell position in queue | Can't hear name called | — |
| **Opportunities** | Clearer menu hierarchy | Repeat order confirmation | — | Digital queue display | Order number system | — |
