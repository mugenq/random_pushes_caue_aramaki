# Choosing the Simplest Useful Tool

> **LLM text | Human AI** · Design philosophy from the author's technical discussions  
> **Provenance:** Repeated author positions in discussions of BeatSolver, data analysis and AI.

## Thesis

Begin with the actual problem. Compare candidate methods by their constraints, not by how fashionable the methods are. An ML model is justified only if its expected benefits survive the costs of collecting lawful data, validation, inference, maintenance, and error handling.

A structured aggregation might be better handled with SQL or a BI tool. Strongly periodic, interpretable signals might be suited to signal-processing techniques. A learned model can be worthwhile when pattern complexity, variability or adaptation requirements warrant it.

## The BeatSolver example

The author's rhythm-game timing project seeks to suggest timing candidates and reduce verification burden, **without replacing human judgment**. Hybrid signal processing and transparent candidate scoring have practical appeal, while learned components imply additional work: acquiring permissioned human-made timing data, building consent-based uploads, evaluation, and ongoing quality control.

This is a reason to be discriminating, not a claim that ML is intrinsically harmful.

## Desired principles

- Prefer interpretable baselines.
- Measure failure modes before claiming success.
- Respect dataset provenance and consent.
- Include operational and computational costs in method choice.
- Keep responsibility for consequential judgments with people.

**Status:** Engineering philosophy with project experience, not a general proof about AI systems.
