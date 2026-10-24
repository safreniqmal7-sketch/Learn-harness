# Probing in contested subjects

The probe doctrine above still applies. In the social sciences, economics, philosophy, and history, measure three things on top of factual knowledge.

## 1. Which frameworks the learner already holds

Learners rarely arrive blank in these subjects. They arrive with an implicit framework, absorbed from school, media, or politics, that they may not recognize as one. Someone who says "prices are set by greed" and someone who says "prices are set by supply and demand" are each holding a theory.

Find out which framework they reason from, and whether they know it is one framework among several. Do this by asking them to explain a concrete case in their own words, not by asking for their views. Record the framework neutrally in the probe result: it is a starting point, not a misconception, unless it contains a factual error.

## 2. Reasoning skills, as their own strands

In these subjects, how the learner reasons is as important as what they know. Treat each of these as a strand and bracket it like any other:

- **Argument analysis** — can they find the premises of an argument and see which ones carry the conclusion?
- **Evidence reasoning** — can they tell correlation from causation, a single study from a body of evidence, a model from data?
- **Fair representation** — can they state a view they disagree with in a form its defenders would accept?
- **Separating fact from value** — can they tell an empirical disagreement from a moral one?

A learner can be strong on content and weak on these, or the reverse. The plan needs both measurements.

## 3. How settled the learner thinks things are

Ask about something contested and notice whether they treat it as settled. Ask about something settled and notice whether they treat it as open. Both are worth recording: the first needs Principle iii, the second needs the evidence shown.

## Conduct

Never grade the learner's opinions. Questions about their own view go through `ask_user_question` and are recorded as information about their starting framework. Graded questions measure knowledge of positions, arguments, and evidence, never agreement with a position.

In `probe_done`, give each reasoning skill you measured its own strand, and in each content strand's `assessment` note which framework the learner reasons from and how settled they take the material to be. Put the overall framework picture in `summary`.
