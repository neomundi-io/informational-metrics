# Volumetry - Informational Volume Metric

## Working English Version

This document presents a public and methodological definition of volumetry as used within the NeoMundi framework.

It does not disclose proprietary parameters, production thresholds, full decision rules, or internal mechanisms used in the NeoMundi engine.

## Definition

Volumetry refers to the observation of the informational volume handled or produced during an AI generation or an execution segment.

It describes simple, measurable, and auditable quantities, such as:

- input volume;
- output volume;
- generation length;
- number of tokens processed;
- number of execution windows observed;
- relationship between the requested volume and the produced volume.

Volumetry does not measure the quality of a response.  
It provides a measurement context for interpreting other informational metrics.

## Role of Volumetry

Volumetry serves as a descriptive foundation.

It makes it possible to situate a generation within its production context:

- short or long response;
- compression or expansion of information;
- low or high generation load;
- comparison between several outputs;
- analysis of length-related effects;
- control of volume-related biases.

In a runtime governance system, volumetry helps avoid interpreting signals in isolation.

A long response should not be considered unstable only because it is long.  
A short response should not be considered reliable only because it is concise.

## Observable Variables

Volumetric variables may include, among others:

- `tokens_in`: input token volume;
- `tokens_out`: output token volume;
- `total_tokens`: total volume processed;
- `input_output_ratio`: relationship between input and output;
- `execution_windows`: number of runtime windows observed;
- `segment_length`: length of an analyzed segment.

These variables are descriptive.  
They do not constitute, by themselves, a governance decision.

## Interpretation

Volumetry can help distinguish several situations:

- a brief response with low informational load;
- a long but stable response;
- a long and unstable response;
- a short but risky response;
- strong informational expansion;
- contraction or synthesis of information.

It also helps better understand certain derived metrics, such as volumetric density, informational energy, or informational density.

## What Volumetry Does Not Claim to Measure

Volumetry does not claim to measure:

- semantic truth;
- factual certainty;
- internal coherence;
- the human quality of a response;
- governance stability;
- the presence or absence of hallucination;
- the legal responsibility of a generation.

It measures volume, not validity.

## Relationship with Other Metrics

Within the NeoMundi framework, volumetry serves as a basis for other informational metrics.

It may help contextualize:

- volumetric density;
- informational energy;
- informational density;
- stability signals;
- governance decisions.

Volumetry does not replace signals such as G or ΔG.  
It provides a contextual layer that helps interpret observed variations.

## Methodological Position

Volumetry is a descriptive and non-decisional metric.

It is useful because it makes visible the amount of information handled by an AI system during execution.

It must always be interpreted alongside other signals, including stability, risk, density, and governance signals.

## Limits

Volumetry can be easily measured, but it can be misinterpreted.

A high volume may correspond to a useful, structured, and stable response.  
A low volume may correspond to an insufficient, ambiguous, or misleading response.

Volumetry should therefore never be used alone to conclude on the quality, stability, or reliability of an AI generation.
