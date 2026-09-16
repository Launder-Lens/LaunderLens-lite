# Data Visualization

This folder contains the data visualization components used in the Anti-Money Laundering (AML) detection system.

## Purpose

The visualizations are used to understand transaction patterns, account relationships, and suspicious activity in the dataset.

## Visualizations

The project includes visualizations for:

- Transaction distribution
- Normal vs. laundering transactions
- Transaction amounts
- Currency and payment formats
- Account-to-account transaction networks
- Suspicious transaction patterns
- Graph-based AML activity

## Graph Visualization

The transaction network is represented as a graph:

- **Nodes** → Bank accounts
- **Edges** → Transactions
- **Suspicious edges** → Potential laundering transactions

Graph visualization tools such as **NetworkX** and **Gephi** are used to explore relationships between accounts and identify multi-account transaction patterns.

## Tools

- Python
- Pandas
- Matplotlib
- NetworkX
- Gephi

## Folder Structure

```text
data_visualization/
├── README.md
├── plots/
├── graph_visualization/
└── scripts/
