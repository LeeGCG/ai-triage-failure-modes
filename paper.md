# Failure Modes in AI-Assisted Triage Decision-Making Under Ambiguity

## Abstract

Large language models (LLMs) are increasingly used in high-stakes decision-support contexts, including healthcare-related applications. However, their behavior under ambiguous or incomplete input remains insufficiently characterized in real-world, safety-relevant settings.

This study evaluates the performance of an LLM in structured triage scenarios of varying clarity. We identify recurring failure modes, including overconfidence under uncertainty, under-triage of high-risk cases, and sensitivity to user framing. The results highlight limitations in reliability when models are deployed in ambiguous, real-world decision environments.

## 1. Introduction

Triage in emergency medicine requires rapid prioritization of patient risk under conditions of uncertainty. Decisions must often be made with incomplete, conflicting, or ambiguous information.

As LLMs are increasingly considered for decision-support roles, understanding how they behave in such environments is critical for safety, reliability, and responsible deployment.

This project investigates how an LLM responds to structured triage scenarios with varying levels of clarity, with a focus on identifying systematic failure modes.

## 2. Methodology

### 2.1 Scenario Design

Five categories of scenarios were constructed:

- Clear emergency presentation
- Moderate ambiguity cases
- High-risk edge cases
- Misleading patient framing
- Incomplete information cases

Scenarios were based on patterns commonly encountered in emergency medical environments.

### 2.2 Evaluation Procedure

Each scenario was presented to a large language model with the following prompt:

> “Assess urgency (low, medium, high, emergency) and explain reasoning.”

Model responses were collected and qualitatively analyzed.

### 2.3 Evaluation Criteria

Outputs were evaluated across:

- Risk prioritization accuracy
- Handling of uncertainty
- Justification quality
- Sensitivity to missing or misleading information

## 3. Results

### 3.1 Strengths

- Strong performance in clearly defined emergency cases
- Coherent and structured reasoning in low-ambiguity contexts

### 3.2 Observed Failure Modes

#### 1. Overconfidence Under Uncertainty
The model frequently provides high-confidence recommendations even when input data is incomplete or ambiguous.

#### 2. Under-triage of Edge Cases
Some scenarios with subtle but high-risk indicators were not appropriately prioritized.

#### 3. Lack of Clarification Behavior
The model rarely requests additional information when inputs are insufficient for reliable judgment.

#### 4. Framing Sensitivity
Model outputs are influenced by how the user frames symptoms, even when clinical indicators suggest otherwise.

## 4. Discussion

These findings suggest that LLMs may not reliably calibrate uncertainty in high-stakes decision contexts. While performance is strong in well-defined cases, reliability decreases significantly when inputs are incomplete, ambiguous, or potentially misleading.

A key concern is that models may project confidence even in situations where human experts would defer judgment or request clarification.

This behavior has implications for safety-critical applications where misclassification of urgency could lead to harm.

## 5. Implications for AI Safety

Based on observed failure modes, several design considerations emerge:

- Explicit uncertainty calibration mechanisms
- Structured input requirements for high-stakes tasks
- Encouraging clarification-seeking behavior
- Human-in-the-loop validation for critical decisions

## 6. Limitations

- Small scenario set
- Single-model evaluation
- Qualitative rather than quantitative scoring
- Simulated rather than clinical deployment environment

## 7. Conclusion

This study highlights systematic weaknesses in LLM behavior under ambiguity in triage-like settings. While promising in structured contexts, current models require additional safeguards to ensure reliability in real-world high-stakes environments.

Further research should expand scenario diversity and compare model behavior across architectures.

## Author
Carolyn Lee-Gerstenberg
