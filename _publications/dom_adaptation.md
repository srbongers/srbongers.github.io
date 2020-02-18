---
title:  "Domain Adaptation by Using Causal Inference to Predict Invariant Conditional Distributions"
type: "published"
venue: "Advances in Neural Information Processing Systems"
venue-link: "https://nips.cc/Conferences/2018"
venue-acronym: "NeurIPS 2018"
author: "S. Magliacane, T. van Ommen, T. Claassen, S. Bongers, P. Versteeg and J. M. Mooij"
image: "/assets/images/dom_adaptation.png"
bibtex: "/assets/bibtex/dom_adaptation.bib"
links:
  - link-arxiv: "https://arxiv.org/abs/1707.06422"
  - link-archive: "https://papers.nips.cc/paper/8282-domain-adaptation-by-using-causal-inference-to-predict-invariant-conditional-distributions"
  - pdf: "https://papers.nips.cc/paper/8282-domain-adaptation-by-using-causal-inference-to-predict-invariant-conditional-distributions.pdf"
  - supplement: "https://papers.nips.cc/paper/8282-domain-adaptation-by-using-causal-inference-to-predict-invariant-conditional-distributions-supplemental.zip"
---

An important goal common to domain adaptation and causal inference is to make accurate predictions when the distributions for the source (or training) domain(s) and target (or test) domain(s) differ. In many cases, these different distributions can be modeled as different contexts of a single underlying system, in which each distribution corresponds to a different perturbation of the system, or in causal terms, an intervention. We focus on a class of such causal domain adaptation problems, where data for one or more source domains are given, and the task is to predict the distribution of a certain target variable from measurements of other variables in one or more target domains. We propose an approach for solving these problems that exploits causal inference and does not rely on prior knowledge of the causal graph, the type of interventions or the intervention targets. We demonstrate our approach by evaluating a possible implementation on simulated and real world data.
