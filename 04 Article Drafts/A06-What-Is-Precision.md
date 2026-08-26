# 6. What Is Precision?

## Why the brain doesn't treat every piece of information as equally reliable

In the previous article, we explored prediction error—the mismatch between what a system expects and what it encounters.

But a new question immediately follows:

**How much should a prediction error matter?**

Imagine hearing a faint sound in a crowded room.

You expected silence.

There is now a mismatch between your prediction and the sensory evidence.

But should you immediately change your interpretation of the situation?

Probably not.

The sound might be noise.

It might be a conversation.

It might be something important.

The brain therefore needs more than information about *what* a signal says.

It also needs information about **how reliable that signal is**.

This brings us to one of the most important concepts in Bayesian inference and predictive processing:

**precision.**

---

## What does "precision" mean?

In statistics, precision is closely related to uncertainty.

A common mathematical definition is:

**Precision = 1 / Variance**

Variance describes how widely measurements are distributed.

If measurements vary greatly, uncertainty is high and precision is low.

If measurements cluster tightly together, uncertainty is lower and precision is higher.

So, in simplified terms:

**High precision → low uncertainty**

**Low precision → high uncertainty**

This sounds simple, but the idea becomes surprisingly powerful when applied to perception and inference.

---

## Precision is not the same as accuracy

There is an important distinction that is easy to miss.

**Accuracy** asks:

> How close is an estimate to the true value?

**Precision** asks:

> How reliable or tightly constrained is the estimate?

Imagine a broken weighing scale that consistently reports your weight as 70.5 kg when your actual weight is 73 kg.

It may be highly precise.

But it is not accurate.

This distinction matters enormously when we talk about beliefs.

A belief can be held with high confidence—or modeled as highly precise—without necessarily being true.

**Precision is not truth.**

It is about the estimated reliability of information.

---

## The brain is constantly dealing with uncertainty

The world does not arrive as a perfectly labeled dataset.

Sensory information is incomplete.

Signals are noisy.

Objects can be partially hidden.

Sounds can overlap.

Lighting changes.

People behave unpredictably.

Our own bodies change.

And our internal state changes how we interpret incoming information.

The brain therefore faces a fundamental computational problem:

> **How should I combine uncertain information from different sources?**

This is where Bayesian inference provides a useful framework.

---

## Prior beliefs meet sensory evidence

A simplified Bayesian picture looks like this:

**Prior belief + Evidence → Posterior belief**

A prior is information derived from what we already know or expect.

Evidence is information coming from the current observation.

The posterior is the updated interpretation after combining them.

But there is a problem.

What happens when the prior is uncertain but the evidence is reliable?

And what happens when the evidence is noisy but the prior is strong?

The answer depends partly on their relative precision.

---

## Imagine looking through fog

Suppose you see a blurry shape in the distance.

You think it might be a person.

But the visual evidence is weak.

You have seen people walking along this path many times before.

Your previous experience provides a useful expectation.

Now imagine the same situation on a clear day.

You can see the object distinctly.

The sensory evidence becomes much more reliable.

Your prior expectation should matter less.

In simplified terms:

**Weak evidence + strong prior → prior has greater influence**

**Strong evidence + weak prior → evidence has greater influence**

This doesn't mean the brain consciously calculates equations.

It means that Bayesian models provide a mathematical language for describing how information with different levels of uncertainty can be combined.

---

## From prediction error to precision

This brings us back to the previous article.

Prediction error describes a mismatch:

**Prediction → Observation → Mismatch**

But a mismatch alone does not tell us how important it is.

Suppose your prediction is:

> "There is nothing unusual happening."

You then hear a faint sound.

That is a prediction error.

But perhaps the sound is unreliable.

Now imagine hearing a loud, unmistakable alarm.

The prediction error is much more compelling.

The computational difference is not simply the size of the mismatch.

It is also the estimated reliability of the information carrying the mismatch.

This is the intuition behind **precision-weighted prediction error**.

Conceptually:

**Precision × Prediction Error**

A prediction error associated with highly reliable information can have a greater influence on inference than an error associated with highly uncertain information.

Again, this is a computational description—not a claim that a tiny calculator in the brain literally multiplies two numbers.

---

## Why would the brain need this?

Without something like precision weighting, every discrepancy between expectation and observation could potentially demand the same amount of updating.

That would be inefficient.

Imagine changing your entire understanding of the world every time you heard an ambiguous noise.

A better strategy is:

> **Update strongly when the evidence is reliable.**

> **Update cautiously when the evidence is uncertain.**

This principle is useful far beyond neuroscience.

It is fundamental to statistical inference.

---

## Precision and attention

Now we reach another interesting connection.

Why do we pay attention to some information and ignore other information?

Predictive-processing theories have proposed that attention may be related to the allocation or modulation of precision.

In this framework, attention can increase the effective influence of selected information.

But we should be careful:

**Attention is not simply the same thing as precision.**

They are related concepts, but they are not interchangeable.

Some computational theories propose that attentional mechanisms partly regulate which prediction errors receive greater effective weight.

This provides a possible computational bridge between:

**attention**

and

**precision-weighted inference.**

---

## Precision in predictive processing

Predictive processing describes perception as an ongoing process of prediction and error correction.

A simplified hierarchy might look like this:

**Higher-level prediction**

↓

**Lower-level sensory processing**

↓

**Prediction error**

↓

**Precision weighting**

↓

**Updating / inference**

↓

**New prediction**

The process is continuous.

And it can operate at multiple levels of the nervous system.

A low-level system might process edges, movement, or sound frequencies.

Higher levels might represent objects, contexts, or beliefs.

Different levels can therefore have different predictions, errors, and uncertainty.

This is one reason why "abnormal precision" is not a sufficiently precise explanation of anything by itself.

We have to ask:

**Precision of what?**

**At which level?**

**Relative to what competing information?**

**Over what timescale?**

---

## And now we reach schizophrenia

This is where precision becomes particularly interesting for our research journey.

Predictive-processing theories have proposed that altered precision weighting could contribute to some aspects of psychosis.

But this is where scientific caution becomes essential.

It would be tempting to say:

> "Schizophrenia is caused by abnormal precision."

We cannot make that claim.

The evidence is considerably more complicated.

Researchers have proposed different possibilities involving:

- sensory evidence;
- prior beliefs;
- prediction errors;
- uncertainty;
- attention;
- hierarchical inference;
- learning.

And these possibilities can point in different directions.

---

## Too much precision?

One family of theories proposes that internally generated predictions or prior beliefs can sometimes receive excessive influence.

In a simplified version:

**Strong prior**

+

**weak sensory evidence**

→

**prior dominates inference**

This has been proposed as one possible mechanism contributing to hallucinations or other unusual perceptual experiences.

But even here, we should be cautious.

A hallucination cannot simply be defined as:

**"a highly precise prediction."**

Human perception is more complicated than that.

---

## Or too much sensory precision?

Other predictive-processing accounts emphasize the opposite possibility.

Perhaps sensory prediction errors sometimes receive excessive influence.

In simplified terms:

**Weak prior**

+

**overweighted sensory prediction error**

→

**sensory evidence dominates inference**

This illustrates an important point:

There is no simple universal rule saying that psychosis means "too much precision."

Different symptoms, processing levels, contexts, and stages of illness may involve different computational abnormalities.

---

## Top-down and bottom-up explanations

This creates an important scientific debate.

A **top-down** account might emphasize overly influential prior expectations.

A **bottom-up** account might emphasize excessive influence of sensory prediction errors.

Both can potentially be expressed in terms of altered precision weighting.

And the reality may not fit neatly into either category.

Recent research continues to examine competing predictive-processing explanations of psychosis rather than treating one simple precision abnormality as established.

That uncertainty is scientifically valuable.

It tells us where the research problem actually is.

---

## Precision is not fixed

There is another reason to be careful.

Precision should not necessarily be thought of as a permanent property of the brain.

The reliability of information changes constantly.

A sound may be clear in a quiet room and ambiguous in a crowded room.

A visual object may be obvious in daylight and uncertain in darkness.

A person's behavior may be predictable in one context and unpredictable in another.

A healthy brain should therefore **change its weighting of information when circumstances change**.

This means that variability in precision is not automatically pathological.

In fact, flexibility is necessary for adaptive behavior.

---

## The deeper question: stability

This leads to a more interesting question.

Suppose two systems have the same average level of precision.

But one maintains relatively stable precision while the other fluctuates dramatically:

**High → High → Moderate → High → High**

versus:

**High → Low → Very high → Low → High**

Their average could be similar.

Their dynamics would be very different.

Could those dynamics matter?

This is where our research journey begins to move beyond the traditional question of "abnormal precision."

---

## From abnormal precision to precision instability

Instead of asking only:

> **Does schizophrenia involve abnormal precision?**

we can ask:

> **Could some forms of psychosis involve instability in how precision is maintained, allocated, or updated over time?**

This is a different hypothesis.

And it is a more demanding one.

It requires us to distinguish pathological instability from normal flexibility.

A brain must change its expectations when the world changes.

The problem would therefore not simply be:

**precision changes.**

The problem would be:

**precision changes inappropriately, excessively, unpredictably, or without appropriate coupling to environmental uncertainty.**

That distinction will be crucial if we want to turn this idea into a testable scientific framework.

---

## Precision Instability Framework

This is where the proposed **Precision Instability Framework (PIF)** enters our research journey.

PIF is not an established scientific theory.

It is a proposed research hypothesis.

The basic idea is that instability in the maintenance or allocation of precision could contribute to unstable inference across multiple domains.

Conceptually:

**Uncertainty**

↓

**Precision**

↓

**Precision weighting**

↓

**Prediction-error influence**

↓

**Inference**

↓

**Perception / belief / salience**

↓

**Experience**

PIF adds another question:

> **How stable is precision itself over time and across contexts?**

---

## What would make this scientifically testable?

This is where a hypothesis becomes more than an interesting idea.

We would need to operationalize it.

For example, computational models might estimate parameters related to:

- precision;
- learning rate;
- volatility;
- prediction-error weighting;
- trial-by-trial variability.

EEG or MEG could potentially investigate rapidly changing neural responses and oscillatory dynamics.

fMRI could investigate network-level changes and dynamic connectivity.

Behavioral experiments could examine how people update beliefs when environmental uncertainty changes.

The important point is that **PIF must make predictions that could potentially be wrong.**

If every possible result can be interpreted as evidence for PIF, then PIF is not a useful scientific hypothesis.

---

## Precision instability is not the same as noise

There is another challenge.

The brain is noisy.

Measurements are noisy.

Human behavior is variable.

So simply finding variability would not prove precision instability.

We would need to distinguish:

**ordinary noise**

from

**meaningful instability in computational weighting.**

That might require comparing observed variability against appropriate controls, task demands, measurement reliability, and expected adaptive changes.

---

## Precision instability is not the same as flexibility

This distinction may be even more important.

A healthy system should be flexible.

If the environment becomes more uncertain, precision should change.

If the sensory signal becomes clearer, precision should change.

Therefore:

**flexibility can be adaptive.**

PIF would need to identify something beyond normal flexibility.

Perhaps the critical property is whether precision changes remain appropriately coupled to the reliability of information.

In other words:

> **The problem may not be that precision changes, but that precision changes become poorly regulated.**

That is a hypothesis we can eventually test.

---

## What do we actually know?

At this point in our journey, it is useful to separate established knowledge from hypothesis.

### We have strong foundations for:

- precision as a statistical concept;
- the relationship between precision and variance;
- Bayesian representations of uncertainty;
- precision-weighted prediction errors in predictive-processing models;
- computational models linking precision and inference.

### We have active research questions concerning:

- the neural implementation of precision;
- the relationship between attention and precision;
- hierarchical precision;
- precision weighting in psychosis;
- sensory versus prior precision;
- how precision changes over time.

### And then there is our proposed hypothesis:

**Precision instability as a potentially important computational property in schizophrenia and psychosis.**

That hypothesis remains to be tested.

---

## The larger picture

Our research journey has now moved through a sequence:

**Sensory evidence**

↓

**Prediction**

↓

**Inference**

↓

**Prediction error**

↓

**Precision**

↓

**Precision weighting**

↓

**Perception / belief / salience**

↓

**Experience**

And now we have reached a new question:

**What happens when the system that determines how much information matters cannot maintain an appropriate weighting over time?**

We don't know the answer yet.

And that is precisely why it is worth investigating.

---

# The next question

Prediction error tells us:

> **Something doesn't match what I expected.**

Precision tells us:

> **How much should that mismatch matter?**

But uncertainty introduces another question:

> **How does the brain know how uncertain it is?**

That will take us to the next stage of our journey:

**How does the brain estimate uncertainty—and what happens when the world itself becomes unpredictable?**

The next article will explore:

**Uncertainty, volatility, and learning.**

