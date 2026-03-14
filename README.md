# Analyzing Cultural Bias in Multilingual Wikipedia

## Overview
Wikipedia exists in hundreds of languages, but the representation of topics and people can differ significantly between language editions. This project analyzes cultural bias in multilingual Wikipedia by studying the hyperlink structure between articles and applying social network analysis techniques.

The goal is to identify how cultural perspectives influence article connectivity and topic importance across different Wikipedia language networks.

---

## Problem Statement
Different Wikipedia language editions often emphasize topics related to their own cultural or regional context. This can create bias in how knowledge is represented globally.

This project investigates:
- Whether cultural preferences influence Wikipedia link structures
- Which topics or entities become central in different language networks
- How cultural bias appears in article connectivity

Research has shown that hyperlink networks in Wikipedia can reveal cultural relationships and biases between language communities. :contentReference[oaicite:1]{index=1}

---

## Dataset
The dataset consists of Wikipedia article link networks collected from multiple language editions.

Each dataset includes:
- Article nodes
- Hyperlink connections between articles
- Language-specific article networks

---

## Technologies Used
- Python
- Pandas
- NetworkX
- Matplotlib
- Social Network Analysis

---

## Methodology
1. Collect Wikipedia hyperlink data across different language editions.
2. Represent articles as nodes and hyperlinks as edges in a network graph.
3. Apply social network analysis metrics such as:
   - Degree Centrality
   - Betweenness Centrality
   - Network Density
4. Compare network structures between language editions.
5. Identify patterns that indicate cultural bias in article linking.

---

## Results
The analysis shows that:
- Language editions tend to prioritize culturally relevant topics.
- Some articles become highly central within specific cultural contexts.
- Cross-language differences reveal how knowledge representation varies globally.

---

---

## Visualizations
Network graphs were generated to visualize article connectivity and centrality within each language edition.

Examples include:
## Metric Correlation Heatmap
![Centrality Chart](bias_analysis/occupation_corr_heatmap.png)

---

## Future Improvements
- Expand analysis to additional Wikipedia language editions
- Apply machine learning to detect bias patterns automatically
- Develop interactive network visualizations

---

## Author
Aarya  
Computer Science 
