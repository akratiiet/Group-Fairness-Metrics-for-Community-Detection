# Group Fairness Metrics for Community Detection Methods in Social Networks

[de Vink, E., Saxena, A.: Group fairness metrics for community detection methods in social networks (2024).](https://arxiv.org/abs/2410.05487)

## Files
**generate_networks.py**: Generates LFR benchmark networks

**set_communities.py**: Applies community detection methods to network data

**get_results.py**: Calculates fairness metric Phi for size, density, and conductance

**create_figures.py**: gathers results, creates figures

**my_module.py**: Helper functions

**main.py**: Shows example of LFR network generation, CDM application, calculating the fairness metric Phi and creation of figures showing the results.

## Data folders
**data**: network data in csv files showing ground-truth communities in 'networkname_nodes.csv' and edge adjacency list in 'networkname_edges.csv'

**data_applied_methods**: same as **data** but with community assignments by the community detection methods

**results**: contains fairness metric Phi and performance values

**figures**: contains figures displaying the results

<img src="https://github.com/user-attachments/assets/3a772113-8d1a-43e1-8a2a-2e3c0a78847d" alt="football_size_Phi_FCCN" width="450">

Example of fairness analysis for the football network regarding size with FCCN as the community-wise performance metric.
