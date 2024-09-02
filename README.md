# NormGame_LLM

`NormGame_LLM` is a project where LLM (Large Language Model) agents play Axelrod's Norms Game. This game simulates the behavior of agents with varying degrees of boldness and vengefulness in a social norms setting.

## Overview

This repository contains Jupyter Notebooks that implement different configurations of agents participating in the Norms Game, as described in the corresponding paper. The configurations vary based on the agents' levels of boldness and vengefulness.

## Notebooks

### Axelrod Experiment with LLM

This project recreates and extends Axelrod's experiment using Large Language Models (LLMs). It includes the following notebooks:

- `Normgame_hbhv.ipynb`: Implementation of the Norms Game for a group with High Boldness and High Vengefulness.
- `Normgame_hblv.ipynb`: Implementation for a group with High Boldness and Low Vengefulness.
- `Normgame_lbhv.ipynb`: Implementation for a group with Low Boldness and High Vengefulness.
- `Normgame_lblv.ipynb`: Implementation for a group with Low Boldness and Low Vengefulness.
- `Eval.ipynb`: Notebook for evaluating simulation results and generating graphs as presented in the paper.

### Natural Language Evolution

This section explores evolutionary approaches using natural language:

- `Normgame_evo.ipynb`: Implementation of the game with natural language evolution, where agents' strategies evolve based on their success.
- `charactristic_generater.ipynb`: Notebook for generating agent personalities using LLMs.
- `umap_personality.ipynb`: Notebook for analyzing the results of natural language evolution by embedding them in UMAP (Uniform Manifold Approximation and Projection).

## Requirements

To run the notebooks, you will need access to the OpenAI API. The API key should be set in your environment variables, and the notebooks retrieve it with the following line of code:

```python
os.environ["OPENAI_API_KEY"] = os.environ.get("OPENAI_API_KEY")
```

Ensure you have your OpenAI API key set in your environment variables before executing the notebooks.

## Running the Notebooks

To run the notebooks, simply open them in Jupyter Notebook or JupyterLab and execute the cells. Make sure you have installed all necessary Python packages and have set your OpenAI API key as described above.

## Data

The `data` directory contains relevant data files used in the simulations. Ensure that these files are in place before running the notebooks.
