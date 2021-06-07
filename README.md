# marginalized_graph_kernel_protein

Some important papers

* About marginalized graph kernel - the paper from ICML 2003:
https://www.aaai.org/Papers/ICML/2003/ICML03-044.pdf

* About predicting energy using GPR and marginalized graph kernel - the paper: 
https://arxiv.org/abs/1810.07310

About the database (A directory named Covid-data)

* Link to the database
https://drive.google.com/drive/folders/1wtzMcocuK8kPsz8K0ktjCZPkv567W6M2

* Number of files in this directory: 606
* Type of files in this directory: .xz
* Columns in each file:  
1. energy: total energy of a certain molecule
2. smiles: a smile string that represents that molecule
3. graphs: a graph object from [graphdot.graph.Graph](https://graphdot.readthedocs.io/en/latest/apidoc/graphdot.graph.html) that represents that molecule

* About the graph object:
1. nodes (dataframe) – each row represent a node

    Each node contains ['!i','aromatic','atomic_number','charge','chiral','hcount','hybridization','ring_list'] 
  
2. edges (dataframe) – each row represent an edge

    Each node contains ['!i', '!j', 'aromatic', 'conjugated', 'order', 'ring_stereo', 'stereo']
  
3. title (str) – a unique identifier of the graph
