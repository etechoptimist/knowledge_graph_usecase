This repository shows a use case of Graph Machine Learning for Casino Industry Marketing: Customer Segmentation

 Step_0: notebok to azure datalake and create the parquet file that merges all blobs

 Step_1: notebook that create the Graph (nodes and edges) and explore the metrics : degree centrality, Betweenness centrality, Closeness centrality, EigenCentrality tod escribe the topology of the graph

 Step 2: it use node2vec to get node embeddings. These nodes embeddings represent only the topology of the network.

 Step 3: GNN with geometric pytorch using node enbeddings from previous notebook plus node features and egde features (edge wieghts)  