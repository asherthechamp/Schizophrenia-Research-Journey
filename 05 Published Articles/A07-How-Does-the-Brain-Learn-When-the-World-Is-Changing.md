7. How Does the Brain Learn When the World Is Changing?

Uncertainty, volatility, and the computational problem of belief updating

In the previous article, we explored precision—the estimated reliability of information and the role it can play in determining how strongly prediction errors influence inference.

But precision leads to another question.

If the brain receives uncertain information, how does it know whether that uncertainty is simply noise—or whether something in the world has actually changed?

Imagine walking through a familiar neighborhood.

You normally expect to see a particular shop on the corner.

One day, the shop is gone.

Your expectation and the incoming evidence no longer match.

You have experienced a prediction error.

But what should you conclude?

Perhaps the shop is temporarily closed.

Perhaps you simply missed it.

Or perhaps the neighborhood is changing.

The brain therefore faces a deeper computational problem:

«Is this observation just noise, or is the world itself changing?»

That distinction is fundamental to learning.

---

Not all uncertainty is the same

The world is full of uncertainty.

Sensory signals are noisy.

Information is incomplete.

Events can be unpredictable.

And our knowledge is always limited.

But uncertainty can arise for different reasons.

Suppose you are trying to determine whether it will rain tomorrow.

You might be uncertain because you have very little information.

But imagine that you have noticed that the relationship between clouds and rain has recently become inconsistent.

Now you face another possibility:

Perhaps the environment itself has changed.

This brings us to the concept of volatility.

---

What is volatility?

In computational models, volatility refers roughly to how much the underlying structure of an environment changes over time.

A stable environment has relatively consistent statistical relationships.

A volatile environment does not.

Imagine learning a game in which one option usually produces a reward.

If the rules remain stable, you can gradually learn the relationship.

But if the probabilities suddenly change, your previous knowledge becomes less reliable.

You need to update your beliefs.

The important question is therefore not only:

«What happened?»

but also:

«Has something changed?»

---

Noise, uncertainty, and volatility

These concepts are related, but they are not interchangeable.

Noise is random variation in observations that does not necessarily indicate a change in the underlying environment.

Uncertainty is limited confidence about the current state or interpretation.

Volatility concerns whether the underlying state or statistical structure of the environment is changing.

Consider a simple example.

Imagine repeatedly tossing a coin.

Sometimes it produces heads.

Sometimes tails.

The individual outcomes are variable.

That variability does not necessarily mean the coin has changed.

Now imagine that the probability of heads suddenly shifts.

The underlying environment is different.

A system that can distinguish these situations has a major computational advantage.

It does not need to react strongly to every unexpected observation.

Instead, it needs to determine whether unexpected observations provide evidence that its model of the world needs to change.

---

Prediction error is only the beginning

This connects directly to the previous articles.

Prediction error tells us:

«Something doesn't match what I expected.»

Precision asks:

«How reliable is this information?»

Volatility asks:

«Is the underlying situation itself changing?»

And learning asks:

«How much should I change my belief?»

These questions can be represented as a larger computational process:

Prediction

↓

Observation

↓

Prediction Error

↓

Precision / Uncertainty

↓

Volatility Inference

↓

Learning

↓

Updated Belief

↓

New Prediction

This is not meant to describe a literal sequence of separate brain modules.

It is a conceptual description of a computational problem.

---

Why learning rate matters

Imagine two environments.

In the first, the world is highly stable.

In the second, the world changes frequently.

Suppose you receive the same unexpected observation in both environments.

Should you update your beliefs by the same amount?

Probably not.

In a stable environment, an isolated unexpected event may simply be noise.

In a volatile environment, the same event may be evidence that something important has changed.

This is where the idea of a learning rate becomes useful.

A simplified learning rule is:

New belief = Old belief + Learning rate × Prediction Error

The learning rate determines how strongly a new observation changes an existing belief.

A low learning rate produces gradual updating.

A high learning rate produces rapid updating.

Neither is universally better.

The appropriate learning rate depends on the environment.

---

Stability versus flexibility

This creates a fundamental trade-off.

If a system updates too slowly, it can become rigid.

It may continue relying on an outdated model even after the world has changed.

But if it updates too quickly, it can become unstable.

Every random fluctuation may cause a major revision.

Adaptive learning therefore requires a balance between:

stability

and

flexibility.

The brain must preserve useful knowledge while remaining capable of recognizing genuine change.

---

The brain has to estimate volatility

This makes volatility itself an object of inference.

The brain cannot simply know in advance whether an environment is stable.

It has to infer this from experience.

Repeated prediction errors may provide evidence that the environment is changing.

But isolated prediction errors may simply reflect noise.

The computational challenge is therefore:

«How should the brain infer whether prediction errors reflect noise or genuine environmental change?»

Hierarchical Bayesian models provide one way of formalizing this problem.

---

Hierarchical learning

One influential computational framework is the Hierarchical Gaussian Filter, or HGF.

The basic idea is that beliefs can be represented at multiple levels.

At a lower level, the system may represent observations.

At a higher level, it may represent the current state of the environment.

At an even higher level, it can represent beliefs about how rapidly that state is changing.

Conceptually:

Observations

↓

Current state

↓

Volatility

Higher-level beliefs can therefore influence how rapidly lower-level beliefs should be updated.

When volatility is inferred to be high, prediction errors may carry more information.

When volatility is low, individual prediction errors may be treated more cautiously.

The HGF is a mathematical model of this process—not a claim that the brain literally contains three computational layers corresponding exactly to the model.

---

What happens when the environment changes?

Imagine that you have learned:

«When I see this signal, this outcome usually follows.»

For a long time, your prediction works.

Then suddenly the relationship changes.

Your predictions begin failing.

At first, you might treat the failures as noise.

But as prediction errors accumulate, the probability that the environment has changed increases.

Eventually, the rational response may be:

«My old model is no longer reliable.»

Your learning rate should increase.

You should update your beliefs.

And once the new relationship becomes stable, the learning rate can decrease again.

This gives us an important idea:

«Adaptive learning requires dynamic learning.»

---

What does this have to do with schizophrenia?

This computational problem becomes particularly interesting in psychosis.

Researchers have investigated whether people with schizophrenia or psychotic experiences differ in how they estimate uncertainty, volatility, or the reliability of prediction errors.

But the findings do not support a simple story.

It is not enough to say:

«Schizophrenia means learning too quickly.»

Nor:

«Schizophrenia means learning too slowly.»

Different studies have found different patterns depending on the task, computational model, symptom dimension, and clinical population.

This complexity is important.

It suggests that we should ask a more precise question:

«How does the regulation of belief updating change under uncertainty and environmental volatility?»

---

Volatility and schizophrenia

Some computational studies have found evidence that people with schizophrenia may infer greater environmental volatility in certain tasks.

In these studies, participants with schizophrenia showed increased estimates of volatility and greater influence of volatility beliefs on lower-level learning.

This can lead to increased switching between choices.

One interpretation is that the system may sometimes treat the environment as more changeable than it actually is.

If so, previously learned information may be discounted too quickly.

But this does not mean that everyone with schizophrenia constantly experiences the world as highly volatile.

Nor does it establish volatility estimation as a general cause of schizophrenia.

The result is task-dependent and should be interpreted within the computational model being used.

---

But belief updating can also be too weak

The story becomes even more interesting when we look at other studies.

Some research suggests that schizophrenia is not characterized simply by excessive updating.

Instead, people may show a more irregular pattern.

They may update strongly in some circumstances but fail to update in others.

In one line of research, patients showed an "all-or-nothing" pattern of belief updating around unexpected events and change points.

That is very different from simply saying:

«The learning rate is too high.»

The problem may instead involve how the system regulates updating across different situations.

That distinction is crucial.

---

The same person can need different learning rates

Consider two situations.

Situation 1: A stable environment

You repeatedly observe the same relationship.

An unexpected observation occurs once.

A rational learner might largely ignore it.

Situation 2: A changing environment

The same unexpected observation occurs after a series of increasingly inconsistent outcomes.

Now the observation may be highly informative.

The appropriate response is different.

This means that healthy cognition requires context-sensitive updating.

The question is not simply:

«How much does this person update?»

It is:

«Does the amount of updating appropriately track the statistical structure of the environment?»

---

Uncertainty versus volatility

This distinction deserves special attention.

Imagine that you are trying to identify a person through fog.

You cannot see clearly.

You are uncertain.

But the person themselves may be standing completely still.

The environment is uncertain from your perspective, but not necessarily volatile.

Now imagine that you can see perfectly—but the person keeps moving unpredictably.

The observations may be clear, while the underlying situation is highly volatile.

So:

Uncertainty ≠ Volatility

A system can be uncertain about a stable environment.

And it can observe a volatile environment with relatively clear sensory information.

This distinction matters for computational psychiatry because different abnormalities may affect different components of the inference process.

---

From precision to volatility

Article 6 asked:

«How much should this information matter?»

Article 7 asks:

«How quickly should I change my model of the world?»

Precision helps address the first question.

Volatility helps address the second.

We can therefore extend our conceptual framework:

Sensory Evidence

↓

Prediction

↓

Prediction Error

↓

Precision

↓

Uncertainty

↓

Volatility

↓

Learning Rate

↓

Belief Updating

↓

New Prediction

The system is continuously moving through this process.

---

What about delusions?

This becomes particularly interesting when we consider delusions.

A person encounters evidence that conflicts with an existing belief.

How much should that evidence change the belief?

There are several possibilities.

If prediction errors are given too much influence, beliefs may change too readily.

If prediction errors are given too little influence, beliefs may become unusually resistant to contradictory evidence.

And if the system has difficulty estimating environmental volatility, it may also have difficulty determining whether a surprising observation represents a meaningful change or random noise.

These are plausible computational possibilities.

But they should not be mistaken for a complete explanation of delusions.

Delusions are complex phenomena involving cognition, emotion, learning, social experience, prior beliefs, and neurobiology.

No single computational parameter is likely to explain them all.

---

The deeper question

At this point, our research journey has reached a more interesting question.

The problem may not simply be:

Too much updating

or

Too little updating.

It may involve the regulation of updating over time.

A system could potentially show a pattern such as:

over-update → under-update → over-update → stabilize

depending on the context.

Its average learning rate might not capture this dynamic.

Two people could have the same average learning rate while having very different trial-by-trial trajectories.

That raises a possibility worth investigating:

«Could the dynamics of belief updating contain information that average computational parameters miss?»

---

From learning dynamics to precision dynamics

This question brings us back to the developing Precision Instability Framework.

PIF proposes a research direction rather than an established theory.

The idea is not that healthy brains maintain perfectly constant precision.

They should not.

Precision must change when the reliability of information changes.

Similarly, learning rates should change when environmental volatility changes.

The potentially interesting question is whether these changes remain appropriately regulated.

For example:

Uncertainty changes

↓

Precision changes

↓

Prediction-error weighting changes

↓

Learning changes

↓

Beliefs update

If these relationships become poorly regulated, the resulting dynamics could potentially become unstable.

But this is a hypothesis.

It requires empirical testing.

---

What would a test look like?

We could create an experiment in which participants learn about an environment whose statistical structure changes over time.

For example:

Stable period

↓

Increasing uncertainty

↓

Environmental change

↓

New stable period

We could then estimate:

- learning rate;
- uncertainty;
- volatility;
- prediction-error sensitivity;
- belief precision;
- trial-by-trial variability.

Computational models could ask whether people with psychotic symptoms differ in how these parameters change across conditions.

The key would be to examine dynamics, not simply averages.

---

Computational modeling

Several modeling approaches could be compared.

A simple reinforcement-learning model might estimate a learning rate.

A Bayesian model could represent uncertainty explicitly.

A hierarchical model such as the HGF could estimate beliefs about volatility.

Change-point models could represent sudden transitions in environmental structure.

Comparing these models would be important because different models make different assumptions.

A parameter called "learning rate" in one model should not automatically be treated as equivalent to a similarly named parameter in another.

Good computational psychiatry therefore requires more than fitting a model.

We need to ask whether the model:

- explains the data;
- generalizes;
- produces reliable parameters;
- makes distinguishable predictions;
- survives comparison with alternative models.

---

From behavior to brain

The same framework can eventually be investigated at the neural level.

EEG and MEG

These techniques provide high temporal resolution and may help investigate:

- rapid responses to unexpected events;
- trial-to-trial variability;
- oscillatory dynamics;
- temporal stability.

fMRI

fMRI may help investigate:

- representations of uncertainty;
- volatility-related activity;
- prediction errors;
- belief updating;
- network-level dynamics.

The ultimate goal is not simply to find a brain region that "contains volatility."

It is to connect:

Behavior

↓

Computational parameters

↓

Neural dynamics

That is the promise of computational psychiatry.

---

What do we actually know?

At this point, it is useful to separate established knowledge from hypothesis.

We have strong theoretical foundations for:

- uncertainty as a central problem in inference;
- Bayesian belief updating;
- prediction error;
- precision;
- learning rates;
- computational representations of volatility.

There is active research on:

- how the brain estimates volatility;
- how uncertainty regulates learning;
- how prediction errors influence belief updating;
- how these processes differ in psychosis;
- whether computational abnormalities differ across symptom dimensions.

And there is our proposed hypothesis:

Precision Instability Framework.

PIF suggests that the temporal regulation of precision and uncertainty may deserve investigation alongside their average levels.

That remains an open research question.

---

The bigger picture

Our journey has now moved through a chain:

Sensory Evidence

↓

Prediction

↓

Prediction Error

↓

Precision

↓

Uncertainty

↓

Volatility

↓

Learning

↓

Belief Updating

↓

Experience

The deeper lesson is that perception and belief are not simply about detecting errors.

The brain must continuously estimate:

What should I expect?

How surprising is this?

How reliable is the evidence?

How uncertain am I?

Has the world changed?

How much should I update?

And then it must do it again.

And again.

And again.

---

The next question

If the brain is constantly updating its model of the world, another question becomes unavoidable:

«Why do some things become especially important?»

Why does one unexpected event attract our attention while another disappears into the background?

Why can an otherwise ordinary event suddenly feel unusually significant?

This takes us toward one of the most important concepts in schizophrenia research:

salience.

And eventually:

aberrant salience.

---

References

Bach, D. R., & Dolan, R. J. (2012). Knowing how much you don't know: A neural organization of uncertainty estimation. Nature Reviews Neuroscience, 13, 572–586.

Mathys, C., Daunizeau, J., Friston, K. J., & Stephan, K. E. (2011). A Bayesian foundation for individual learning under uncertainty. Frontiers in Human Neuroscience, 5, 39.

Mathys, C., et al. (2014). Uncertainty in perception and the Hierarchical Gaussian Filter. Frontiers in Human Neuroscience, 8, 825.

Yu, A. J., & Dayan, P. (2005). Uncertainty, neuromodulation, and attention. Neuron, 46(4), 681–692.

Fromm, S., et al. (2022). Models of Dynamic Belief Updating in Psychosis—A Review Across Different Computational Approaches. Frontiers in Psychiatry, 13, 814111.

Powers, A. R., et al. (2020). Volatility Estimates Increase Choice Switching and Relate to Prefrontal Activity in Schizophrenia. Biological Psychiatry: Cognitive Neuroscience and Neuroimaging, 5(2), 173–183.

Fromm, S., et al. (2023). Belief Updating in Subclinical and Clinical Delusions. Schizophrenia Bulletin Open, 4(1), sgac074.

Mikus, N., Lamm, C., & Mathys, C. (2025). Computational Phenotyping of Aberrant Belief Updating in Individuals With Schizotypal Traits and Schizophrenia. Biological Psychiatry, 97(2), 188–197.

Keller, G. B., & Sterzer, P. (2024). Predictive Processing: A Circuit Approach to Psychosis. Annual Review of Neuroscience, 47, 85–101.

Goodwin, I., et al. (2026). Predictive processing accounts of psychosis: bottom-up or top-down disruptions. Nature Mental Health, 4, 60–84.

---

Evidence status

Uncertainty, volatility, predictive processing, and computational models of psychosis are active areas of research.

The Precision Instability Framework (PIF) described in this series is a proposed research hypothesis, not an established scientific theory.
