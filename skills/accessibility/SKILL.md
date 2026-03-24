---
name: Accessibility
description: This skill should be used when the user asks about "accessibility", "accessible design", "WCAG", "web content accessibility guidelines", "accessibility statement", "EU Accessibility Directive", "Public Sector Bodies Accessibility Regulations", "POUR principles", "perceivable operable understandable robust", "inclusive design", "designing for disabilities", "access needs", "assistive technology", "screen reader", "accessibility audit", "accessibility testing", "disproportionate burden", "accessibility compliance", or needs to understand how to design services that are usable by everyone regardless of their abilities or circumstances.
version: 1.0.0
---

# Accessibility

Accessibility means designing services so that everyone can use them — including people with disabilities, people using assistive technology, and people with low digital literacy, limited English, or other barriers to access.

In the UK and across the EU, accessibility is not optional for public sector services: it is a legal requirement. But the more important framing for service designers is that accessibility is a design quality. If a service cannot be used by the people who need it most, it is not a good service.

---

## The Legal Framework

### The EU Accessibility Directive and UK Regulations

The EU Web Accessibility Directive (Directive 2016/2102) requires public sector bodies to make their websites and mobile apps accessible. In the UK this was transposed as the **Public Sector Bodies (Websites and Mobile Applications) Accessibility Regulations 2018**.

**What public sector bodies must do:**
- Evaluate the accessibility of their websites and apps
- Fix accessibility issues — unless a fix would be a disproportionate burden, or the content is exempt
- Publish an accessibility statement

**Key timeline (from the regulations):**
| Scope | Compliance deadline |
|-------|-------------------|
| Regulations in force | 23 September 2018 |
| New websites | 23 September 2019 |
| Existing websites | 23 September 2020 |
| Mobile apps | 23 June 2021 |

**Monitoring and enforcement:** The Cabinet Office (in the UK) monitors compliance and can take enforcement action against public sector bodies that do not meet the requirements.

### WCAG: The Technical Standard

The Web Content Accessibility Guidelines (WCAG) set out the technical requirements services must meet. The current minimum for public sector services in the UK is **WCAG 2.1 Level AA**.

WCAG is organised around four principles — a service must be:

| Principle | Meaning |
|-----------|---------|
| **Perceivable** | Information must be presentable in ways all users can perceive — e.g. text alternatives for images, captions for video |
| **Operable** | Users must be able to operate the interface — e.g. keyboard navigation, no content that causes seizures |
| **Understandable** | Information and operation must be understandable — e.g. readable language, consistent navigation, error identification |
| **Robust** | Content must be robust enough to be interpreted by a wide range of user agents, including assistive technologies |

These four principles are often abbreviated as **POUR**.

---

## Accessibility Statements

Public sector bodies must publish an accessibility statement for every website and mobile app. The statement must:
- Describe the accessibility of the service
- List known accessibility issues and their impact
- Explain any exemptions claimed (disproportionate burden, exempt content)
- Provide contact details for users to report accessibility issues
- Link to the enforcement procedure if the response is unsatisfactory

### What Users Actually Need From Accessibility Statements

GDS research in 2018 into how users interact with accessibility statements produced five key findings:

**Finding 1: Users had never, or rarely, used an accessibility statement.**
Most users do not seek out the statement proactively. They find it when something has gone wrong — when they are struggling to use the service and are looking for help or alternatives.

*Design implication:* Write the statement for someone in difficulty, not for someone browsing documentation.

**Finding 2: Users expected to find information about accessible services.**
Users came to the statement hoping to find out what accessible routes were available to them — not a technical audit of WCAG compliance.

*Design implication:* Lead with what the user can do. Tell them what accessible alternatives exist: phone number, in-person option, accessible format.

**Finding 3: Users need to know what they can do, not what they can't do.**
Users found statements organised around failures and limitations discouraging and unhelpful. They wanted to know the path forward.

*Design implication:* Structure the statement around enabling action, not cataloguing problems.

**Finding 4: Users were offended by negative language that made them feel like a burden.**
Language like "we are unable to provide..." or framing accessibility as a limitation created a sense that the user's needs were an inconvenience.

*Design implication:* Use positive, active language. Avoid framing accessibility as deviation from the norm.

**Finding 5: Users do not think accessibility statements are for them if the language is technical and complex.**
WCAG-level technical language (referring to criteria numbers, success criteria, conformance levels) meant most users could not understand what the statement was telling them.

*Design implication:* Write in plain English. A WCAG 2.1 criterion number is meaningless to a user — describe the actual problem and its impact on real use.

---

## Accessibility Guidance for Service Teams

GDS research with public sector digital managers — the people responsible for making services compliant — produced a parallel set of findings about what guidance needs to do:

**Finding 1: Teams need practical information on what is required and how it will affect their work.**
Abstract principles do not help teams make decisions. Teams need to know: what do I actually have to do, by when, and who is responsible?

**Finding 2: Teams expected practical support from GDS, including specific tool or third-party recommendations.**
Knowing a requirement exists is not enough. Teams need to know how to test for it, what tools to use, and where to find qualified help.

**Finding 3: Teams need to know which areas of accessibility to prioritise, to make use of limited time and resources.**
Most teams do not have unlimited capacity to fix every accessibility issue immediately. Guidance needs to help teams prioritise by impact — which issues cause the most harm to users with the most significant barriers.

**Finding 4: Teams struggled with the clarity of requirements — some did not realise that compliance was mandatory.**
The language of regulation can obscure the difference between requirements, best practice, and principles. Guidance must make clear what is a legal requirement and what is recommended.

**Finding 5: Teams expected working examples of best practice.**
Abstract guidance is harder to apply than concrete examples. Show what a well-written accessibility statement looks like, what good colour contrast looks like in practice, what a properly labelled form looks like.

---

## Accessibility in the Design Process

Accessibility is easier and cheaper to build in from the start than to retrofit. It should be part of every phase of the design process, not a compliance check at the end.

### In Discovery
- Recruit participants with access needs for user research
- Include assistive technology users (screen reader, switch access, voice control)
- Research the range of circumstances in which the service will be used: low bandwidth, shared devices, public terminals, mobile-only users

### In Define and Develop
- Use the GOV.UK Design System and GOVUK Frontend components — they are built to meet WCAG 2.1 AA
- Test with keyboard-only navigation from the start
- Write content in plain English — this is a WCAG requirement (readable language) as well as a content design principle
- Use sufficient colour contrast — minimum 4.5:1 for normal text, 3:1 for large text
- Provide text alternatives for non-text content (images, icons, charts)
- Design error messages that identify the problem and tell the user how to fix it

### In Deliver
- Conduct an accessibility audit before launch — either using automated tools as a first pass, followed by manual testing, or commissioning a specialist audit
- Test with real assistive technology users, not just automated tools (automated tools catch approximately 30–40% of WCAG issues)
- Publish an accessibility statement
- Establish a process for receiving and acting on accessibility issue reports

---

## Common Accessibility Issues in Government Services

**Forms:**
- Missing or unclear labels on form fields
- Error messages that identify the field but not the problem
- Timeout warnings not given in advance, or with insufficient time to respond

**PDFs:**
- Untagged PDFs that cannot be read by screen readers
- Documents not available in accessible HTML format
- PDFs used where HTML would be more appropriate

**Navigation:**
- No way to skip repeated navigation to reach main content
- Focus order that does not follow visual layout
- Interactive elements that cannot be reached by keyboard

**Content:**
- Images without meaningful alternative text
- Tables without proper header markup
- Video without captions or audio description

**Colour and contrast:**
- Insufficient contrast between text and background
- Colour used as the only way to convey information (e.g. error states indicated only by red)

---

## Making Accessibility Research and Consultation Accessible

When conducting research or consultation about accessibility, practice what you preach. GDS's approach to consulting on the accessibility regulations included:

- Involving a content designer in drafting consultation materials
- Publishing consultation documents in HTML (not PDF-only)
- Using an accessible online survey tool
- Providing content in British Sign Language (BSL) and Easy Read formats
- Running engagement events specifically with disability organisations and local authority digital managers

This is relevant beyond accessibility work: any research or consultation that is not itself accessible will systematically exclude the people with the highest stake in getting accessible design right.

---

## The Case for Accessibility

The legal case is clear. The practical case is also strong:

**Scale:** Approximately 1 in 5 people in the UK have a disability. Government services are for everyone — there is no valid reason to design out 20% of potential users.

**Overlap:** Accessibility improvements benefit far more people than those with permanent disabilities. Temporary impairments (a broken arm, post-surgery recovery), situational limitations (bright sunlight, a noisy environment, a small screen), and ageing all create accessibility needs. Accessible design is often just good design.

**Support cost:** Services that cannot be used independently by people with access needs generate support contacts — phone calls, in-person visits, complaints. Accessible digital services reduce this cost.

**Trust:** A service that does not work for part of its user base signals to those users that they are an afterthought. For public services, this erodes trust in government more broadly.

---

## Level Guidance

**Junior:** Learn WCAG 2.1 AA as a checklist, and know how to test against it. Run the service through an automated checker (Axe, Wave). Test every screen with keyboard-only navigation. Read every image alt text aloud and ask: does that tell someone what's in the image if they can't see it?

**Mid-weight:** Push accessibility into the design process rather than treating it as a post-build audit. Build testing with assistive technology users into research plans. Challenge the use of PDFs, complex tables, and heavy use of colour to convey meaning. Write accessibility considerations into design rationale and critique documents.

**Senior / Lead:** Make the organisational and procurement case. Accessibility audits are cheaper than retrofitting failed audits. Build accessibility requirements into supplier contracts and assurance processes. Ensure accessibility statements are maintained and acted on — an out-of-date statement with a backlog of unaddressed issues is a legal and reputational risk. Advocate for disability-inclusive hiring in research and design teams.

---

## Additional Resources

- **WCAG 2.1:** w3.org/TR/WCAG21 — the full technical standard
- **GDS Accessibility guidance:** gov.uk/guidance/accessibility-requirements-for-public-sector-websites-and-apps
- **GOV.UK Design System accessibility:** design-system.service.gov.uk/accessibility
- **Accessibility statement template:** gov.uk/government/publications/sample-accessibility-statement
- **`skills/service-standards/SKILL.md`** — Principle 11 (usable by everyone equally) from Lou Downe's 15 Principles, and GDS Standard criterion 5 (make sure everyone can use the service)
- **`skills/user-research/SKILL.md`** — recruiting and including participants with access needs in research
