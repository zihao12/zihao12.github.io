---
title: "A Unified Causal View of Domain Invariant Representation Learning"
collection: publications
permalink: /publication/2022-08-15-Unified-Causal-View-Of-Domain-Invariant-Representation-Learning
date: 2022-08-15
venue: 'Arxiv prepint'
paperurl: 'https://arxiv.org/abs/2208.06987'
citation: 'Zihao Wang, and Victor Veitch. "A Unified Causal View of Domain Invariant Representation Learning
." arXiv preprint arXiv:2208.06987 (2022).'
---
Machine learning methods can be unreliable when deployed in domains that differ from the domains on which they were trained. To address this, we may wish to learn representations of data that are domain-invariant in the sense that we preserve data structure that is stable across domains, but throw out spuriously-varying parts. There are many representation-learning approaches of this type, including methods based on data augmentation, distributional invariances, and risk invariance. Unfortunately, when faced with any particular real-world domain shift, it is unclear which, if any, of these methods might be expected to work. The purpose of this paper is to show how the different methods relate to each other, and clarify the real-world circumstances under which each is expected to succeed. The key tool is a new notion of domain shift relying on the idea that causal relationships are invariant, but non-causal relationships (e.g., due to confounding) may vary.