# Article 07 — Research Notes

## Working title

How Does the Brain Learn When the World Is Changing?

## Subtitle

Uncertainty, volatility, and the computational problem of belief updating

---

# 1. Core Research Question

How does the brain distinguish temporary uncertainty or noisy evidence
from evidence that the underlying environment has actually changed?

This is fundamentally a problem of adaptive inference.

The system must balance:

- stability;
- flexibility;
- uncertainty;
- prediction error;
- learning.

---

# 2. Core Conceptual Distinctions

## Noise

Random variation in observations that does not necessarily indicate a
change in the underlying state or statistical structure of the environment.

## Uncertainty

Limited confidence about the current state or interpretation.

Uncertainty can arise because there is insufficient evidence or because
observations are noisy.

## Volatility

The inferred degree to which the underlying statistical structure or
latent state of the environment is changing over time.

Volatility is therefore not synonymous with uncertainty.

## Precision

A statistical quantity related to the inverse of variance.

Precision represents estimated reliability/informativeness.

## Learning rate

The degree to which new evidence changes an existing belief.

---

# 3. Core Computational Relationship

A simplified learning rule is:

New belief = Old belief + Learning rate × Prediction Error

The learning rate should not necessarily be fixed.

In dynamic environments, adaptive learning requires estimating whether
unexpected observations represent:

- noise;
- uncertainty;
- or genuine environmental change.

In hierarchical Bayesian models, inferred volatility and uncertainty can
therefore influence the effective learning rate.

---

# 4. Why Volatility Matters

In a stable environment:

- repeated observations can be integrated;
- beliefs become more precise;
- isolated deviations can often be treated as noise;
- slower updating can be adaptive.

In a volatile environment:

- previous observations may become less informative;
- prediction errors become more informative;
- uncertainty about the current state can increase;
- faster updating can be adaptive.

Therefore:

Environmental uncertainty/volatility
→ Learning-rate regulation
→ Belief updating

This is a conceptual computational relationship, not a claim about one
specific neural mechanism.

---

# 5. Hierarchical Learning

The Hierarchical Gaussian Filter (HGF) provides one computational
framework for representing learning in changing environments.

In simplified terms:

Level 1:
Observed outcomes

Level 2:
Belief about the current state

Level 3:
Belief about volatility/change in the underlying state

Higher-level beliefs about volatility can influence lower-level learning.

The model therefore provides a formal distinction between:

- observation noise;
- uncertainty about the current state;
- volatility of the environment.

Change-point detection models provide another framework for related
questions, especially when the environment is modeled as undergoing
discrete changes.

Different computational frameworks use different terminology and
assumptions, so parameters should not be treated as interchangeable.

---

# 6. Evidence on Psychosis

## Review evidence

A review of computational models of dynamic belief updating in psychosis
found substantial heterogeneity across tasks, samples, and modeling
approaches.

Both excessive updating and insufficient updating have been linked to
psychosis-related phenomena.

Schizophrenia and delusion-proneness have in several studies shown
difficulty distinguishing informative environmental changes from
uninformative noise.

Some studies report increased belief updating and overestimation of
environmental volatility.

However, the review emphasizes that correlations between computational
parameters and positive symptoms remain sparse and that findings can
differ depending on model and clinical context.

---

# 7. Direct Evidence for Volatility in Schizophrenia

A computational-fMRI study of schizophrenia found:

- heightened initial beliefs about environmental volatility;
- stronger influence of volatility beliefs on lower-level learning;
- increased choice switching;
- stronger association between volatility beliefs and dorsolateral
  prefrontal activity.

The finding was replicated in an independent nonmedicated sample.

Interpretation:

People with schizophrenia in this paradigm appeared to infer that the
environment was more volatile than healthy controls.

This may contribute to increased switching during reward-based
decision-making.

Important limitation:

This does not establish that all schizophrenia involves globally
increased volatility estimation.

---

# 8. Evidence Against a Simple "High Learning Rate" Model

A schizophrenia study using change-point and oddball conditions found
that patients did not simply behave like a model with uniformly
heightened sensitivity to unexpected events.

Average learning rates did not differ systematically.

Instead, patients showed a distinctive pattern involving:

- excessive updates in some situations;
- failure to update in others;
- reduced moderate belief updating;
- less flexible beliefs after change points;
- lower precision during stable periods.

The authors described this as an "all-or-nothing" pattern of belief
updating.

This is important because it suggests that computational dysfunction
may involve the regulation of updating rather than simply its average
magnitude.

---

# 9. Psychotic-Like Experiences

A 2023 study examined belief updating in 300 participants using a task
with controlled noise and environmental change points.

Psychotic-like experiences were associated with:

- lower tracking accuracy;
- smaller increases in belief precision after change points;
- slower updating following large prediction errors;
- reduced overall belief updating in response to prediction errors;
- reduced modulation of updating at inferred environmental change points.

The authors interpreted these findings as altered dynamics of belief
updating under environmental uncertainty.

This supports the idea that psychosis-related traits can involve
abnormal interaction between prediction error, uncertainty, and
change-point probability.

---

# 10. Volatility Versus Delusions

A 2023 fMRI study compared healthy participants and people with
schizophrenia while also distinguishing delusional ideation.

Findings included:

Schizophrenia:

- lower accuracy;
- heightened choice switching;
- overestimation of environmental volatility;
- attenuated neural representation of volatility in anterior insula,
  medial frontal, and angular regions.

Delusional ideation:

- increased precision-weighted prediction-error-related neural
  activation in frontostriatal regions.

Important implication:

Volatility-related abnormalities may not be identical to the mechanisms
specifically associated with delusional ideation.

This argues against treating "volatility" as a direct computational
definition of delusion.

---

# 11. Recent Computational Phenotyping

Mikus, Lamm, and Mathys (2025) developed a hierarchical Bayesian model
that jointly estimated beliefs about:

- observational noise;
- task volatility.

Samples included:

- healthy participants in a test-retest study;
- a large online sample with schizotypal traits;
- a cohort of 100 patients with schizophrenia.

Findings included:

- moderate-to-high reliability of model parameters;
- relationships between uncertainty about task volatility and
  schizotypal traits/positive symptoms;
- a different relationship between negative symptoms and beliefs about
  observational noise.

Interpretation:

Different symptom dimensions may relate to different computational
beliefs about the statistical structure of the environment.

This supports a transdiagnostic and symptom-specific approach rather than
a single computational deficit for schizophrenia.

---

# 12. Predictive Processing

Predictive-processing theories describe perception and inference as
involving predictions and prediction errors.

Precision determines the estimated influence of information.

Volatility introduces a higher-order question:

Is the underlying relationship itself changing?

A useful conceptual hierarchy is:

Observation
→ Prediction Error
→ Precision / Uncertainty
→ Volatility Inference
→ Learning-rate Regulation
→ Belief Updating
→ New Prediction

This is a conceptual synthesis rather than a claim that the brain
implements these stages as discrete modules.

---

# 13. Important Distinction

Prediction error:

"What does not match my prediction?"

Precision:

"How reliable is this information?"

Uncertainty:

"How certain am I about my current estimate?"

Volatility:

"How likely is it that the underlying state or statistical
relationship has changed?"

Learning rate:

"How much should I change my belief?"

These concepts are related but not interchangeable.

---

# 14. Stability Versus Flexibility

Adaptive inference requires both stability and flexibility.

Too little updating:

- beliefs become rigid;
- adaptation to genuine change becomes slow.

Too much updating:

- beliefs become unstable;
- random noise receives excessive influence.

The computational problem is therefore not simply:

"How high should the learning rate be?"

It is:

"How should learning rate change as uncertainty and environmental
volatility change?"

---

# 15. Connection to PIF

PIF remains a proposed research hypothesis.

The existing literature does NOT establish:

"Schizophrenia is precision instability."

A more defensible research question is:

Could temporal dynamics in precision and uncertainty regulation provide
additional information about computational abnormalities in psychosis?

Potential dimensions include:

- trial-by-trial variability;
- temporal stability;
- coupling between uncertainty and precision;
- coupling between volatility and learning rate;
- adaptation to changing environments;
- differences between stable and volatile task contexts.

The key hypothesis would not be that precision changes.

Healthy systems must change precision.

The hypothesis would concern whether precision/uncertainty dynamics are
inappropriately regulated or poorly coupled to environmental statistics.

---

# 16. Potential Experimental Strategy

## Behavioral

Use probabilistic learning tasks containing:

- stable blocks;
- volatile blocks;
- controlled observation noise;
- discrete change points.

Measure:

- learning rate;
- prediction-error sensitivity;
- belief precision;
- change-point sensitivity;
- volatility estimation;
- trial-by-trial variability.

## Computational

Compare:

- fixed learning-rate models;
- reinforcement-learning models;
- Bayesian models;
- Hierarchical Gaussian Filter;
- change-point detection models.

Use:

- model comparison;
- parameter recovery;
- posterior predictive checks;
- test-retest reliability.

## EEG / MEG

Potentially investigate:

- rapid prediction-error responses;
- trial-to-trial variability;
- oscillatory dynamics;
- temporal stability of neural responses.

## fMRI

Potentially investigate:

- prefrontal representations of volatility;
- uncertainty-related activity;
- prediction-error signals;
- network-level dynamics;
- dynamic connectivity.

---

# 17. Methodological Cautions

Computational parameters are model-dependent.

A "learning rate" in one model is not necessarily equivalent to a
parameter with the same informal label in another model.

HGF and change-point detection models make different assumptions.

Clinical samples can differ in:

- medication;
- illness stage;
- symptom profile;
- cognitive ability;
- task performance.

Therefore results should not automatically be generalized to all
people with schizophrenia.

---

# 18. Evidence Status

## Established / strong conceptual foundations

- uncertainty is central to adaptive inference;
- Bayesian updating provides a formal framework for combining evidence
  and prior information;
- precision is related to uncertainty;
- environmental volatility can be modeled computationally;
- adaptive learning requires sensitivity to changing environmental
  statistics.

## Active research

- neural implementation of volatility estimation;
- relationship between uncertainty and learning;
- computational mechanisms of psychosis;
- symptom-specific computational phenotypes;
- relationship between precision and volatility;
- temporal dynamics of belief updating.

## Proposed hypothesis

Precision Instability Framework (PIF).

PIF remains a proposed research hypothesis.

It should generate falsifiable predictions and should not be presented
as an established theory of schizophrenia.

---

# 19. Key References

Mathys, C., Daunizeau, J., Friston, K. J., & Stephan, K. E. (2011).
A Bayesian foundation for individual learning under uncertainty.
Frontiers in Human Neuroscience, 5, 39.

Yu, A. J., & Dayan, P. (2005).
Uncertainty, neuromodulation, and attention.
Neuron, 46(4), 681–692.

Bach, D. R., & Dolan, R. J. (2012).
Knowing how much you don't know: A neural organization of uncertainty
estimation.
Nature Reviews Neuroscience, 13, 572–586.

Stephan, K. E., et al. (2016).
The neurobiology of uncertainty: implications for statistical learning.
Philosophical Transactions of the Royal Society B, 371, 20160048.

Mathys, C., et al. (2014).
Uncertainty in perception and the Hierarchical Gaussian Filter.
Frontiers in Human Neuroscience, 8, 825.

Fromm, S., et al. (2022).
Models of Dynamic Belief Updating in Psychosis—A Review Across Different
Computational Approaches.
Frontiers in Psychiatry, 13, 814111.

Fromm, S., et al. (2023).
Computational mechanisms of belief updating in relation to
psychotic-like experiences.
Frontiers in Psychiatry, 14, 1170168.

Powers, A. R., et al. (2020).
Volatility Estimates Increase Choice Switching and Relate to Prefrontal
Activity in Schizophrenia.
Biological Psychiatry: Cognitive Neuroscience and Neuroimaging, 5(2),
173–183.

Powers, A. R., et al. (2020).
All or nothing belief updating in patients with schizophrenia reduces
precision and flexibility of beliefs.
Nature Mental Health / related open literature record.

Fromm, S., et al. (2023).
Belief Updating in Subclinical and Clinical Delusions.
Schizophrenia Bulletin Open, 4(1), sgac074.

Mikus, N., Lamm, C., & Mathys, C. (2025).
Computational Phenotyping of Aberrant Belief Updating in Individuals With
Schizotypal Traits and Schizophrenia.
Biological Psychiatry, 97(2), 188–197.

Keller, G. B., & Sterzer, P. (2024).
Predictive Processing: A Circuit Approach to Psychosis.
Annual Review of Neuroscience, 47, 85–101.

Goodwin, I., et al. (2026).
Predictive processing accounts of psychosis: bottom-up or top-down
disruptions.
Nature Mental Health, 4, 60–84.

---

# 20. Central Takeaway for Article 7

The brain must distinguish:

NOISE

from

GENUINE CHANGE.

Uncertainty concerns how well the current state is known.

Volatility concerns whether the underlying environment itself may be
changing.

Adaptive learning requires the brain to regulate belief updating in
accordance with these estimates.

Psychosis research suggests that this regulation may be altered, but
the direction is not uniformly "too much" or "too little" updating.

The most defensible scientific framing is therefore:

**Psychosis may involve altered dynamic regulation of belief updating
under uncertainty and environmental volatility.**

This provides a stronger foundation for asking whether instability in
precision/uncertainty regulation could represent an additional
computational phenotype.

PIF remains a hypothesis to be tested.

