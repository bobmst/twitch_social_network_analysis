# Twitch EN Social Collaboration Network Analysis Project

This repository contains the code for analyzing the social collaboration network of English users on the live streaming platform Twitch. The project employs social network analysis techniques to uncover insights about the network structure, community dynamics, and influential nodes within the Twitch ecosystem.

## Project Overview

The primary goal of this project is to explore the Twitch English User's Social Collaboration Network (SCN) through social network analysis (SNA). By leveraging network analysis methods, we aim to understand the digital interactions that shape the Twitch community, identify distinct user communities, and evaluate the influence of network metrics on content creation and audience engagement. 

## Dataset

The project utilizes the Twitch Social Networks dataset from Stanford, which includes edge data (`musae_ENGB_edges.csv`) representing connections between streamers and target data (`musae_ENGB_target.csv`) containing metadata about each streamer, such as their streaming days, mature content flag, viewership counts, and partnership status.
Link to the dataset: [SNAP: Network datasets: Wikipedia Article Networks (stanford.edu)](https://snap.stanford.edu/data/twitch-social-networks.html)

## Analysis Approach

1. **Data Preparation and Initial Analysis**: Load the edge and target data, construct a directed graph representing the Twitch network, and perform initial network visualization.
2. **Network Analysis**: Calculate degree distribution, centrality measures (degree, closeness, and betweenness), and geodesic distances to understand the network's structural properties.
3. **Community Detection and Clustering**: Identify distinct communities within the network using hierarchical clustering techniques and analyze inter-cluster and intra-cluster connectivity patterns.
4. **Reduced Network Construction**: Create a reduced graph representation of the network at the cluster level to visualize the community structure.
5. **Research Problems**: Address key research problems, including the influence of network structure on content creation and audience engagement, identification of influential nodes, and community dynamics.

## Repository Structure

- `twitch_en_network - Copy.ipynb`: The Jupyter Notebook containing the Python code for data preprocessing, network analysis, and community detection.
- `data/`: Directory containing the Twitch network dataset files.
- `result/`: Directory for storing intermediate and final analysis results.

## Dependencies

The project primarily utilizes the following Python libraries:

- NetworkX
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
