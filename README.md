# Nodeflow: Node-Based ANN Machine Learning Platform

A Python-based visual machine learning platform for building and experimenting with **ANN workflows using a node-based interface**.

The platform allows users to preprocess datasets, perform feature engineering and feature selection, train Artificial Neural Networks, and visualize model outputs through connected nodes.

## Features

- Data preprocessing
- Feature engineering
- ANN model training
- Feature selection using **RReliefF**
- Model interpretability using **SHAP**
- Visualization of training and prediction results
- Modular node-based workflow
- Inference
- Hyperparameter tuning

## Workflow

```text
Dataset
   ↓
Preprocessing
   ↓
Feature Engineering
   ↓
Feature Selection
   ↓
ANN Training
   ↓
Evaluation & Visualization

```

## Nodes:
![Nodes1](images/Nodes1.png)
![Nodes2](images/Nodes2.png)

# Working ANN Node tree
### This is an example of a complete ANN training node tree along with results and Scatter Plots:

![Nodetree](images/ss1.png)
![Nodetree](images/ss2.png)
![Nodetree](images/ss3.png)

# Other Screenshots:
### This is an example of using RReliefF node to determine feature importance:
![Nodetree](images/ss4.png)

# Status:
🚧 Under Development

## Current Work status:
- Trying to Fix Various UI issues (help needed 🥹)
- Trying to implement new systems other than just ANN like segmentation (semantic and instance), depth estimation, mask actions (combining masks of segmentation and depth estimation for example)
- Main goal currently is to implement a few nodes like:
  1. Camera node
  2. LLM node (to inference ollama models locally and potentially chain them)
  3. VLM node (same as llm but for image input, may use a general llm node with toggle options for selecting image input ot text input)
  4. prompt node (to give input prompts (system and user prompts) for the llm node)

# Current progress:
- Prompt node is completed
