## Problems

Download the _email-Eu-core_ directed network from the SNAP dataset repository available at http://snap.stanford.edu/data/email-Eu-core.html.

### 1 Number of nodes

### 2 Number of edges

### 3 In-degree, out-degree and degree of the first five nodes

### 4 Number of source nodes

### 5 Number of sink nodes

### 6 Number of isolated nodes

### 7 In-degree distribution

### 8 Out-degree distribution

### 9 Average degree, average in-degree and average out-degree

### 10 Distance between five pairs of random nodes

### 11 Shortest path length distribution

### 12 Diameter

### 13 Is the graph strongly connected? If so, compute the strongly connected component size distribution

### 14 Is the graph weakly connected? If so, compute the weakly connected component size distribution

### 15 Number of bridge edges

### 16 Number of articulation nodes

### 17 Number of nodes in In(v) for five random nodes

### 18 Number of nodes in Out(v) for five random nodes

### 19 Clustering coefficient for five random nodes

### 20 Clustering coefficient distribution

### 21 Average clustering coefficient

---

## Concepts

### 1.17 Clustering Coefficient

The clustering coefficient of a vertex $i$ in a graph $G(V, E)$, denoted by $C_{i}$, gives what portion of $i$'s neighbours are connected. Formally, the clustering coefficient is as given in Eq. 1.24
$$C_{i} = \frac{2e_{i}}{k_{i}(k_{i} - 1)} \in [0, 1]  \tag{1.24}$$

### 1.18 Average Clustering Coefficient

The average clustering coefficient of a graph $G(V, E)$, denoted by $C$, is defined as the average of the clustering coefficients of all the vertices $v \in V$. Formally, the average clustering coefficient is given by
$$C = \frac{1}{|V|} \sum_{i}|V|C_{i} \tag{1.25}$$
