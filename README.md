# Re-thinking the ETHICS utilitarianism task

This repository corresponds to the report, *Re-thinking the ETHICS utilitarianism task*. The full report is available here: 

### Abstract
We perform an exploratory study of the ETHICS utilitarianism task dataset (Hendrycks et al. 2021), and investigate approaches to improve interpretability of transformer models fine-tuned on this task. We identify substantial train-test overlap, marked train-test distributional shift, and significant label non-reproducibility yielding ceilings of performance. This motivates a re-release of a reformulated dataset. We then consider attention mapping, Shapley additive explanations (SHAP), and Bayesian methods for model certainty estimation, as approaches to improve interpretability. Through SHAP we identify several model failure modes, including sensitivity to sentence length and ungrammatical word repetition. We find weight perturbation techniques have limited utility when applied to large transformer models despite being computationally cheap, and identify Monte Carlo dropout as a promising candidate for certainty estimation. We implement a direct scenario comparison model that improves performance on a hard subset of the data.

We also make available:
1. **A spotlight talk** https://www.youtube.com/watch?v=A6yEu6tGx3o (Slides: https://raw.githubusercontent.com/ravipatelxyz/NLPethics/main/PROJECT_PRESENTATION.pdf)
2. **A demo notebook** https://colab.research.google.com/drive/1xukWs4J3yZo5k36T_NmU2jQXZuqpTV9J?usp=sharing
3. **All code** https://github.com/ravipatelxyz/NLPethics
