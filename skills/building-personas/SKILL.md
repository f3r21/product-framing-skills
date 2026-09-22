---
name: building-personas
description: Builds or reviews a product persona against Product School and Mind the Product criteria. Use when the user shares a problem statement and asks for a persona, shares a persona for review, or asks whether a persona is generic, invented or missing its job to be done.
---

# Building personas

## Overview
Hold a persona to the criteria below: build one from a problem statement, or review one the
user brings.

Every criterion comes from the three sources tagged in the table at the end. Cite only these.
If a point is not covered by them, say so instead of supplying one. None of them fixes a field
list: [PS] says "there's also no exact list of what you should include".

## Template
Fill the user's template when they supply one. Otherwise: Snapshot (name and a one-line
situation), Context, Goals (one or two), Pains, Current workaround, The job ("When [situation],
I want to [motivation], so I can [expected outcome]" [MTP]), In their words. Each field is held
by a criterion below.

## Criteria

| # | Criterion | What to look for | Source |
|---|---|---|---|
| 1 | One person | A story about someone the team could know. Red flag: a segment label plus an adjective, which fits anyone | [PS] Relatable, Well-structured |
| 2 | Complete | Every field of the template filled; goals as "their desired outcome", the quote in "recurring language or phrases they use" | [MTP] |
| 3 | Context is a moment | When and where it happens, on what device, how often, the use habits "frequency, session duration"; "the moment you realize you have to do something different" | [PS]; [MTP] |
| 4 | Every detail earns its place | "Put only those details relevant enough for your team to design and build features". Red flag: hobbies, favorite brands, leaders they follow, with no consequence for the product | [PS] Concise |
| 5 | Pains tied to the problem | One to three, ordered by importance and frequency, each one a push to look for something else | [PSG]; [MTP] |
| 6 | Workaround named | What they do today instead: "the status quo or alternative solutions" are the real competition | [MTP] |
| 7 | The job is progress, not a feature | Job story format. Red flag: the motivation names a solution | [MTP] |
| 8 | Emotional or social dimension | In the pains or the quote: people "also hire them to feel a certain way or to project a certain identity" | [MTP] |
| 9 | Evidence | ✅ anchored in an interview, a survey or a real person the user named. ⚠️ when nothing says where it came from: "sketch out what you think you know about your customers, and then test your hypotheses later". ❌ only when it claims an interview, a survey or data it does not show | [PS] |

## Output

**Build**, when the user gives a problem statement and asks for a persona:

1. What is real: an interview, a survey, a person they know who went through this, or nothing
   yet. If the request says, use it. If it says nothing about that, ask that one question and
   stop; three lines is enough.
2. The persona in the template, its seven labels in place from `Snapshot:` to `In their words:`,
   as plain text the user can paste unchanged: one sentence per field, one per goal and per pain,
   at most fifteen words each and thirty for the job story's three parts, under 150 words in all.
3. `Assumed, validate with:` the list that carries the assumptions, at most five lines, the ones
   that would change the product if wrong, each with the probing question that confirms or
   kills it. [MTP]'s shape: "Take me back to when you first started looking for a solution like
   this. What was going on in your work or life at that time?"
4. One closing line offering the review table.

**Review**, when the user shares a persona:

1. A table: one row per criterion, marked ✅ / ⚠️ / ❌, each with a one-line reason that quotes
   the user's own words.
2. Up to three probing questions [MTP]: what was happening in their life that led them to look,
   what alternatives they considered, how they wanted to feel.
3. One closing line offering a rebuild. The rebuild itself waits for the user to ask.

## Reference examples

- Job as solution [MTP]: "ordering meals online". Job as progress: "feeding my family healthy
  meals without the hassle of cooking".
- One persona per user group [PS]: Airbnb's digital nomads, business travellers, couples and
  families are four personas, not one.

## Sources

| Tag | Citation |
|---|---|
| [PS] | Carlos Gonzalez de Villaumbrosia, "How to Create Product Personas + Examples", Product School, 22 May 2024, updated 28 May 2024. https://productschool.com/blog/user-experience/product-persona |
| [MTP] | Mike Belsito, "Jobs to be done for Product Managers", Mind the Product, 29 January 2025. https://www.mindtheproduct.com/jobs-to-be-done-for-product-managers/ |
| [PSG] | "Jobs-To-Be-Done", Product School glossary, undated. https://productschool.com/resources/glossary/jobs-to-be-done |
