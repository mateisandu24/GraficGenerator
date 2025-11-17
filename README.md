# Fake News Dynamics Simulation

## Economic Cybernetics – Network & Information Flow Modeling

This project simulates the spread of fake news vs. its correction in a social network using principles from Economic Cybernetics, including agent-based behavior, network analysis, and information-flow dynamics.

**Implementation and code are available in the GitHub repository:** [mateisandu24/GraficGenerator](https://github.com/mateisandu24/GraficGenerator)

## Academic Foundation

This project is based on the research paper:

**"Modeling the spread of fake news on Twitter"**
- **Authors:** Murayama T., Wakamiya S., Aramaki E., Kobayashi R.
- **Journal:** PLOS ONE, Vol. 16, Nr. 4 (2021)
- **DOI:** [https://doi.org/10.1371/journal.pone.0250419](https://doi.org/10.1371/journal.pone.0250419)

The paper proposes a mathematical model for describing the spread of false information on Twitter through a probabilistic approach based on point-process models. The model assumes that fake news propagation occurs in two stages:

1. **Initial Phase** – The information behaves as normal news, with users redistributing the content
2. **Correction Phase** – After a certain period ("correction time"), some users identify the news as false and begin spreading corrective information

This research formed the theoretical foundation for the thesis work in Economic Cybernetics.

## Overview

The simulation models a directed, weighted network of agents representing social-media users.

### Two Phases Generated

- **Spread Phase** – diffusion of a fake news item
- **Correction Phase** – diffusion of verifying or clarifying information

The structure is inspired by two-stage diffusion models in literature (fake news → corrective reaction).

## Network Models

### 1. Stochastic Network

A randomly generated graph showing natural, chaotic diffusion:

- 20 nodes, 56 edges
- Moderate density and clustering
- One connected component

**Visualizations include:**
- Network graph
- Histograms
- Timeline
- Wordclouds

### 2. Deterministic Network

A logical, controlled structure:

- One fake-news source node
- One correction node
- Lower density and clustering
- Designed to illustrate clean, causal propagation paths

**Analysis:** Both networks are exported as CSV and analyzed with Cytoscape to compute metrics such as path length, clustering, diameter, and density.

## Economic Cybernetics Significance

- Demonstrates emergent behavior from local agent interactions
- Models disturbance (fake news) and feedback correction as cybernetic processes
- Shows how network structure influences information propagation

**Connects directly to themes in Economic Cybernetics:**
- Regulation
- Stability
- Information flows
- Non-linear diffusion

## ⚠️ Disclaimers

- All data is fully simulated
- The political scenario is fictional and used only as an academic example
- No real social-media data (Twitter, TikTok, etc.) was collected or analyzed
- Indicators (intensity, decay, correction time) are illustrative, not fitted to real events
- Work is developed strictly for educational use in the Economic Cybernetics curriculum

## Conclusion

The project provides a compact demonstration of how fake news and corrective information propagate differently through a network. It illustrates how cybernetic concepts—feedback, disturbance, regulation—can be visualized using agent-based and graph-based simulations.
