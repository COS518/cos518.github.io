---
layout: base
---

## Overview

The semester-long project in COS518 is an systems-building
project.  Projects should be done in groups (either of size two or
three, *to be determined* by the instructor after the course size
finalized) and must involve significant system programming. All group
students are expected to share equally in the implementation.

There is a significant departure this year in the scope of the project
compared to previous versions of COS518.  In particular, we expect
most students to satisfy the group project by **reimplementing and
reproducing** the results from a paper we read during the semester or
on a like topic.

As in previous years, students are also able to satisfy the project by
performing novel research projects, but such projects must be
closely related to the material and topics taught in the COS518
curricula.  The instructors will take a ***narrow*** view as to what
projects satisfy this criteria (e.g., your ongoing research on
self-driving cars or software-defined networks will likely not be
approved).

Students uncertain as to the satisfiability of their project are urged
to speak to instructors as soon as possible, as the initial timeline
for project selection is aggressive.

## Timeline
- Team selection (2/9)
- Project proposal (2/26)
- Project selection (3/9):  Project topic/proposal finalized
- Interim project presentation (3/28)
- Project presentation (5/14)
- Final report (Dean's Date of 5/15)
<br><br>

## Assignments

### Project Proposal

There are two types of projects in this class: reproducing others'
research results, and novel research.  Proposals should be submitted
via a private note to Instructors on Piazza.

#### Project Proposal:  Reproducing Research

For **reproducing research** projects, students should write a note to
the instructors with a few paragraphs that include the following
information.  Please tag these proposals as #proposal #reproduction.

- Background
   - Name of paper
   - Brief summary of paper's problem domain / challenge, goals, and technical approach
   - Summary of paper's current implementation, evaluation strategy, and key results

- Plan:
   - Proposed implementation (language, framework, etc.)
   - Evaluation strategy (testing platform/setup, simulated data/traces, etc.)
   - Key results trying to reproduce
   - Discussion of how you can compare your findings (quantitatively, qualitatively) with previously published results
   - New questions/settings trying to evaluate that are not addressed in the original paper

As the final plan mentions, it is important when reading a paper to ask what
questions and/or settings are *not* included in an evaluation.  For example,
what happens if a workload shifts from being uniformly distributed to
Zipfian?  What if failures occur in a different fashion than evaluated?  What
if the data in a big data processing system has a different structure than
evaluated (e.g., the "graph" that the data represents has a different edge
distribution)?  And so forth...

#### Project Proposal:  Novel Research

For **novel research** projects, students should write a note to the
instructors with a few paragraphs that include the following
information.  Please tag these proposals as #proposal #novel.

- Background
   - What problem is research attempting to solve?
   - Why is the problem important?
   - How does this relate directly to topics or papers covered in class

- Novelty
   - What is the current state-of-the-art in related work, and why are they insufficient?
   - What is your (novel) technical insight/approach to solving this problem

- Plan
   - Proposed implementation (language, framework, etc.)
   - Key questions that evaluation will address
   - Evaluation strategy (testing platform/setup, simulated data/traces, etc.)
   - What does "success" look like?  How do you quantify/compare results to alternative approaches / related work?

If students are concerned that their proposal project might not be
sufficiently relevant to COS 518 to satisfy the topical criteria,
please contact instructors earlier than later.  Proposals not closely
related to the topical matter may be rejected outright as not
appropriate.

### Project selection

The project proposal from above will be finalized.  This may involve
one or more back-and-forth between instructors and group (likely via
Piazza).

### Presentation

More information forthcoming.

### Final report

Rather than a research paper written as a Latex document, your final
report will be a blog post that expands on a similar organization and
topics as addressed in your initial project proposal.

For reproduction projects, the post should have a particular focus and
discussion on the evaluation (setup, comparative results, discussion
of differences, and so forth).

Your final report must be published on a public forum like Medium as part of
a course page, to be  determined soon by the instructors.  Source code and
data should also be made available.
