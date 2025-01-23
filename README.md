# Evaluating Retrieval-Augmented Generation with RAGAS
# ODSC AI Builders Summit 2025
This repo contain resources accompanying my webinar at ODSC AI Builders Summit 2025 including slides and notebooks.

## Getting Started
You will need to install a couple of libraries in your Python environment. For MacBook (Silicon),
```bash
pip install -U ragas pymilvus llama-index transformers sentence-transformers mlx-lm==0.20.6
```
Note the pinned version for `mlx-lm`. This is due to a breaking change in later versions that hasn't been fixed as of Jan 23, 2024. I will update this once the code has been patched.

Similar libraries are required for other hardware like those with Nvidia CUDA-capable or AMD graphics cards (details during presentation).

## Presentation
In the first half of the webinar, I will give a background on why RAG evaluation is important and how an established yet simple method works.

## Workshop
In the second half of the webinar, I will run through code notebooks to show:
1. Basics of vector databases with Milvus
2. Basics of foundation model eval with RAGAS
3. Creating a RAG-esque pipeline with Milvus
4. Combining Milvus and RAGAS, to build a RAG pipeline and evaluate it

## Next Steps
This repo will be continued to be updated after the event based on the questions and feedback received.