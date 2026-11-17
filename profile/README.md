# Small decision models for everyday work

Classification models turn messages and documents into labels that software can act on. A support system can route a ticket, a maintenance workflow can flag a note for review, and a model router can send difficult requests to a larger model. Handling routine decisions with a small model can reduce inference costs and keep more processing on your own infrastructure.

BA Research is an independent AI research lab in Calgary, Alberta. Our goal is to build the most useful open-source decision models for everyday commercial workflows. We evaluate models on practical tasks and aim for efficient self-hosted deployment and clear commercial-use terms for future releases.

## Try Qev

Qev is our experimental family of decision models based on Qwen. Your application supplies a question and the available answers. Qev scores those answers for tasks like choosing a category, checking a yes/no condition, or applying a scoring rubric.

The Qev 1.0 research checkpoints come in 0.8B, 2B, and 4B sizes. The model cards cover setup, evaluation, and limitations.

[See recorded examples](https://ba-research.github.io/#try) · [Browse models on Hugging Face](https://huggingface.co/ba-research) · [Run locally](https://github.com/ba-research/try-qev/tree/main/local) · [Open the Colab template](https://colab.research.google.com/github/ba-research/try-qev/blob/main/notebooks/ba_research_qev_enterprise_template.ipynb)

Local and Colab setup require authorized model files. Evaluate Qev on your own tasks before using it in a workflow.
