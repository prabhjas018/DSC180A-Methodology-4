---
layout: default
title: DSC 180A Methodology Assignment 4
---

# DSC 180A — Methodology Assignment 4

**Name:** Prabhjas Singh  
**UCSD Email:** YOUR_UCSD_EMAIL@ucsd.edu  
**Section/Domain:** D27 — Steering and Monitoring LLMs  
**Mentor:** YOUR_MENTOR_NAME

## Quarter 2 Project Reflection

**1. What is the most interesting topic covered in your domain this quarter?**  
The most interesting topic to me has been representation steering in language models. I am interested in how patterns in a model's internal activations can be measured and how changing those activations might influence its responses. Our Pain Axis reproduction has given me an opportunity to explore this idea experimentally.

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**  
I would like to investigate whether a pain related steering direction generalizes across different prompts and model sizes. Rather than evaluating it on only a small set of examples, I would test a larger and more varied set of situations and measure whether steering changes the model's answers consistently.

**3. What is a potential change you'd make to the approach taken in your current Quarter 1 Project?**  
I would expand the validation beyond our initial small sample and add stronger controls. For example, I would compare the pain direction with randomly chosen directions, use more diverse prompts, and repeat the experiment with multiple random seeds. This could help determine whether any changes are specifically caused by the pain direction rather than by unrelated variation.

**4. What other techniques would you be interested in using in your project?**  
I would like to explore PCA or SVD to analyze activation patterns, linear probes to measure what information is represented, and layer-by-layer ablation studies to see where interventions have the strongest effect. I would also like to compare different steering strengths and evaluate possible tradeoffs in response quality.
