# Article 07 — Research Dossier

## How Does the Brain Learn When the World Is Changing?

### Research focus

Uncertainty, volatility, learning-rate regulation, belief updating, and
their relationship to psychosis and schizophrenia.

---

# 1. Research Question

How does the brain determine whether an unexpected observation reflects
random noise or genuine change in the environment, and how should this
determination influence belief updating?

A secondary question is whether abnormalities in this process contribute
to computational phenotypes associated with psychosis.

A further exploratory question for the Precision Instability Framework
(PIF) is whether temporal dynamics in precision and uncertainty
regulation contain information that average computational parameters
do not capture.

---

# 2. Central Conceptual Framework

The article uses the following conceptual progression:

Sensory evidence
↓
Prediction
↓
Prediction error
↓
Precision
↓
Uncertainty
↓
Volatility inference
↓
Learning-rate regulation
↓
Belief updating
↓
New prediction

This is a conceptual synthesis rather than a claim that these are
discrete anatomical or computational modules.

---

# 3. Definitions

## Noise

Random variability in observations that does not necessarily indicate a
change in the underlying state or statistical structure.

## Uncertainty

Limited confidence about the current state, estimate, or interpretation.

## Volatility

The inferred degree to which the underlying state or statistical
structure of an environment is changing over time.

## Precision

A quantity related to the inverse of variance and representing the
estimated reliability or informativeness of information.

## Prediction error

The discrepancy between predicted and observed information.

## Learning rate

The degree to which new evidence changes an existing belief.

---

# 4. Core Mathematical Intuition

A simplified learning rule is:

New belief =
Old belief +
Learning rate × Prediction Error

The learning rate should not necessarily be fixed.

In a stable environment, a low learning rate can protect beliefs from
random noise.

In a volatile environment, a higher learning rate can facilitate rapid
adaptation.

Therefore, adaptive inference requires estimating the statistical
structure of the environment and adjusting learning accordingly.

---

# 5. Yu & Dayan (2005)

Yu, A. J., & Dayan, P. (2005).
Uncertainty, neuromodulation, and attention.
Neuron, 46(4), 681–692.

## Contribution

Provides a theoretical framework for distinguishing different sources
of uncertainty and discussing how uncertainty can influence attention
and neuromodulation.

## Relevance

Supports the broader idea that uncertainty is not merely a nuisance
variable.

The nervous system needs to estimate uncertainty because uncertainty
affects how incoming information should influence processing.

## Limitation

This is a theoretical computational neuroscience framework.

It does not establish a specific mechanism of schizophrenia.

---

# 6. Bach & Dolan (2012)

Bach, D. R., & Dolan, R. J. (2012).
Knowing how much you don't know: A neural organization of uncertainty
estimation.
Nature Reviews Neuroscience, 13, 572–586.

## Contribution

Reviews neural mechanisms involved in estimating uncertainty.

## Relevance

Provides a foundation for treating uncertainty estimation as a
computational problem implemented by the nervous system.

## Importance

Supports the distinction between uncertainty about the current state
and uncertainty arising from changing environmental structure.

## Limitation

The review concerns uncertainty broadly and is not a schizophrenia-
specific model.

---

# 7. Mathys et al. (2011)

Mathys, C., Daunizeau, J., Friston, K. J., & Stephan, K. E. (2011).
A Bayesian foundation for individual learning under uncertainty.
Frontiers in Human Neuroscience, 5, 39.

## Contribution

Provides a Bayesian foundation for modeling learning under uncertainty.

## Relevance

Establishes a formal framework for representing hierarchical beliefs
and uncertainty.

## Importance

Provides theoretical groundwork for hierarchical learning models.

---

# 8. Mathys et al. (2014)

Mathys, C., et al. (2014).
Uncertainty in perception and the Hierarchical Gaussian Filter.
Frontiers in Human Neuroscience, 8, 825.

## Contribution

Develops the Hierarchical Gaussian Filter (HGF) as a computational
framework for hierarchical inference under uncertainty.

## Core idea

Beliefs about higher-level properties of the environment can influence
learning at lower levels.

A simplified hierarchy can be represented as:

Observation
↓
Current state
↓
Volatility

## Relevance

The model formalizes the idea that inferred volatility can influence
belief updating.

## Important limitation

The HGF is a computational model.

Its parameters should not be interpreted as direct measurements of
specific biological processes without additional validation.

---

# 9. Fromm et al. (2022)

Fromm, S., et al. (2022).
Models of Dynamic Belief Updating in Psychosis—A Review Across Different
Computational Approaches.
Frontiers in Psychiatry, 13, 814111.

## Contribution

Reviews computational models of dynamic belief updating in psychosis.

## Major finding

The literature does not support one simple computational abnormality.

Findings include:

- increased updating;
- reduced updating;
- altered volatility estimation;
- altered responses to prediction errors;
- differences across tasks and computational models.

## Importance

This strongly argues against statements such as:

"Schizophrenia is caused by a high learning rate."

Instead, the literature motivates examination of how belief updating is
regulated under different environmental conditions.

---

# 10. Powers et al. (2020)

Powers, A. R., et al. (2020).
Volatility Estimates Increase Choice Switching and Relate to Prefrontal
Activity in Schizophrenia.
Biological Psychiatry: Cognitive Neuroscience and Neuroimaging, 5(2),
173–183.

## Contribution

Investigates computational estimates of environmental volatility in
schizophrenia using behavioral and neuroimaging measures.

## Main finding

Participants with schizophrenia showed increased estimates of
environmental volatility in the task.

Volatility beliefs influenced lower-level learning and were associated
with choice switching.

Volatility-related beliefs also related to dorsolateral prefrontal
activity.

## Importance

Provides direct evidence that volatility estimation can differ in
schizophrenia.

## Limitation

The finding is task-specific.

It does not demonstrate that schizophrenia universally involves
overestimation of volatility.

---

# 11. All-or-Nothing Belief Updating

Research on belief updating in schizophrenia has reported an
"all-or-nothing" pattern in response to unexpected events and change
points.

## Contribution

Challenges the idea that schizophrenia can be characterized by a
globally elevated learning rate.

## Important observation

Average learning rates may fail to capture important differences in the
way updating occurs across individual trials or contexts.

Some observations can produce excessive updating while other relevant
information may produce insufficient updating.

## Importance for PIF

This is particularly relevant to a hypothesis concerning temporal
dynamics and instability rather than simply elevated or reduced
parameters.

---

# 12. Fromm et al. (2023)

Fromm, S., et al. (2023).
Belief Updating in Subclinical and Clinical Delusions.
Schizophrenia Bulletin Open, 4(1), sgac074.

## Contribution

Examines belief updating in relation to psychotic and delusional
phenotypes.

## Relevance

Provides evidence that psychotic-like experiences can be associated with
altered updating under environmental uncertainty and change points.

## Important implication

Computational abnormalities may involve the relationship between
prediction error, precision, environmental change, and updating rather
than a single fixed learning parameter.

---

# 13. Mikus, Lamm & Mathys (2025)

Mikus, N., Lamm, C., & Mathys, C. (2025).
Computational Phenotyping of Aberrant Belief Updating in Individuals With
Schizotypal Traits and Schizophrenia.
Biological Psychiatry, 97(2), 188–197.

## Contribution

Uses a hierarchical Bayesian model to jointly estimate beliefs about
observational noise and task volatility.

## Importance

Provides a more refined computational decomposition of uncertainty.

## Major relevance

Relationships between uncertainty about task volatility and
schizotypal/positive symptoms differed from relationships between
observational-noise beliefs and negative symptoms.

## Implication

Different symptom dimensions may correspond to different computational
processes.

This supports moving away from treating schizophrenia as one
computational phenotype.

---

# 14. Volatility Is Not Delusion

An important conceptual distinction emerges from the literature.

Volatility estimation abnormalities and delusional ideation should not
be treated as identical.

Some studies associate schizophrenia with altered estimation of
environmental volatility.

Other findings associate delusional ideation with altered
precision-weighted prediction-error responses.

Therefore:

Volatility abnormality
≠
Delusion

They may interact, but they should not be collapsed into one mechanism.

---

# 15. Prediction Error Versus Volatility

Prediction error asks:

"What is different from what I predicted?"

Volatility asks:

"How likely is it that the underlying relationship has changed?"

These are different computational questions.

A large prediction error does not automatically mean that volatility is
high.

A stable environment can produce occasional large prediction errors.

Likewise, a volatile environment may produce observations that happen to
match a current prediction.

---

# 16. Precision Versus Volatility

Precision asks:

"How reliable is this information?"

Volatility asks:

"How likely is the underlying state or statistical relationship to be
changing?"

These variables can interact but should not be treated as synonyms.

A person can be highly uncertain about a stable environment.

A person can also observe a volatile environment with relatively clear
sensory information.

---

# 17. Learning Rate Versus Volatility

Volatility is not itself the learning rate.

Rather, inferred volatility can influence how much weight is given to
new evidence.

Conceptually:

Higher inferred volatility
→ greater expected relevance of new information
→ potentially higher learning rate

Lower inferred volatility
→ greater expected stability
→ potentially lower learning rate

The precise mathematical relationship depends on the computational
model.

---

# 18. Why Average Parameters May Be Insufficient

Suppose two participants have identical average learning rates.

Participant A:

high → low → high → low

Participant B:

medium → medium → medium → medium

Their averages could be similar.

Their dynamics are not.

This creates a methodological motivation for examining:

- trial-by-trial variability;
- temporal autocorrelation;
- adaptation to changing environments;
- state transitions;
- context sensitivity;
- coupling between uncertainty and updating.

This is a hypothesis-generating argument, not evidence that such measures
are already established biomarkers.

---

# 19. PIF Connection

The Precision Instability Framework proposes that abnormalities may be
better characterized by the dynamics of precision and uncertainty
regulation rather than their average levels alone.

This is explicitly a proposed hypothesis.

The literature reviewed here does not establish PIF.

Instead, the literature motivates a testable question:

> Does temporal instability in precision/uncertainty regulation provide
> additional explanatory or predictive information about psychosis beyond
> mean computational parameters?

---

# 20. Potential Predictions of PIF

If PIF is correct, one possible prediction would be that psychosis-related
phenotypes show greater temporal instability in measures related to
precision or uncertainty.

Potential measurable quantities include:

- trial-to-trial variability;
- temporal variance;
- autocorrelation;
- state-transition frequency;
- instability of computational parameter estimates;
- altered coupling between uncertainty and learning rate;
- abnormal adaptation following environmental change.

These are candidate measures rather than established biomarkers.

---

# 21. Falsification Criteria

PIF should make predictions that could fail.

Possible falsification outcomes include:

1. No difference in temporal instability between relevant groups.

2. Mean computational parameters explain all observed group differences
   while dynamic measures add no explanatory value.

3. Instability measures fail to generalize across tasks.

4. Instability measures show poor test-retest reliability.

5. Apparent instability is explained by measurement noise or model
   misspecification.

6. Alternative computational models explain the findings more
   successfully.

A strong research program should actively test these possibilities.

---

# 22. Proposed Experimental Paradigm

Participants could perform probabilistic learning tasks containing:

- stable environments;
- volatile environments;
- controlled observation noise;
- discrete change points.

Measurements could include:

- learning rate;
- prediction-error sensitivity;
- belief precision;
- uncertainty;
- volatility estimates;
- change-point sensitivity;
- trial-by-trial variability.

Clinical groups could include:

- healthy controls;
- schizophrenia;
- individuals with psychotic experiences;
- potentially individuals with other psychiatric conditions.

---

# 23. Computational Analysis

Candidate models:

### Model 1
Fixed learning-rate reinforcement learning.

### Model 2
Adaptive learning-rate reinforcement learning.

### Model 3
Bayesian belief-updating model.

### Model 4
Hierarchical Gaussian Filter.

### Model 5
Change-point model.

Model comparison should evaluate whether the added complexity of
volatility or hierarchical uncertainty is justified.

---

# 24. Model Validation

Important analyses include:

- parameter recovery;
- posterior predictive checks;
- model comparison;
- cross-validation;
- test-retest reliability;
- sensitivity analysis;
- simulation-based validation.

This is essential because computational parameters are latent estimates,
not directly observed variables.

---

# 25. Neural Investigation

## EEG / MEG

Potential targets:

- prediction-error responses;
- trial-to-trial variability;
- oscillatory dynamics;
- temporal stability;
- state transitions.

## fMRI

Potential targets:

- volatility-related activity;
- uncertainty representations;
- prediction-error signals;
- prefrontal systems;
- salience-related networks;
- dynamic functional connectivity.

The aim should be to connect:

Behavior
↓
Computational model
↓
Neural dynamics

rather than to assign a computational parameter to a single brain
region.

---

# 26. Major Scientific Cautions

## Caution 1

Schizophrenia is heterogeneous.

## Caution 2

Psychosis is not synonymous with schizophrenia.

## Caution 3

Delusions are not reducible to volatility estimation.

## Caution 4

Learning-rate parameters are model-dependent.

## Caution 5

HGF parameters are not direct biological measurements.

## Caution 6

Medication, illness stage, cognitive ability, and task demands can
affect computational estimates.

## Caution 7

Cross-sectional associations do not establish causality.

## Caution 8

Temporal variability can arise from genuine instability or measurement
noise.

---

# 27. Evidence Classification

## Established conceptual foundations

- Bayesian inference provides a formal framework for belief updating.
- Prediction errors quantify discrepancies between predictions and
  observations.
- Precision represents estimated reliability/informativeness.
- Uncertainty is fundamental to adaptive inference.
- Environmental volatility can be represented computationally.
- Adaptive learning requires context-sensitive updating.

## Supported but still actively researched

- altered volatility estimation in schizophrenia;
- altered belief updating in psychosis;
- relationships between uncertainty and symptom dimensions;
- neural representation of volatility;
- computational phenotyping of psychosis.

## Not established

- schizophrenia is caused by abnormal volatility estimation;
- all people with schizophrenia have excessive learning rates;
- all psychosis involves excessive prediction errors;
- volatility abnormalities explain delusions;
- PIF is an established theory.

---

# 28. Central Scientific Message

The brain must solve two related but distinct problems:

**How reliable is the current evidence?**

and

**Has the world itself changed?**

Precision and uncertainty help address the first.

Volatility addresses the second.

Learning-rate regulation links these estimates to belief updating.

Psychosis research suggests that this system may operate differently in
some clinical populations, but the abnormalities are heterogeneous.

The scientifically interesting question is therefore not simply whether
people update too much or too little.

It is whether the brain appropriately regulates updating as uncertainty
and environmental volatility change.

---

# 29. Relation to the Schizophrenia Research Journey

Articles 1–3:
Perception and the construction of experience.

Article 4:
Predictive processing.

Article 5:
Prediction error.

Article 6:
Precision.

Article 7:
Uncertainty, volatility, and adaptive learning.

Article 8:
Salience and aberrant salience.

The conceptual progression is:

Evidence
→ Prediction
→ Error
→ Precision
→ Uncertainty
→ Volatility
→ Learning
→ Salience
→ Psychosis

This progression should remain explicit throughout the series.

---

# 30. Final Evidence Statement

The literature supports the investigation of uncertainty, volatility,
belief updating, and learning dynamics in psychosis.

It does not establish a single computational mechanism for
schizophrenia.

The Precision Instability Framework remains a proposed research
hypothesis.

Its scientific value will depend on whether it generates predictions
that are:

- measurable;
- reproducible;
- model-robust;
- clinically informative;
- and falsifiable.

