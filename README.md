# awesome-heterogeneity

An awesome collection of sources regarding breaking the heterogenity of complex systems.
This heterogenity can be discovered in 3 axese:
- Horizontal axis: Components (features of dataset or subsets of features)
- Vertical axis: Subgroups (samples or subsets of samples)
- Time


## Overview, Taxonomy and Surveys

| Year | Title | Paper | Code | Category |
| ---- | ------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------- | ---- | ------------- |
| 2023 |Causal Discovery from Temporal Data: An Overview and New Perspectives              | [Link](http://arxiv.org/abs/2303.10112)             ||Components + Time
| 2020 |A survey of pattern mining in dynamic graphs              | [Link](http://arxiv.org/abs/2303.10112)             |      |Components + Time
| 2024 |A Comprehensive Survey on Community Detection With Deep Learning              | [Link](https://ieeexplore.ieee.org/abstract/document/9732192)             |      |Components
| 2022 |Comparing algorithms for characterizing treatment effect heterogeneity in randomized trials              | [Link](https://onlinelibrary.wiley.com/doi/full/10.1002/bimj.202100337)             |      | Subgroups


## Time axis
| Year | Title | Paper | Code | Category |Represention
| ---- | ------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------- | ---- | ------------- | --------|
| 2020 |Multivariate Time Series Clustering and its Application in Industrial Systems              | [Link](https://www.tandfonline.com/doi/full/10.1080/01969722.2019.1691851)             || Time| Variable Order Markov Model
| 2003 |Finding recurrent sources in sequences              | [Link](https://dl.acm.org/doi/10.1145/640075.640091)             || Time| -
| 2020 |Adaptively constrained dynamic time warping for time series classification and clustering              | [Link](https://www.sciencedirect.com/science/article/pii/S0020025520303054?via%3Dihub)             ||Time| distances between trajectories
| 2021 |Clustering-based anomaly detection in multivariate time series data              | [Link](https://www.sciencedirect.com/science/article/pii/S1568494620308577?via%3Dihub)             || Time|  Squared Euclidean distance between a multivariate subsequence
| 2021 |Multivariate time series clustering based on complex network              | [Link](https://www.sciencedirect.com/science/article/pii/S0031320321001060?via%3Dihub)             || Time| Transition network






## Horizontal axis
| Year | Title | Paper | Code | Category |Description|
| ---- | ------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------- | ---- | ------------- | -----|
| 2022 |Discovery of Extended Summary Graphs in Time Series              | [Link](https://proceedings.mlr.press/v180/assaad22a.html)             |[Code](https://github.com/ckassaad/PCGCE)|Components + time | Constraint Based Causal graph
| 2020 |Discovering contemporaneous and lagged causal relations in autocorrelated nonlinear time series datasets              | [Link](https://proceedings.mlr.press/v124/runge20a.html)             |[Code](https://github.com/jakobrunge/tigramite)|Components + Time | Constraint Based Causal graph
| 2021 |High-recall causal discovery for autocorrelated time series with latent confounders              | [Link](https://arxiv.org/abs/2007.01884)             |[Code](https://github.com/jakobrunge/tigramite)|Components + time | Constraint Based Causal graph without sufficiency assumption
| 2020 |DYNOTEARS: Structure Learning from Time-Series Data              | [Link](https://arxiv.org/abs/2002.00498)             |[Code](https://github.com/ckassaad/causal_discovery_for_time_series)|Components + Time | Score Based (Continuous Optimization) Causal graph



## Vertical axis
| Year | Title | Paper | Code | Category |Description|
| ---- | ------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------- | ---- | ------------- | ----|
| 2022 |Causal Interaction Trees: Finding Subgroups with Heterogeneous Treatment Effects in Observational Data             | [Link](https://academic.oup.com/biometrics/article/78/2/624/7460035?login=true)| [Code](https://github.com/jiabei-yang/CIT) |Components + Subgroups| Causal Interaction Trees
| 2022 |Unsupervised machine learning for the discovery of latent disease clusters and patient subgroups using electronic health records             | [Link](https://www.sciencedirect.com/science/article/pii/S1532046419302849)| |Components + Subgroups| Poisson Dirichlet Model 
| 2022 |Robust subgroup discovery             | [Link](https://link.springer.com/article/10.1007/s10618-022-00856-x#Sec41)|[Code](https://github.com/HMProenca/RuleList) | Subgroups| Minimum Description Length
| 2022 |Anytime Subgroup Discovery in High Dimensional Numerical Data             | [Link](https://ieeexplore.ieee.org/document/9564223)| | Subgroups + Time| Monte Carlo Tree Search





