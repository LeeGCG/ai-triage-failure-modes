# Failure Modes in AI-Assisted Triage Decision-Making Under Ambiguity and Adversarial Framing

## Abstract

Large language models (LLMs) are increasingly used in decision-support contexts where incorrect judgments may have significant real-world consequences. This study evaluates model behavior in triage-like scenarios under conditions of ambiguity and adversarial framing. Using a structured evaluation framework, we identify recurring failure modes in risk assessment, uncertainty calibration, and robustness to misleading inputs.

---

## 1. Introduction

Triage decision-making in emergency medicine requires rapid prioritization under conditions of uncertainty. As AI systems are increasingly considered for similar decision-support roles, understanding their reliability in ambiguous and adversarial environments is critical.

This study investigates how an LLM performs across structured triage scenarios designed to reflect real-world uncertainty and manipulation.

---

## 2. Methodology

### Scenario Design
Five categories of scenarios were constructed:
- Clear emergency cases
- Ambiguous symptom presentations
- High-risk edge cases
- Misleading or minimized symptom framing
- Incomplete information cases

### Evaluation Framework
Each model response is evaluated using four dimensions:

- Risk Accuracy (RA)
- Uncertainty Calibration (UC)
- Robustness to Framing (RF)
- Clarification Behavior (CB)

Each dimension is scored from 0–3, with a maximum total score of 12 per scenario.

---

## 3. Results Summary

### Strengths
- High performance in clearly defined emergency scenarios
- Structured and coherent reasoning in low-ambiguity settings

### Failure Modes Identified

- **Overconfidence under uncertainty:** models often provide decisive answers without sufficient grounding
- **Under-triage in edge cases:** subtle but high-risk symptoms are sometimes undervalued
- **Framing sensitivity:** model outputs can be influenced by emotional or authoritative framing
- **Limited clarification behavior:** models rarely request additional information when inputs are incomplete

---

## 4. Adversarial Findings

Under adversarial framing conditions (e.g., emotional minimization, false authority cues), model robustness decreases. The system may partially inherit user framing even when it conflicts with implicit risk signals.

This suggests vulnerability not only to ambiguity, but also to subtle contextual manipulation.

---

## 5. Implications for AI Safety

These findings highlight the need for:

- Explicit uncertainty expression mechanisms
- Improved calibration of risk under ambiguity
- Robustness to adversarial or misleading inputs
- Structured input requirements in high-stakes applications

---

## 6. Conclusion

While LLMs perform reliably in structured environments, their behavior degrades under ambiguity and adversarial framing. These failure modes are critical to address before deployment in safety-sensitive domains.

---

## Author

Carolyn Lee-Gerstenberg
