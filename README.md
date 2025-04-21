# Hands-On Graph Neural Netowrk (GNN) for Urban Infrastructure
 This is a hands-one tutorial for students to start learning about Graph Neural Network (GNN) and utlizling the GNN for networks in Urban Infrastructure.


## Module 0: Introduction to Graph Neural Networks and Training Workflow
### 1. Objective:
Provide learners with a hands‑on introduction to building a simple Graph Neural Network (GNN) in PyTorch Geometric, covering graph creation, model construction, training loop, evaluation metrics, and plotting training/evaluation curves.

### 2. Key concepts
- Graph basics: nodes, edges, features, adjacency
- PyTorch Geometric Data object: attributes x, edge_index, y
- Model architecture: simple two-layer GCN
- Training loop: forward pass, loss computation, backward pass, optimizer step
- Evaluation: MAE, RMSE, accuracy (for classification)
- Visualization: plot loss curve, metric curves, example predictions vs. ground truth

## Module 1: Urban Road Network Analysis with GNNs
### 1. Topic Content
**Objective**: Learn to model an urban road network as a graph and apply GNNs for traffic‑flow prediction and anomaly detection.
### 2. Key Concepts:
- Graph representation (nodes = intersections, edges = road segments)
- Spatial features (road length, speed limit, connectivity)
- Time‑series node features (historical traffic volume/speed)
- GNN architectures: GCN, Graph Attention Networks (GAT)
### 3. Use Cases:
- Short‑term traffic forecasting
- Detecting congestion anomalies
- Evaluating network resilience under link failures

## Module 2: Urban Water‑Supply Network Modeling with GNNs
### 1. Topic Content
**Objective**: Represent a water distribution network as a graph to predict pressure/flow and detect leaks.
### 2. Key Concepts:
- Graph (nodes = junctions, reservoirs; edges = pipes)
- Hydraulic features (pipe diameter, length, roughness)
- Sensor data (pressure, flow rates, valve statuses)
- GNN tasks: regression (pressure forecasting), classification (leak detection)
### 3. Use Cases:
- Forecasting low‑pressure events
- Early leak detection
- Network segmentation for maintenance

## Module 3: Urban Waste‑Water Network Analysis with GNNs
### 1. Topic Content
**Objective**: Use GNNs on a sewer network graph to predict flow overloads and detect blockages.
### 2. Key Concepts:
- Graph (nodes = manholes, treatment plants; edges = sewer pipes)
- Dynamic features (inflow, outflow, rainfall input)
- GNN tasks: sequence modeling (spatio‑temporal GNN), anomaly detection
### 3. Use Cases:
- Predicting surcharge under heavy rainfall
- Identifying likely blockage locations
- Optimizing cleaning routes