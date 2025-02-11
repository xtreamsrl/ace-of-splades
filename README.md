# RAG: One Year Later

Become the Ace of SPLADEs!

**name** | **open in**
:-----: | :-------:
[Embed Movies into Vectors](./notebooks/00-datasets_builder.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/xtreamsrl/movies-buddy/blob/main/notebooks/00-dataset_builder.ipynb)
[Simple RAG Pipeline](./notebooks/01-first-rag.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/xtreamsrl/movies-buddy/blob/main/notebooks/01-first-rag.ipynb)
[You Need a Domain Expert](./notebooks/02-domain-expert.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/xtreamsrl/movies-buddy/blob/main/notebooks/02-domain-expert.ipynb)
[LLM-As-a-Judge](./notebooks/03-llm-as-a-judge.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/xtreamsrl/movies-buddy/blob/main/notebooks/03-llm-as-a-judge.ipynb)
[HyDE: Hypothetical Document Embeddings](./notebooks/04-HyDE.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/xtreamsrl/movies-buddy/blob/main/notebooks/04-HyDE.ipynb)
[Leverage Metadata To Enanche Retrieval](./notebooks/05-improve-metadata-search.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/xtreamsrl/movies-buddy/blob/main/notebooks/05-improve-metadata-search.ipynb)


## 🤗 How to contribute

1. Clone the repo.

> [!NOTE]
> The project uses Python 3.12

2. Install `uv`, following the [official docs](https://docs.astral.sh/uv/getting-started/installation/)

3. Run the following:

```bash
uv sync
```

4. It is highly recommended to use `nbstripout` to avoid pushing the output of Jupyter Notebooks.
   Install it with:

```bash
uv run pre-commit install --install-hooks
```
