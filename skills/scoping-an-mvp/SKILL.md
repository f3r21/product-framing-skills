---
name: scoping-an-mvp
description: Scopes a minimum viable product and its Now/Next/Later roadmap, or reviews one, against Atlassian and ProdPad criteria. Use when the user asks whether an MVP is genuinely minimal, shares an in/out list or a roadmap, or asks which features to build first.
---

# Scoping an MVP

## Overview
The review covers the hypothesis and the roadmap the user shared, nothing else in their
document.

Every criterion comes from the five sources tagged in the table at the end. Cite only these.
If a point is not covered by them, say so instead of supplying one.

## Template
Fill the user's template when they supply one. Otherwise: In, Out, Why, then Now / Next / Later.
Each field is held by a criterion below.

## Criteria

| # | Criterion | What to look for | Source |
|---|---|---|---|
| 1 | Pain first | The slice answers "First ask yourself: What problem are you trying to solve?" Red flag: a reason that argues from competitors or from looking finished | [AT] step 1 |
| 2 | Core only | "only the core features necessary to satisfy early adopters and validate a product idea"; "the few features you identified from the start". Red flag: every candidate kept as a simpler version. A slice drops candidates, not detail: UberCab was "a version based entirely within SMS", Amazon "a bookstore as the minimum viable product" | [AT] |
| 3 | Least effort | "the least amount of effort put into it … in order to test, collect feedback, and learn". A landing page, an SMS line or stapled paper counts: the Handy Guide "started out as pieces of scrap paper stapled together", tested by showing "the actual papers to people in my product circle"; "Experimentation starts long before any developer is involved" | [HG]; [AT] step 3 |
| 4 | Still viable | Each item in the slice still works for a real user: "MVPs are tested with real users". Red flag: a feature shrunk until it does nothing, a reminder that alerts nobody, a shared list with one user | [AT] FAQ |
| 5 | Learning goal | What launching will teach: "every idea you have is a hypothesis", so "you build the bare minimum of your hypothesis in order to validate it"; who tests it, "a beta group or internal testers"; and the "build-measure-learn (BML) feedback loop" after. Red flag: "we will polish after launch" with nothing to measure | [HG]; [AT] steps 3–4 |
| 6 | Out is specific, with a reason | "list what's out of scope … Be as specific as possible"; "Flag things that are out of scope at the moment, but might be considered at a later time". Red flag: nothing out, or a list with no reasons | [CF]; [PR] |
| 7 | Columns by confidence | Now: "validated Initiatives … where the problem is well understood and the focus has shifted to the solution". Next: "the big bets from Later are broken down into smaller problems". Later: "strategic problem areas the team cares about but has not yet shaped into something workable" | [NNL] |
| 8 | No dates | "organizes work by levels of confidence instead of fixed dates". Red flags: "Treating the columns as Q1, Q2, Q3"; "Putting artificial dates on the cards" | [NNL] |
| 9 | Now is short and matches the slice | "A long Now column is a sign of weak prioritization. Now should hold what the team can realistically focus on". Red flag: the slice and the Now column name different items | [NNL] |
| 10 | Every entry traces | Each entry is one of the candidates and names the problem it serves: "Entries should describe the outcome you want, not the solution you have assumed". Red flag: an item that appears for the first time in Later | [NNL] |
| 11 | Competitive landscape | "What will make your service stand out? What are customers still missing out on?" Optional: ✅ or —, never ❌ | [AT] step 2 |

## Output

**Build**, when the user gives a candidate feature list and asks for a hypothesis:

1. One line answering the question the user asked, then what is known: the problem, the
   persona's pains and the metric the product should move. If the request has them, use them.
   If one is missing, ask for it and stop; three lines is enough.
2. The hypothesis in the template, as plain text the user can paste unchanged: one line per item,
   `item: the pain it serves` for In and `item: the reason` for Out, at most twenty words each;
   the Why in two sentences, the problem solved first and what launching will teach.
3. Now / Next / Later, one line per item as `item: the problem it serves`, no dates. Now names
   the In items and nothing else.
4. One closing line offering the review table, and nothing after the roadmap but that line.

**Review**, when the user shares an MVP hypothesis or a roadmap:

1. One line answering the question the user asked, then a table: one row per criterion, marked
   ✅ / ⚠️ / ❌, each with a one-line reason that quotes the user's own words.
2. Up to three questions that would move the hypothesis forward: what problem is solved first,
   what launching will teach, what evidence would move an item between columns.
3. One closing line offering a rewrite. The rewrite itself waits for the user to ask.

## Sources

| Tag | Citation |
|---|---|
| [AT] | Max Rehkopf, "What is a Minimum Viable Product (MVP)? How to Get Started", Atlassian Agile Coach, undated. https://www.atlassian.com/agile/product-management/minimum-viable-product |
| [HG] | Janna Bastow, "Minimum Viable Product (MVP) Experiment – The Handy Guide Example", ProdPad, 1 March 2022. https://www.prodpad.com/blog/minimum-viable-product-mvp-example/ |
| [NNL] | Janna Bastow, "Now-Next-Later Roadmap", ProdPad glossary, updated 29 June 2026. https://www.prodpad.com/glossary/now-next-later-roadmap/ |
| [CF] | "Product requirements document (PRD) template", Atlassian Confluence templates, undated. https://www.atlassian.com/software/confluence/templates/product-requirements |
| [PR] | Dan Radigan, "What is a Product Requirements Document (PRD)?", Atlassian Agile Coach, undated. https://www.atlassian.com/agile/product-management/requirements |
