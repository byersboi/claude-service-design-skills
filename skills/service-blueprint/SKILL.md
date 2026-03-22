---
name: Service Blueprint
description: This skill should be used when the user asks about "service blueprint", "blueprinting", "frontstage backstage", "line of visibility", "mapping service processes", "back office front office mapping", "service design blueprint", "employee actions", "support processes", "create a blueprint", "blueprint template", or needs to map the operational components that deliver a service end-to-end.
version: 1.0.0
---

# Service Blueprint

A service blueprint maps every component required to deliver a service — from what the customer experiences at the front, to the people, processes, and systems working behind the scenes. It is the core artefact in service design that connects the customer experience to operational reality.

Unlike a journey map (which focuses on the customer), a blueprint focuses on the organisation delivering the service. It answers: "What has to happen, and who has to do it, for this experience to be possible?"

---

## Blueprint Structure

A service blueprint is read left to right (time) and top to bottom (visibility to customer).

### Rows (top to bottom)

```
Physical Evidence
────────────────────────────────────────────────────
Customer Actions
────────────────── LINE OF INTERACTION ──────────────
Frontstage Actions (visible employee/system actions)
────────────────── LINE OF VISIBILITY ───────────────
Backstage Actions (invisible employee/system actions)
────────────────── LINE OF INTERNAL INTERACTION ─────
Support Processes
```

**Physical Evidence**
Everything the customer can see, touch, or interact with at each stage: signage, app screens, letters, uniforms, spaces, receipts, email confirmations. This row reveals inconsistencies in the physical and digital touchpoints.

**Customer Actions**
What the customer does at each stage: searches, books, arrives, waits, uses, completes, follows up. Drawn directly from the journey map. These actions drive everything below.

**Line of Interaction**
The boundary between customer and service. Every point where the customer directly interacts with an employee or system.

**Frontstage Actions**
What employees or automated systems do that the customer can see or experience directly: greets the customer, processes the booking, provides advice, sends the confirmation.

**Line of Visibility**
The boundary between what the customer sees and what happens out of sight. Powerful for revealing invisible dependencies.

**Backstage Actions**
What employees do to support the service that the customer never sees: updates the record, escalates the query, checks inventory, prepares materials.

**Line of Internal Interaction**
The boundary between customer-facing staff and internal support functions.

**Support Processes**
Internal systems, tools, and third parties that support the service: CRM, payment systems, logistics partners, IT infrastructure.

---

## When to Create a Blueprint

**Current-state blueprint:** Map the existing service to understand how it actually works — revealing gaps, inefficiencies, and pain points. Use after research, in the Define phase.

**Future-state blueprint:** Design the intended service model. Use in the Develop and Deliver phases to align delivery teams on what needs to change.

**Concept blueprint:** A lighter-touch blueprint used to communicate a concept and test feasibility. Used during Develop to evaluate whether a concept is operationally realistic.

---

## Step-by-Step Process

### 1. Define scope and perspective

Decide:
- Which service or sub-service to blueprint (be specific — "full end-to-end" is often too large to start)
- Which customer segment you are mapping (one persona per blueprint)
- Current state or future state
- Time horizon (first contact through to ongoing use, or just the peak experience)

### 2. Gather source material

Assemble before you start the blueprint:
- Customer journey map (if it exists)
- Process maps or SOPs from operations
- Research insights (what customers actually do, not what they are supposed to do)
- Staff interviews or shadowing notes
- Existing system documentation

### 3. Map the customer actions

Start with the customer row. List every action the customer takes from left to right. Keep these grounded in research — what customers actually do, including workarounds and failures.

### 4. Map the frontstage actions

For each customer action, identify what the employee or system does that the customer can see. Note which channel this happens in (face to face, phone, digital, automated).

### 5. Map the backstage actions

For each frontstage action, identify what needs to happen behind the scenes to make it possible. Include manual processes, system checks, data retrieval.

### 6. Map support processes

Identify the internal systems, tools, and third parties that the backstage actions depend on.

### 7. Add physical evidence

Return to the top row and annotate the physical and digital artefacts present at each stage.

### 8. Annotate pain points and opportunities

Add swim-lane annotations for:
- Failure points (where things break down)
- Wait times (both customer-facing and internal)
- Opportunities for improvement
- Evidence from research

---

## Common Mistakes

**Mapping the ideal, not the real.** Blueprints drawn from documentation rather than observation typically show the intended process — which often bears little resemblance to what actually happens. Ground the current-state blueprint in research.

**Making it too large to be useful.** A blueprint covering every edge case and exception across all customer segments becomes unreadable. Scope tightly. Create multiple focused blueprints rather than one exhaustive map.

**Mixing current and future state.** Keep these separate. Conflating them creates confusion about what exists and what is intended.

**Treating it as a document, not a design tool.** The blueprint has most value when built collaboratively with operational stakeholders. Co-creating it surfaces knowledge, builds shared understanding, and generates buy-in.

**Ignoring the backstage.** Many journey maps already exist. The unique value of a blueprint is the backstage — the internal operations that make the experience possible. Don't just replicate the journey map.

**Never updating it.** Blueprints go stale quickly. Establish who owns the blueprint and how it will be maintained.

---

## Facilitation Tips

**Run blueprint workshops with mixed participants.** Include front-line staff, operations, IT, and design together. Each group holds different knowledge — none has the full picture alone.

**Build it iteratively.** Start with a rough swim-lane sketch. Add detail through iteration, not all at once.

**Use colour coding.** Highlight pain points in red, opportunities in green, evidence in blue, assumptions in yellow.

**Print large.** Blueprints are meant to be walked. Print at A0 or plotter size for workshop sessions. Digital tools (Miro, Mural) work well for remote teams.

---

## Level Guidance

**Junior:** Focus on correctly placing actions in the right row. When unsure, ask: "Can the customer see this?" If yes → frontstage. If no → backstage. Build the customer actions row first and work downward.

**Mid-weight:** Push for depth in the support processes row. Most pain points and inefficiencies live at the internal interfaces between teams and systems — the area that gets least attention.

**Senior / Lead:** Use the blueprint as a strategic alignment tool. In a workshop, disagreements about what belongs in the blueprint reveal deeper organisational issues around ownership, accountability, and process maturity. Surface these — they are the real design problems.

---

## Additional Resources

- **`references/blueprint-template.md`** — Row-by-row template with prompts for each layer
- **`references/blueprint-annotations.md`** — Standard annotation types, symbols, and colour coding conventions
