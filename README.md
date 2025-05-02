# LLM Mathematical Reasoning Experiments

The paper on Pitfalls and Paths to Reproducibility in LLM Reasoning (https://arxiv.org/pdf/2504.07086) shows we could potentially increase the accuracy in LLM reasoning significantly just by changing the prompt format. This experiment investigates this further specifically with Mathematical LLMs such as DeepSeek-R1-Distill-Qwen1.5B. Focusing on mathematical reasoning initially helps reduce ambiguity in CoT evaluation as there are less nuanced expected answers. 

We have broken down this project into two key aspects:
  - Mathematical Chain of Thought Evaluation
  - Prompt-tuning LLMs to solve mathematical tasks.

## Prompt Tuning
1. Try out different prompt templates to get a fixed LLM model to answer the same mathematical problem to determine whether accuracy increases.
2. Set up a feedback loop system where we have a dataset of questions and answers, to see if we can automatically update the prompt to improve.
3. Try using the same optimal prompt on differnet models to investigae whether this optimal prompt can be generalised.

