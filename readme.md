# FOG Computing Project

Welcome!

This repo was made as part of FOG Computing course lead by prof. dr. Vlado Stankovski.

## Architecture
![project_architecture](assets/architecture.jpg)

Tracking/managment of our experiments was done using [Weights & Biases](https://docs.wandb.ai/).

We are packaging up the prediction system and deploying it as a [Docker](https://docs.docker.com/) container on [AWS Lambda](https://aws.amazon.com/lambda/).

Our prediction system is wrapped in a frontend written in Python using [Gradio](https://gradio.app/docs).

## Colab Demo

<div align="center">
  <a href="https://colab.research.google.com/github/lukakeso/FOG/blob/main/src/notebooks/lab07_deployment.ipynb"> <img src=https://colab.research.google.com/assets/colab-badge.svg width=240> </a>
</div> <br>

## Local installation

```
conda env create -f environment.yml
```
