# Sparti: Bayesian Nonparametric Space Partition methods
A toolbox of Bayesian nonparametric space partition methods. We provide implementations of Sparti methods as follows:

- Rectangular Bounding Process(https://github.com/sparti-ml/Sparti/tree/main/Github_RelationalModel_RBP_upload)
    
    This method uses "bounding" strategy to directly generate boxes in a product space and is able to reduce modelling on sparse and noisy regions.
    
    Related paper: Xuhui Fan, Bin Li, Scott A. Sisson. “Rectangular Bounding Process”. The 32nd Conference on Neural Information Processing Systems (NeurIPS-18) 

- Network embedding for node classification, link prediction and node retrieval, etc.

    This task provides a network, and contains the following steps:
    
    1. Each node is represented as the hashcode;  
    2. Pairwise hamming similarity calculation between the hashcodes;  
    3. Hamming-similarity-based node classification, link prediction and node retrieval, etc.

    We provide the following algorithms:
    
    - [NetHash](https://github.com/drhash-cn/graph-hashing/tree/main/nethash). Wei Wu, Bin Li, Ling Chen, Chengqi Zhang. (2018). Efficient Attributed Network Embedding via Recursive Randomized Hashing. Proceedings of the 27th International Joint Conference on Artificial Intelligence. 2861-2867.
    - [#GNN](https://github.com/drhash-cn/graph-hashing/tree/main/hash-gnn). Wei Wu, Bin Li, Chuan Luo and Wolfgang Nejdl. (2021). Hashing-Accelerated Graph Neural Networks for Link Prediction. Proceedings of the 30th Web Conference. 2910-2920.
    - [#GNN+](https://github.com/drhash-cn/graph-hashing/tree/main/hash-gnn-plus). 
