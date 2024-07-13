This repository shows a use case of Graph Machine Learning for Casino Industry Marketing: Customer Segmentation

 Step 0_accesing azure datalake: notebok to azure datalake and create the parquet file that merges all blobs. It uses Azure SDK to access the blobs.

 Step 1_graph_construction_and_metrics: notebook that create the Graph (nodes and edges) and explore the metrics : degree centrality, Betweenness centrality, Closeness centrality, EigenCentrality tod escribe the topology of the graph. Basically, NetworkX python  package  is used for the creation, manipulation, and study of the structure, dynamics, and functions of complex networks.

Step 2_knowledge_graphml_node2vec: it uses node2vec to get node embeddings. These nodes embeddings represent only the topology of the network.

Step 3_gnn_geometric_pytorch: GNN with geometric pytorch using node embeddings from previous notebook plus node features and egde features (edge weights)  

Step 4_clustering_using_node_embeddings: using KMeans, it uses the node embeddings from geometric pytorch to cluser them and get the expected market segmentation.


