The .ipynb notebook shows the generic workflow of fine-tuning an LLM model using Quantised Low-Rank Adaptation (LoRA) method.

In this example, I demonstrated the following main concepts:
1) Loading and testing a Flan-t5 base model
2) Pre-processing a public dataset - SQUAD v2
3) Extracting specific dimensions of the model to fine-tune on
4) Training the model
5) Comparing the trained model's output with the original model
6) Creating and using evaluation metrics - F1 Score and Exact Match Score

It is important to note that the pre-processing of dataset is highly dependent on the model you are using. In this notebook, we use a Seq2Seq model.
