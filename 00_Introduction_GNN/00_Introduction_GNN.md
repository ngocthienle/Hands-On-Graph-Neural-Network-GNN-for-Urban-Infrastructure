# Module 0: Introduction to Graph Neural Networks and Training Workflow

## Objective
Provide learners with a hands‑on introduction to building a simple Graph Neural Network (GNN) in PyTorch Geometric, covering graph creation, model construction, training loop, evaluation metrics, and plotting training/evaluation curves.

## 1. Topic Content
- **Graph basics**: nodes, edges, features, adjacency
- **PyTorch Geometric Data object**: attributes x, edge_index, y
- **Model architecture**: simple two-layer GCN
- **Training loop**: forward pass, loss computation, backward pass, optimizer step
- **Evaluation**: MAE, RMSE, accuracy (for classification)
- **Visualization**: plot loss curve, metric curves, example predictions vs. ground truth
  
## 2. Code Workflow
### Conda environment setup
```bash
conda create -n gnn_intro python=3.8
conda activate gnn_intro
pip install torch torch-geometric networkx matplotlib scikit-learn
```
### Synthetic graph creation
Generate a toy graph with 100 nodes, random edges, and synthetic node features and labels.
### Data object construction
Build edge_index tensor and feature/label tensors.
### Model definition
Define a simple two-layer GCNConv model class.
### Training loop
Train for 50 epochs, record train loss each epoch.
### Evaluation
Compute metrics on a held‑out test set (e.g., MAE/RMSE for regression or accuracy for classification).
### Plotting metrics
Use matplotlib to draw training loss curve and test metric curve.