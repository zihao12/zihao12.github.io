---
title: "Concept Algebra for Text-Controlled Vision Models"
collection: publications
permalink: /publication/2023-01-30-Concept-Algebra-for-Text-Controlled-Vision-Models
date: 2023-01-30
venue: 'Arxiv prepint'
paperurl: 'https://arxiv.org/abs/2302.03693'
citation: 'Zihao Wang and Lin Gui and Jeffrey Negrea and Victor Veitch. "Concept Algebra for Text-Controlled Vision Models." arXiv preprint arXiv:2302.03693 (2023)'
---
This paper concerns the control of text-guided generative models, where a user provides a natural language prompt and the model generates samples based on this input.
Prompting is intuitive, general, and flexible. 
However, there are significant limitations: prompting can fail in surprising ways, and it is often unclear how to find a prompt that will elicit some desired target behavior. 
A core difficulty for developing methods to overcome these issues is that failures are know-it-when-you-see-it---it's hard to fix bugs if you can't state precisely what the model should have done! 
In this paper, we introduce a formalization of ``what the user intended'' in terms of latent concepts implicit to the data generating process that the model was trained on. 
This formalization allows us to identify some fundamental limitations of prompting. We then use the formalism to develop \emph{concept algebra} to overcome these limitations. 
Concept algebra is a way of directly manipulating the concepts expressed in the output through algebraic operations on a suitably defined representation of input prompts. 
We give examples using concept algebra to overcome limitations of prompting, including concept transfer through arithmetic, and concept nullification through projection.
Code available at \url{https://github.com/zihao12/concept-algebra}.