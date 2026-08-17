# Article 3 — How Does the Brain Construct Reality?

## Perception, prediction, uncertainty, and the experience of the world

We usually imagine perception as something simple.

The world is out there.

Light reaches the eyes.

Sound reaches the ears.

The brain receives the information.

And we experience reality.

It is an intuitive picture.

But it is incomplete.

The brain does not receive the external world directly. Sensory
systems provide signals from which neural systems construct
perceptual representations.

Those signals are incomplete, noisy, and constantly changing.

From them, the nervous system has to construct an interpretation
of what is happening.

That raises a profound question:

> **If the brain does not simply record reality, how does it construct
> the reality we experience?**

And for our schizophrenia research journey, an even more important
question follows:

> **What happens when the processes involved in perception, prediction,
> uncertainty, and inference become altered?**

---

# The Brain Does Not Simply Record Reality

A camera records light.

The brain does something considerably more complicated.

Consider a familiar object.

You can recognize it even when:

- the lighting changes;
- part of it is hidden;
- you see it from an unusual angle;
- the image is blurry;
- it appears in a different context.

The sensory signal changes.

Yet your perception can remain remarkably stable.

This stability suggests that perception is not simply a one-to-one
translation of sensory input.

The brain uses information about the world that it has already learned.

It combines incoming signals with context, expectations, and prior
knowledge.

This does not mean that perception is imaginary.

It means that perception is an interpretation constrained by evidence.

---

# Sensory Information Is Incomplete

Imagine trying to identify an object from a photograph with half of
the image missing.

You might still recognize it.

Why?

Because the missing information can sometimes be constrained by what
you already know.

The same principle applies throughout perception.

Sensory information can be:

- incomplete;
- ambiguous;
- noisy;
- degraded;
- conflicting.

The nervous system therefore faces a continuous inference problem:

> **What is the most likely explanation for the information I am
> receiving?**

This question lies at the heart of several computational theories
of perception.

---

# A Bayesian Way of Thinking About Perception

One mathematical framework for inference is Bayesian inference.

In simplified form:

**P(hypothesis | evidence)**

is proportional to:

**P(evidence | hypothesis) × P(hypothesis)**

In ordinary language:

What we believe after receiving evidence depends on both the evidence
and what we already considered plausible.

Suppose you hear a sound in the distance.

The sound itself may be ambiguous.

But if you are standing beside a river, you may consider one
explanation more likely.

If you are standing in a busy city, you may consider another more likely.

The sensory signal has not necessarily changed.

The context has.

Bayesian inference provides a mathematical language for describing
this kind of combination of evidence and prior information.

But Bayesian inference is a broad mathematical framework.

It should not be equated with predictive processing.

---

# Prediction Enters the Picture

Predictive-processing theories take the idea of inference further.

In simplified terms, a hierarchical system can generate predictions
about incoming sensory information.

Incoming information can then be compared with those predictions.

The mismatch can be represented as a prediction error.

Conceptually:

**Prediction**

↓

**Sensory evidence**

↓

**Mismatch**

↓

**Prediction error**

↓

**Model updating**

This is a simplified conceptual diagram.

Real neural systems are considerably more complicated.

Predictive coding is not one single theory with one universally
accepted implementation.

Different researchers have proposed different models of how prediction,
prediction error, attention, and learning interact.

That distinction matters.

Predictive processing is best understood as a family of related
computational and theoretical approaches rather than one completed
theory of the brain.

---

# Why Predict at All?

Why would the brain need predictions?

Because the world is uncertain.

If the brain had to interpret every sensory signal from scratch,
perception would be slow and computationally expensive.

Predictions allow the system to anticipate what it is likely to
encounter.

They can also make perception more stable.

Consider language.

When someone speaks to you in a noisy environment, you can often
understand words that are acoustically incomplete.

Your knowledge of language helps constrain the interpretation.

The same general principle can operate across perception.

The brain does not simply ask:

> "What signal arrived?"

It may also need to ask:

> "Given everything I already know, what could have produced this
> signal?"

---

# But Predictions Can Be Wrong

A prediction is not reality.

It is a hypothesis.

When incoming information conflicts with the prediction, the system
has an opportunity to update.

This is where prediction error becomes important.

A prediction error is not necessarily a failure.

It can be useful information.

If you expect a familiar object and encounter something unexpected,
the mismatch tells you that your model may need revision.

In this sense, perception can be understood as a continuous process
of balancing expectations against evidence.

---

# The Importance of Uncertainty

Now we reach a deeper problem.

What if the sensory signal itself is unreliable?

Suppose you are trying to identify a person in a dark room.

The sensory evidence is weak.

Your prior knowledge may become more important.

But suppose you are looking at a person in bright daylight.

The sensory evidence is much stronger.

The brain can rely more heavily on the incoming information.

This introduces an important computational concept:

**precision.**

---

# What Is Precision?

In Bayesian and predictive-processing frameworks, precision is broadly
related to the reliability of information.

It is often described mathematically as the inverse of variance.

In simplified terms:

**High precision → lower uncertainty**

**Low precision → higher uncertainty**

Precision therefore affects how strongly information should influence
inference.

This is a computational concept.

The brain does not necessarily contain a little meter labelled
"precision."

Rather, computational models use precision to describe the relative
reliability or uncertainty associated with information.

---

# Precision Is Not Simply Attention

Precision and attention are related concepts in some computational
accounts, but they are not interchangeable.

Attention refers to mechanisms through which processing is selectively
prioritized.

Precision is a computational quantity describing the estimated
reliability or uncertainty of information.

Some predictive-processing theories connect attention with
precision-weighting mechanisms.

But the concepts should not simply be equated.

This distinction will become important when we later examine attention,
salience, and the Precision Instability Framework.

---

# Precision Changes the Balance

Imagine two sources of information.

### Source A

Very noisy sensory evidence.

### Source B

A strong expectation based on previous experience.

A rational inference system may give greater weight to Source B.

Now reverse the situation.

### Source A

Clear, reliable sensory evidence.

### Source B

A weak expectation.

The sensory evidence may dominate.

So the important question is not simply:

> "Does the brain predict?"

It almost certainly uses expectations in many contexts.

A more interesting question is:

> **How strongly should the brain trust its predictions compared with
> incoming evidence?**

That is a question about weighting and uncertainty.

---

# From Perception to Psychosis

Now we can return to schizophrenia.

Psychosis involves experiences such as:

- hallucinations;
- delusions;
- disturbances of thought;
- altered salience;
- changes in self-experience.

Could computational abnormalities in inference contribute to some of
these experiences?

This is an active area of research.

But we need to be careful.

There is no established computational model that explains all of
schizophrenia.

And there is no evidence that one simple change in prediction explains
every hallucination or delusion.

---

# Hallucinations

A hallucination is a perception-like experience occurring without
an appropriate external stimulus.

Hallucinations are heterogeneous.

They can differ in:

- modality;
- emotional character;
- perceived location;
- controllability;
- agency;
- frequency;
- relationship to thought.

One influential computational hypothesis proposes that internally
generated expectations can sometimes exert unusually strong influence
on perceptual experience.

Experimental work has shown that learned perceptual expectations can
contribute to hallucination-like experiences under certain conditions.

This is important evidence.

But it does not establish the simple statement:

> "Hallucinations are caused by excessive priors."

The evidence is more complicated.

Some studies have reported stronger influence of prior expectations,
while others have reported findings more consistent with weakened or
altered priors.

Different levels of the perceptual hierarchy may also behave
differently.

Therefore the scientifically useful question is not simply whether
priors are "too strong."

It is:

> **How are sensory evidence, prior expectations, uncertainty, and
> their relative weighting altered in different psychotic experiences?**

---

# Delusions

Delusions raise a different computational problem.

A delusion is not simply a perception.

It is a belief.

And beliefs must be updated in response to evidence.

Computational psychiatry has therefore investigated questions such as:

- How does the brain update beliefs?
- How much weight does it give new evidence?
- How does it estimate uncertainty?
- How quickly does it change its beliefs?
- How does salience influence belief formation?

Different computational models emphasize different mechanisms.

There is no single accepted computational explanation of delusions.

---

# Salience

Another influential framework is the theory of aberrant salience.

Salience concerns what stands out as important or significant.

Kapur proposed that dysregulated dopamine signaling could contribute
to the inappropriate assignment of salience, helping connect
biological processes with the phenomenology of psychosis.

This theory has been influential.

But, like predictive processing, it should not be treated as a
complete explanation of schizophrenia.

Two decades of research have produced important findings while also
leaving substantial questions unresolved.

That is a recurring theme of this research journey.

A good scientific theory should become more precise as evidence
accumulates—not more certain simply because it is influential.

---

# Prediction Is Not the Same as Explanation

This distinction is especially important.

Predictive processing can provide a framework for understanding how
a system might combine:

- evidence;
- expectations;
- uncertainty;
- prediction errors.

But a framework is not automatically an explanation of a disorder.

To explain schizophrenia, we would still need to understand:

- development;
- genetics;
- neurotransmission;
- neural circuits;
- cognition;
- social context;
- individual differences;
- symptom heterogeneity;
- treatment response.

The challenge is to connect these levels without pretending that
one level replaces the others.

---

# From Experience to Computation

This is where our journey connects Articles 2 and 3.

Article 2 asked:

> **What is schizophrenia like from the inside?**

Article 3 asks:

> **How might the brain generate experiences of the world?**

The conceptual bridge is:

**Experience**

↓

**Perception**

↓

**Inference**

↓

**Computation**

↓

**Neural implementation**

This is not an established causal hierarchy.

It is a research strategy.

It allows us to ask whether a particular experience can be described
computationally and whether that computational description can then
be connected to measurable neural processes.

---

# Where Does Precision Become Interesting?

This brings us to a question that will become increasingly important
throughout this research journey.

Suppose perception depends partly on estimating the reliability of
different sources of information.

What happens if those estimates themselves become unstable?

Not simply:

> Too much prediction.

Not simply:

> Too little prediction.

But perhaps:

> **The system has difficulty consistently determining how much weight
> different sources of information deserve.**

This is a more general hypothesis.

It could potentially affect different domains:

- sensory perception;
- attention;
- salience;
- learning;
- motivation;
- cognition;
- self-processing.

But we must draw a clear scientific boundary.

---

# Introducing PIF

The **Precision Instability Framework**, or PIF, is a proposed
research hypothesis developed within this research journey.

It is not an established theory of schizophrenia.

PIF asks whether instability in precision maintenance or allocation
could contribute to disturbances across multiple domains.

The question is not:

> "Is PIF correct?"

The scientific question is:

> **Does PIF generate predictions that survive comparison with competing
> explanations and empirical data?**

That distinction matters.

An original idea becomes scientifically useful not when we believe it,
but when it becomes testable.

---

# What Would PIF Have to Explain?

If precision instability were relevant to schizophrenia, we would need
to ask whether the hypothesis makes useful predictions concerning:

- perception;
- attention;
- learning;
- salience;
- motivation;
- cognition;
- self-experience.

And importantly:

Would the same mechanism explain all of these domains?

Or would different mechanisms be required?

This is precisely where a hypothesis can fail.

And that is scientifically valuable.

---

# Competing Explanations

PIF should therefore be compared with other frameworks, including:

- predictive-processing models;
- Bayesian belief-updating models;
- aberrant-salience models;
- dopamine-centered models;
- glutamatergic models;
- E/I balance models;
- neurodevelopmental models;
- cognitive-control models;
- large-scale network models.

The goal is not to replace these models with PIF.

The goal is to discover which explanations survive evidence.

Perhaps one will.

Perhaps several will.

Perhaps schizophrenia will ultimately require a combination of
mechanisms.

---

# The Unresolved Problem

We began with a simple question:

> **How does the brain construct reality?**

We now have a more complicated answer.

The brain does not appear to passively record the world.

Perception involves the interaction of sensory evidence with
expectations, context, uncertainty, and internal models.

Computational theories such as Bayesian inference and predictive
processing give us ways of describing these processes.

But the transition from ordinary perception to psychosis remains
far from solved.

Hallucinations, delusions, altered salience, disturbances of agency,
negative symptoms, and cognitive difficulties may not all arise from
one computational abnormality.

The heterogeneity of schizophrenia is therefore not simply a nuisance
to be ignored.

It may be one of the most important clues.

---

# A Different Question

Perhaps the wrong question is:

> "What is the one mechanism that causes schizophrenia?"

Perhaps a better question is:

> **"What computational and biological processes become unstable,
> and how do different patterns of instability produce different
> experiences?"**

That question is more difficult.

But it may also be more scientifically productive.

And it brings us to the next stage of the journey.

---

# Conclusion

The brain does not experience the world by simply receiving a perfect
copy of reality.

It continuously interprets incomplete information.

It uses previous experience.

It generates expectations.

It responds to discrepancies.

And it must estimate how much confidence to place in different sources
of information.

This gives us a powerful way to think about perception.

But it does not yet give us a complete theory of schizophrenia.

The important scientific frontier lies somewhere between experience,
computation, and biology.

And one question will follow us into the next articles:

> **What happens when the brain's estimates of reliability themselves
> become unreliable?**

That is where prediction meets uncertainty.

And eventually, precision.

---

# Scientific Note

Predictive processing, Bayesian inference, aberrant salience, and
related computational approaches are active areas of scientific
research.

They should not be treated as established complete explanations of
schizophrenia.

The Precision Instability Framework (PIF) is an original proposed
research hypothesis in this project.

It is not an established theory.

The purpose of this research journey is to investigate hypotheses
against evidence and competing explanations—not to assume that they
are correct.

---

# References

See:

`06 References/A03-References.md`

