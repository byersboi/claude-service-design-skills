---
name: Content Design
description: This skill should be used when the user asks about "content design", "writing for services", "service content", "plain English", "GDS style guide", "GOV.UK style", "content designer", "writing for users", "service language", "form question design", "error messages", "transaction content", "labelling", "content patterns", "words to avoid", "active voice", "readability", "content critique", "content review", "writing a discussion guide", "prototype content", "realistic content", "content accessibility", "inclusive language", "writing headings", "call to action", "button labels", "confirmation pages", or needs help writing, reviewing, or designing the words that form part of a service.
version: 1.0.0
---

# Content Design

Content design is the practice of designing the words, structure, and flow of information that form part of a service. It is a design discipline — not copywriting, not communications, not technical writing.

The distinction matters. A copywriter asks: "How do we say this well?" A content designer asks: "Does this need to be said at all? And if so, what is the clearest possible way to say it for this specific person at this specific moment?"

In the UK, content design practice is heavily shaped by the Government Digital Service (GDS), whose style guide and design principles set the standard across public sector digital services — and have influenced wider practice beyond government.

---

## Content Design vs. Writing

| Writing | Content Design |
|---------|---------------|
| Produces text to be read | Designs an experience through language |
| Starts with what needs to be said | Starts with what the user needs to know or do |
| Measures quality by craft | Measures quality by user outcomes |
| Finished when published | Iterated based on user behaviour and feedback |
| Written in isolation | Done in collaboration with UX, research, and product |

---

## Core Principles

### 1. Start with user needs, not organisational needs

The most common content failure is writing for the organisation's perspective rather than the user's. Ask:
- What does the user need to know at this point?
- What do they need to do next?
- What language do they use for this?

Not:
- What does the organisation need to communicate?
- What is the legal requirement to state?
- What does policy say must be included?

### 2. Plain English is a design decision

Plain English is not dumbing down — it is designing for cognitive load. Every unnecessary word, every piece of jargon, every passive construction adds friction to what should be a seamless interaction.

**The Flesch reading ease test** is a useful gut check — aim for a score that suits your audience, but generally 60–70 (plain English) is appropriate for most service content. Government service content typically targets reading age 9.

### 3. Active voice over passive

Passive voice obscures agency and adds words. Active voice is clearer and shorter.

| Passive | Active |
|---------|--------|
| "Your application will be reviewed by our team." | "We'll review your application." |
| "Mistakes can be made during the process." | "You might make mistakes during the process." |
| "The form must be submitted before the deadline." | "Submit the form before the deadline." |

### 4. Front-load the important information

Users scan before they read. Put the most important information first — at the top of the page, at the start of the sentence, at the beginning of the bullet point.

This is sometimes called the **inverted pyramid** from journalism: start with the conclusion, then add detail.

### 5. Write for the worst-case reader

Design content for the user who:
- Is stressed or anxious about the outcome
- Is reading on a mobile device with poor signal
- Does not have English as a first language
- Has low literacy or cognitive load
- Is encountering this service for the first time

If it works for them, it works for everyone.

---

## GDS Style Guide: Key Rules

The [GOV.UK style guide](https://www.gov.uk/guidance/style-guide/a-to-z) is the definitive reference for UK public sector content. Its principles are widely adopted beyond government.

### Sentence case everywhere

Use sentence case for headings, labels, and buttons — not title case.

✓ "Apply for a blue badge"
✗ "Apply For A Blue Badge"

Exceptions: proper nouns, official names, acronyms.

### Contractions

Avoid complex contractions (should've, could've). Use full words. Simple contractions (don't, can't, you'll) are acceptable in conversational contexts but the GDS guide recommends using full forms (do not, cannot, you will) for clarity.

### Abbreviations and acronyms

Always spell out on first use, then use the abbreviation.

> "You'll need a National Insurance number (NI number). Your NI number is on your payslip."

Widely known abbreviations (NHS, UK, VAT, GP) do not need spelling out.

### Numbers

- Write one to nine as words; use numerals for 10 and above
- Use numerals in: lists, instructions, measurements, ages, percentages, money
- Use % not "per cent" (except at the start of a sentence)
- Use £ with no decimals unless pence are needed: £75, not £75.00

### Dates and times

- "4 June 2017" (no comma, no ordinal — not "4th June")
- "Monday to Friday, 9am to 5pm"
- Use "to" in ranges, not hyphens or dashes
- "Midnight" and "midday", not 00:00 or 12 noon

### Bullet points

- Always use a lead-in sentence ending with a colon
- Start each bullet with a lowercase letter (unless it begins with a proper noun)
- No semicolons between bullets
- No full stop after the final bullet
- One idea per bullet; maximum one sentence per bullet

### Links

- Front-load with the meaningful word: "read the [guidance on expenses](link)" not "click [here](link) for guidance on expenses"
- Never use "click here" or "find out more" as link text — it is meaningless out of context and inaccessible

---

## Words to Avoid

The GDS style guide maintains a list of words that should be replaced with plain alternatives. These appear frequently in government and corporate writing.

| Avoid | Use instead |
|-------|-------------|
| Deliver (metaphorical) | Create, make, provide |
| Empower | Allow, let, give permission to |
| Facilitate | Run, help, support (be specific) |
| Going forward | From now on, in future |
| Innovative | (describe what makes it new, specifically) |
| Key (as adjective) | (omit or be specific) |
| Leverage | Use |
| Prioritise | (say what you will do first and why) |
| Ring-fence | Keep, protect, set aside |
| Robust | (describe what makes it strong, specifically) |
| Streamline | (describe the improvement specifically) |
| Tackle | Deal with, address, solve, stop |
| Transform | Change, improve (be specific) |
| Utilise | Use |
| Stakeholders | (name them: users, staff, managers) |
| Learnings | Learning, lessons, findings |

**The test**: if you cannot say it in conversation without sounding strange, rewrite it.

---

## Designing Form Questions

Form questions are one of the most important content design challenges in service design. A badly worded question creates errors, confusion, and calls to the helpline.

### Principles for form questions

**Ask only what you need.** Every field has a cost — to the user's time, attention, and trust. Before adding a field, ask: "What decision does this enable? What happens if we don't ask?" If you cannot answer clearly, cut it.

**One thing per question.** Never combine two questions into one field or label.

✗ "Name and job title"
✓ "Full name" (separate field) + "Job title" (separate field)

**Use the user's language, not yours.** Test what users actually call the thing you are asking about. "National Insurance number" vs "NI number" vs "NINO" — which does your user population use and recognise?

**Frame questions from the user's perspective.** Questions should be from the user's point of view, not the system's.

✗ "Claimant date of birth"
✓ "What is your date of birth?"

**Provide hint text where needed.** Hint text appears below the label and clarifies format, purpose, or scope. Keep it brief — one sentence maximum. Do not use hint text to explain a poorly-designed question: fix the question instead.

**Error messages must be specific and helpful.** A good error message tells the user exactly what went wrong and exactly what to do.

✗ "Invalid input"
✓ "Enter your date of birth in DD MM YYYY format, for example 15 03 1985"

---

## Transactional Content Patterns

Transactional services (apply, register, book, pay, report) follow predictable content patterns. Knowing these patterns speeds up design and ensures consistency.

### Start page
- What the service does (one sentence)
- Who can use it
- What the user needs before they start
- How long it takes
- Call to action: "Start now"

### Question pages
- One question per page
- Label + hint text (if needed)
- No body copy unless genuinely necessary for the user to answer the question

### Check your answers page
- Summary of all answers
- Each item editable
- Clear call to action for submission

### Confirmation page
- What happened ("We've received your application")
- What happens next (specific, with timeframes if known)
- Reference number (if applicable)
- What to do if something goes wrong

### Error pages
- Explain what went wrong
- Tell the user what to do
- Do not blame the user

---

## Content for Prototypes

Realistic content makes prototypes dramatically more testable. Lorem ipsum content forces participants to imagine the real service — which they cannot do accurately.

**Principles for prototype content:**

- Use realistic data — real-looking names, addresses, dates, reference numbers
- Write at the intended reading level — not placeholder text, not "insert content here"
- Include realistic error states — many usability issues only appear when something goes wrong
- Write the confirmation page — this is often the most important moment in the journey and is frequently omitted from early prototypes
- Test the content, not just the interaction — note what language confuses participants; content failures are as important as UX failures

---

## Inclusive Language

**Disability:**
- "Disabled people" not "the disabled" or "people with disabilities" (check with your specific audience — some communities have preferences)
- "Wheelchair user" not "wheelchair-bound"
- "D/deaf" for hard of hearing communities (capital D for those who identify with Deaf culture)
- Avoid implying that disability is inherently a problem to be solved

**Gender:**
- Use "they/them/their" as a singular pronoun when gender is unknown
- Avoid gendered job titles: "chair" not "chairman", "firefighter" not "fireman"
- Do not assume gender from names

**Age:**
- "Older people" not "the elderly" or "seniors"
- "Young people" not "youths"

**Ethnicity:**
- Follow the preferences of the communities being described — these evolve and vary
- Use specific terms when precision matters (e.g., "South Asian" is often more accurate than "Asian")
- Capitalise: Black, White, Asian, Mixed — when referring to ethnic identity

---

## Content Review Checklist

Use this when reviewing service content — your own or someone else's.

**Purpose and necessity**
- [ ] Does every piece of content serve a user need?
- [ ] Is anything present only for organisational reasons?
- [ ] Can anything be cut?

**Clarity**
- [ ] Is it written in plain English?
- [ ] Are all technical terms or jargon explained or removed?
- [ ] Are sentences under 25 words?
- [ ] Is active voice used throughout?

**Structure**
- [ ] Is the most important information first?
- [ ] Do headings accurately describe the content below them?
- [ ] Are bullet point lists used correctly (lead-in, consistent, no semicolons)?

**Form questions (if applicable)**
- [ ] One question per field?
- [ ] Written from the user's perspective?
- [ ] Error messages specific and helpful?
- [ ] Hint text concise and necessary?

**Tone and language**
- [ ] Does it use the user's own language?
- [ ] Are GDS words-to-avoid used?
- [ ] Is it inclusive?
- [ ] Does it avoid blaming the user?

**Accessibility**
- [ ] Is link text meaningful out of context?
- [ ] Are abbreviations expanded on first use?
- [ ] Are numbers formatted correctly?

---

## Level Guidance

**Junior:** Focus on the basics — active voice, plain English, cutting unnecessary words. Read the GDS style guide A to Z once. When in doubt about a word or phrase, ask: "Would I say this out loud to a real person?" If the answer is no, rewrite it.

**Mid-weight:** Focus on question design and transactional patterns. Most content problems in services live in forms — the label is confusing, the hint text is wrong, the error messages don't help. Develop a systematic approach to reviewing and testing form content.

**Senior / Lead:** Focus on content strategy across the service. Ensure content design is involved from the start of discovery — not brought in at the end to "write the screens." Advocate for content patterns, shared language, and a single content standard across a programme. Treat content decisions as design decisions with the same rigour as interaction design.

---

## Additional Resources

- **GOV.UK Style Guide:** gov.uk/guidance/style-guide/a-to-z
- **GDS Content Design guidance:** gov.uk/guidance/content-design
- **`references/content-patterns.md`** — Common transactional content patterns with annotated examples
- **`references/form-question-bank.md`** — Tested question and label wording for common service contexts
