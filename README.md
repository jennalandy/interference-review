## Causal Inference with Partial Interference: A Review

This review was put together as a final project for [Harvard's BST 258, Causal Inference: Theory and Practice](https://www.coursicle.com/harvard/courses/BST/258/) by Jenna Landy, Christian Testa, and Daniel Xu.

**Abstract**: Standard causal inference methods often make use of the assumption of no interference, which states that an observation’s treatment does not affect any other observation’s outcome. Though often reasonable, this assumption breaks down in many settings, including those involving infectious diseases and social networks. In this review, we provide an overview of popular methods developed to handle partial interference, where we assume that individuals may only interfere with other individuals in their defined group. After defining causal estimands relevant to the interference setting, we present estimators for these estimands, as well as methods for inference and constructing confidence intervals that have been developed in recent years. Through simulations under partial interference, we demonstrate the need for these estimators over traditional treatment effect estimators that otherwise ignore interference. Lastly, we conclude by discussing some limitations of existing methods and areas of future research.

- [Paper](https://github.com/jennalandy/interference-review/blob/master/Causal_Inference_with_Partial_Interference.pdf)
- [Slide Deck](https://github.com/jennalandy/interference-review/blob/master/slide_deck.pdf)
- [Simulation Study (rendered qmd)](https://github.com/jennalandy/interference-review/blob/master/simulation_study/SimulationStudy.pdf)
- [Simulation Study (raw qmd)](https://github.com/jennalandy/interference-review/blob/master/simulation_study/SimulationStudy.qmd)
