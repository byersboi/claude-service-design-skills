# Prototyping Methods Comparison

Side-by-side comparison of service prototyping methods to help select the right approach.

---

## Quick Selection Guide

| Question | Recommended method |
|----------|-------------------|
| Is this a digital touchpoint or screen? | Paper prototyping, Figma/digital mockup |
| Is this a physical service or space? | Desktop walkthrough, role play, bodystorming |
| Is this a human interaction or conversation? | Role play / experience prototype |
| Do I need to simulate technology before building it? | Wizard of Oz |
| Do I want to communicate the concept to stakeholders? | Storyboard, service advertisement |
| Do I want to test the full service in real conditions? | Pilot |
| Am I early in Develop? | Low fidelity (paper, sketch, desktop walkthrough) |
| Am I late in Develop / early Deliver? | High fidelity (Wizard of Oz, pilot) |

---

## Methods Comparison Table

| Method | Fidelity | Build time | What you learn | Best phase | Real users needed? |
|--------|---------|-----------|----------------|-----------|-------------------|
| Paper prototype | Very low | 30 min – 2 hr | Comprehension, navigation, language | Early Develop | Yes — internal first, then real |
| Desktop walkthrough | Low | 1–3 hr | Service flow logic, handoffs, spatial | Early-mid Develop | No — team only |
| Role play | Low–medium | 1–4 hr | Emotional quality, staff scripts, interaction feel | Mid Develop | Yes — ideally real users |
| Storyboard | Low | 1–3 hr | Concept comprehension, narrative clarity | Early Develop | Yes — check understanding |
| Wizard of Oz | Medium | 1–3 days | Digital interaction behaviour, language, expectation | Mid-late Develop | Yes |
| Service advertisement / video | Low–medium | 4–8 hr | Value proposition comprehension | Early-mid Develop | Yes |
| Pilot | High | Weeks–months | Full service effectiveness, operational issues | Deliver | Yes — real conditions |

---

## Method Profiles

### Paper Prototyping

**Description:** Sketched representations of screens, letters, forms, or interfaces, used to simulate a digital or paper-based interaction.

**Build:** Print or draw each screen/step on separate sheets or cards. The facilitator acts as the "system" — swapping screens in response to user actions.

**Setup time:** 30 minutes – 2 hours depending on complexity.

**Session format:**
- Brief participant: "We're testing whether this design makes sense — not testing you"
- Give participant a task: "Can you [complete action using this design]?"
- Observe silently — note where they pause, hesitate, or click in the wrong place
- Ask aloud: "What do you expect to happen when you press that?" "What are you looking for?"

**Number of users:** 5 is sufficient to identify most usability issues (Nielsen's rule).

**What it will not test:** Emotional response to the full service; backend operations; edge cases.

---

### Desktop Walkthrough

**Description:** A tabletop simulation of a service using printed cards, sticky notes, and simple props to represent spaces, people, and artefacts.

**Build:** Print service environment maps, create small cards for each actor and artefact, use physical props to represent key touchpoints.

**Best for:** Services with significant spatial components (hospital, retail, branch network); multi-actor services where handoffs are critical; early service model exploration.

**Session format:**
- Set up the service environment on a table
- Walk through the scenario step by step, moving the actor cards and narrating
- Pause at each handoff or decision point to discuss
- Note where the flow breaks down logically

**Participants:** Internal team + operational stakeholders. Real users are less useful here — this is for testing logic, not experience.

---

### Role Play / Experience Prototyping

**Description:** Acting out service interactions — with team members, stakeholders, or real users playing the roles of customer and service staff.

**Variants:**

*Internal role play:* Team members play all roles. Used to explore the interaction space and stress-test the concept. Fast and low-cost.

*Staff role play:* Recruit the staff who would deliver the service. Test whether the scripts and processes feel right from their perspective.

*User role play:* Recruit real users to play the customer role, with a team member playing the service role. Highest validity for emotional and behavioural insights.

*Bodystorming:* Physically move through a space as the user would, noticing environmental and spatial factors that affect experience.

**Setup time:** 1–4 hours to design the scenario and brief participants.

**What to capture:**
- Where does the interaction feel awkward or forced?
- Where does the person playing the staff member not know what to say?
- What emotional reactions does the interaction produce?
- Where does the "customer" deviate from the intended script?

---

### Storyboard

**Description:** A sequence of illustrated panels (comic-book style) showing a user's journey through the service.

**Build:** 6–12 panels. Stick figures are fine. Each panel: scene setting, character action, dialogue/thought bubble, annotation.

**When to use:**
- Before role play, to communicate the concept clearly to participants
- As a standalone concept communication tool for stakeholders
- As a test artefact — show to users and ask them to narrate what they see

**Storyboard test format:**
- Show the storyboard to a user: "Can you tell me what's happening in this story?"
- Where they misinterpret, the concept needs clarification
- Ask: "Does this feel realistic? What would you expect to happen differently?"

---

### Wizard of Oz

**Description:** A human secretly plays the role of a system (chatbot, AI, algorithm) while a user believes they are interacting with technology.

**Classic applications:**
- Testing a chatbot: human reads messages and types responses in real time
- Testing a recommendation engine: human manually selects recommendations based on user profile
- Testing a smart form: human fills in fields based on user answers to voice input

**Setup time:** 1–3 days to build a realistic front-end interface.

**Running the session:**
- User sees only the interface (app, screen, etc.)
- "Wizard" operates behind the scenes — ideally in a separate room
- Communication channel between facilitator and wizard for timing
- Observe how the user interprets responses, what they type, what confuses them

**What it will not test:** System performance at scale; real-world latency; edge cases the wizard didn't anticipate.

---

### Pilot

**Description:** A live, bounded test of the full service in real conditions with real users.

**Pilot design principles:**
1. Define scope explicitly: which users, which geography, which channels, which time period
2. Set success criteria before launch: what numbers would confirm this is working?
3. Design measurement in: survey, observation, analytics, staff debrief
4. Plan the exit: how will you close the pilot and what happens to participants?
5. Identify risks and mitigations in advance

**Minimum viable pilot:**
- As small as possible to generate meaningful learning
- Real users in real context (not controlled laboratory conditions)
- Enough volume to distinguish signal from noise
- Enough time to observe stable behaviour (not just novelty effects)

**What a pilot tests that nothing else can:**
- How the service performs under real operational load
- How staff behaviour, scripts, and processes hold up in practice
- What edge cases emerge that prototyping never anticipated
- Whether improvements in experience translate into improvements in outcomes

---

## Fidelity Decision Framework

Ask:
1. **What is the key assumption to test?** Match fidelity to this — not to your comfort level.
2. **How much will it cost to be wrong later?** Higher later-stage cost → invest in higher fidelity now.
3. **How much time do we have?** Calibrate accordingly — lower fidelity is always faster.
4. **Who is the audience?** Internal team: low fidelity fine. Real users: needs to be convincing enough to elicit honest responses.

**Rule of thumb:** Build the minimum fidelity needed to answer the test question. Not the maximum fidelity you could justify.
