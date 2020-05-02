# dynmaic-anomalies-in-graph-network
Lits about anomalies detection in dynamic graph network

## Notion
Since I can't figure out what is important in this huge lobby network, I'd like to let algorithm to find what something unusual happens. This is the main reason I am getting here. 

## Anomalies
sudden (dis)appearance of large dense directed graph

## Lits
### 2019
Graph Level Anomaly Detection http://web.stanford.edu/class/cs224w/project/26424135.pdf
- one step edge completion problems for graph representation learning
- The goal is that in learning to predict masked out graph features on a particular graph class, when presented an anomalous class our model will flag anomalous structures as unlikely "completions" based on the normal distribution.

### 2018
SPOTLIGHT https://www.cs.cmu.edu/~deswaran/papers/kdd18-spotlight.pdf

## Indirect Lits
### 2017
GraphSage: Inductive representation learning on large graphs 
https://cs.stanford.edu/people/jure/pubs/graphsage-nips17.pdf

### This topic is related to the graph representation learning, i.e., whole graph embedding
Ideally, we should be able to use these graph level embeddings for anomaly detection by comparing different embeddings against each other. Unsupervised inductive whole-graph embedding by preserving graph proximity

#### Graph level likelihood prediction
For a given graph \G, we can estimate the likelihood of that graph, \P(G), with GraphRNNs and GRANs. 

(Both are efficient graph generation with graph recurrent attention networks)

- Graphrnn: Generating realistic graphs with deep auto-regressive models
- GRAN: Efficient graph generation with graph recurrent attention networks
