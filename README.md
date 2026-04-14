# Failure Modes in AI-Assisted Triage Decision-Making

## Overview
This project explores how AI systems perform in triage-style decision-making, with a focus on ambiguity, edge cases, and potential failure modes.

The goal is to better understand how AI behaves in high-stakes, real-world scenarios where incorrect prioritization can lead to harm.

## Motivation
My background in emergency medicine and patient care has involved frequent triage decisions under uncertainty. These environments require rapid risk assessment, prioritization, and handling incomplete or conflicting information.

This project applies those same principles to evaluating AI systems.

## Methodology
- Developed realistic triage scenarios based on real-world patterns:
  - Clear cases
  - Ambiguous cases
  - Edge cases
  - Misleading or incomplete inputs

- Queried a large language model to:
  - Assess urgency
  - Provide reasoning

- Analyzed outputs for:
  - Consistency
  - Risk awareness
  - Failure modes

## Key Findings
- Models perform well on clear, textbook cases
- Performance degrades in ambiguous scenarios
- Tendency toward overconfidence in uncertain situations
- Susceptibility to misleading or biased user input

## Failure Modes Identified
- Overconfidence under uncertainty
- Under-triage in edge cases
- Lack of clarification when inputs are incomplete
- Over-reliance on user framing

## Implications
These results suggest that AI systems used in high-stakes environments require:
- Structured input constraints
- Human-in-the-loop validation
- Better uncertainty handling
- Explicit safety guardrails

## Next Steps
- Expand scenario dataset
- Compare multiple models
- Develop improved prompting strategies
- Explore human-AI collaboration frameworks

## Author
Carolyn Lee-Gerstenberg
