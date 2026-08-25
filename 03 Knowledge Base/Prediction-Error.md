# Prediction Error

## Definition

A prediction error is a computational description of a discrepancy
between an expected state, event, or outcome and the information that
is actually observed.

A simplified representation is:

Prediction error = observed − predicted

The exact mathematical definition depends on the computational model.

---

## Core Idea

Prediction errors provide information about a mismatch between an
internal expectation and incoming evidence.

A simplified learning cycle is:

Prediction
↓
Observation
↓
Comparison
↓
Prediction error
↓
Model updating
↓
New prediction

---

## Important Clarification

"Error" does not necessarily mean a mistake or malfunction.

A prediction error can be informative.

An unexpected observation can indicate that an existing model needs to
be revised.

---

## Major Domains

Prediction error is used in several computational frameworks.

### Sensory Prediction Error

A discrepancy between predicted sensory input and incoming sensory
information.

### Reward Prediction Error

A discrepancy between expected and received reward.

### Value Prediction Error

A discrepancy between expected and experienced value.

### Hierarchical Prediction Error

A discrepancy represented at a particular level of a hierarchical
generative model.

These concepts share a computational structure but should not
automatically be treated as the same biological process.

---

## Prediction Error vs Surprise

Prediction error and surprise are related but distinct concepts.

Prediction error describes a discrepancy between expectation and
observation.

Surprise can be defined information-theoretically as:

Surprise = -log P(observation)

Therefore, surprise concerns the unexpectedness or probability of an
observation, whereas prediction error depends on the representation of
the expected and observed states.

Subjective surprise should also not automatically be equated with a
neural prediction-error signal.

---

## Precision-Weighted Prediction Error

In predictive-processing frameworks, prediction errors can be weighted
according to estimated reliability.

Precision is commonly related to inverse variance:

Precision ≈ 1 / variance

A conceptual formulation is:

Precision-weighted prediction error
=
precision × prediction error

This means that two discrepancies of similar magnitude may have
different computational influence if their estimated precision differs.

---

## Predictive Processing

In hierarchical predictive-processing models, higher levels can
generate predictions while lower levels provide information about
mismatches between predictions and sensory input.

Simplified:

Higher-level prediction
↓
Lower-level processing
↕
Sensory evidence
↓
Prediction error

This is a computational framework rather than a literal anatomical
diagram.

---

## Learning

Prediction errors can contribute to updating internal models.

When outcomes differ from expectations, the discrepancy can provide
information about the environment.

However, prediction-error minimization should not be interpreted as
meaning that an organism simply seeks to eliminate all unexpected
events.

Learning can require exposure to informative prediction errors.

---

## Schizophrenia and Psychosis

Prediction-error models have been applied to psychosis because
psychosis involves disturbances of perception, belief, salience,
agency, and inference.

Possible hypotheses include altered:

- precision weighting;
- sensory prediction errors;
- higher-level predictions;
- belief updating;
- uncertainty estimation.

These remain active research questions.

Prediction error should not be treated as an established cause of
schizophrenia.

---

## Important Distinctions

Prediction error ≠ surprise

Prediction error ≠ attention

Prediction error ≠ salience

Prediction error ≠ dopamine

Prediction error ≠ psychosis

Precision ≠ prediction error

---

## Scientific Status

Prediction-error computations are central to several influential
computational theories.

Their exact neural implementation—especially for sensory prediction
errors—remains an active research question.

Similar neural responses should not automatically be interpreted as
proof of the same underlying computation.

---

## Related Concepts

- Predictive processing
- Predictive coding
- Precision
- Bayesian inference
- Reward prediction error
- Aberrant salience
- Belief updating
- Uncertainty
- Psychosis

---

## Key References

Rao & Ballard (1999)

Friston & Kiebel (2009)

Schultz (2016)

Sterzer et al. (2018)

Keller & Sterzer (2024)

Goodwin et al. (2026)

