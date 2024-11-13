# 📘 Jupyter Notebook Workshop Demo

This repository contains a demo of how to use Union with Jupyter Notebooks. It contains two notebooks:

| 📘 Notebook | 📝 Description | 🔗 Colab Link | 
|----------|-------------|-------------|
| **Basic demo** | Simple example of how to run Union tasks and workflows in a notebook | [![Colab Badge](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/unionai-oss/jupyter-notebook-workshop/blob/main/workshop.ipynb) |
| **Train a model** | A model-training example where you create a dataset, train a model, and generate predictions | [![Colab Badge](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/unionai-oss/jupyter-notebook-workshop/blob/main/train_model.ipynb) |

## ☁️ Running a Serverless Workspace

Currently, you need a developer installation of `union` to run the workspace.

```bash
git clone https://github.com/unionai-oss/union.git
cd union
pip install -e .
```

Then, you can run the workspace with:

```bash
union create workspace workspace.yaml
```

Delete it with:

```bash
union delete workspace jupyter-notebook-workshop
```
