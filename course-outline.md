# Course Outline

## Quantitative Ecology: From Research Design to Predictive Modelling

This one-week intensive course follows the development of an ecological investigation from initial research questions and study design through statistical explanation, interpretation and prediction.

The course is cumulative. Rather than treating statistical methods as independent topics, participants repeatedly return to the same ecological system and ask increasingly demanding questions of the data.

The broad progression is:

**Research Design → Explore → Model → Challenge → Predict → Interpret**

***

## Day 1 — From ecological questions to data

### What are we trying to learn, and what evidence do we need?

Quantitative analysis begins before data are collected. The first day establishes the ecological problem, considers how research questions translate into observations, and examines how study design determines what can subsequently be inferred.

Participants then begin exploring the course dataset as an ecological system rather than immediately fitting models.

Topics include:

* ecological questions, hypotheses and predictions;

* experimental, mensurative and observational research;

* sampling units, replication and independence;

* response and explanatory variables;

* sources of variation and uncertainty;

* distributions and data structure;

* missing values and unusual observations;

* graphical exploration of ecological data.

### Central idea

**Good analysis cannot rescue a study that does not contain the evidence needed to answer the question.**

By the end of the day, participants should understand what was measured, how the observations arose, what variation exists in the data, and which ecological questions can reasonably be addressed.

***

## Day 2 — Explaining ecological variation

### Can we explain the patterns we observe?

Having established the ecological system and explored the data, the second day moves from description towards quantitative explanation.

Generalised linear models provide the main framework. The emphasis is not on memorising model families or R syntax, but on connecting the biological response, its statistical distribution and the ecological hypothesis being investigated.

Topics include:

* models as representations of ecological hypotheses;

* response distributions;

* linear predictors and link functions;

* Gaussian, binomial, Poisson and related models;

* coefficients and effect sizes;

* predictions and uncertainty;

* model diagnostics;

* interpreting statistical results biologically.

### Central idea

**A statistical model is useful because of the ecological question it represents, not because of its complexity.**

Participants use models to investigate relationships first encountered during Day 1 and evaluate what those models capture — and what they do not.

***

## Day 3 — When ecological relationships are not simple

### What if the relationship is not linear?

Ecological relationships are frequently nonlinear, but increasing model complexity should follow evidence rather than precede it.

Day 3 begins with limitations exposed by simpler models and asks how relationships can be represented when their form is not known in advance.

Generalised additive models provide a flexible extension of the modelling framework developed on Day 2.

Topics include:

* recognising nonlinearity;

* ecological reasons for nonlinear responses;

* smooth functions;

* basis complexity and smoothness;

* fitting GAMs with `mgcv`;

* visualising and interpreting smooth relationships;

* uncertainty and model diagnostics;

* avoiding unnecessary flexibility.

### Central idea

**Complexity should enter a model because the ecology requires it.**

The aim is not simply to learn GAMs, but to understand why a flexible relationship may provide a better representation of an ecological process.

***

## Day 4 — Structure, hierarchy and dependence

### What if our observations are not independent?

Ecological data commonly contain structure arising from sites, individuals, sampling occasions, regions or repeated observations.

Day 4 considers what happens when the assumption of independent observations is unrealistic and introduces hierarchical thinking and mixed-effects models.

Topics include:

* recognising grouped and repeated observations;

* pseudoreplication and dependence;

* hierarchical ecological data;

* fixed and random effects;

* random intercepts and slopes;

* mixed-effects models;

* partitioning sources of variation;

* conditional and population-level interpretation;

* consequences of study design for model structure.

### Central idea

**The structure of the model should reflect the structure of the observations.**

This reconnects statistical modelling directly to the research-design questions introduced on Day 1.

***

## Day 5 — From explanation to prediction

### Can our understanding predict observations we have not seen?

For most of the week, models have been developed using all available observations to understand ecological patterns.

Day 5 changes the question.

Instead of asking how well a model explains the data used to construct it, participants ask whether that understanding generalises to new observations.

This provides the conceptual transition from explanatory statistical modelling to predictive modelling.

Topics include:

* explanation versus prediction;

* training and test data;

* out-of-sample prediction;

* cross-validation;

* prediction error and model comparison;

* overfitting;

* regularisation;

* bias and variance;

* introduction to tree-based predictive methods;

* interpreting predictive performance ecologically.

### Central idea

**The model may not have changed. The question has.**

Predictive approaches are therefore introduced not as a separate machine-learning toolbox, but as another way of asking questions of ecological data.

***

# Course progression

Across the five days, the same broad scientific process is revisited:

**What is the ecological question?**

↓

**What evidence would answer it?**

↓

**What structure is present in the observations?**

↓

**What model represents the question and the data?**

↓

**What has the model explained — and what has it missed?**

↓

**Does that understanding generalise to new observations?**

The objective is not to identify a single "best" statistical method.

It is to develop the ability to move from an ecological problem to an appropriate quantitative analysis, understand the assumptions made along the way, and interpret the result in terms of the original biology.
