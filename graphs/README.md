## August 2023

- [x] **Link Prediction Based on Graph Neural Networks. (NeurIPS18)**
    + Link existence prediction has been based on handcrafted heuristics: eg. CN, PA (1-hop neighbors), AA, AR (2-hop neighbors), etc (Table 3). Introducing a new framework aims to unifying different heuristics by learning, which is based on gamma-decay theory. In addition, this removed the needs of using high-order heuristics for the task.
    + Heuristics belong to a generic framework, *graph structure features* (structural features), located inside the **observed** node and edges features, can be directly computed from the graph.  
    + Link prediction happens on *local enclosing subgraphs*, not on entire graphs. A new framework, namely SEAL permits to further incoporate *latent* and *explicit* node features. Thus SEAL includes a 3-component node information matrix: structural node labels, node embeddings, and node attributes, which are largely **orthogonal** each other.
    + Arcodding to the authors: 
        > Graph structure features are *inductive*, meaning that these features are not associated with a particular
        node or network. This is in contrast to latent features, which are often *transductive* – the changing of network
        structure will require a complete retraining to get the latent features again. (page 12).

        > Latent features, obtained by factorizing the adjacency matrix of the laplacian one, focus more on global properties and long range effects, cannot capture structural smililarities between nodes, and transductive. 

        > Explicit features are often given by continuous or discrete node attribute vectors. 
    + Propsed **DRNL** for node labeling, which  islatter used as structural features. The model backend is built on Deep Graph Convolutationl Neural Network (DGCNN).
    
- [x] **Graph Neural Network for Link Prediction with Subgraph Sketching. (ICLR23)**
    + Solved the node automorphic problem where two node are automorphic have the same representation due to equivariant permutation GNNs.
    + Used subgraph sketching to augument node features, which solved the node automorphic problem. In addition, the subgraph sketching extracted features can be
    incorporated into standard message passing for propagation.

- [ ] **Equivariant and Stable Positional Encoding for More Powerful Graph Neural Networks. (ICLR22)**


## July 2023

- [ ] Exploring Chemical Space with Score-based Out-of-distribution Generation

- [ ] Graph Generation with Destination-Predicting Diffusion Mixture.

- [x] Multiresoluation Equivariant Graph Variational AutoEncoder.

- [ ] Hierarchical Generation of Molecular Graphs using Structural Motifs. ()

- [ ] SetVAE: Learning Hierarchical Composition for Generative Modeling of Set-Structured Data. (CVPR21)

- [x] Accurate Learning of Graph Representations with Graph Multiset Pooling. (ICLR21) [Link](https://drive.google.com/file/d/1yB30VT9W_h25T3XbA8PEx8zk85OqBD2a/view?usp=sharing)

- [ ] Neural Structured Prediction for Inductive Node Classification. (ICLR22)

- [ ] Equivariant Subgraph Aggregation Networks. (ICLR22)

- [ ] Evaluation Metrics for Graph Generative Models: Problem, Pitfalls, and Practical Solucations. (ICLR22)

- [ ] A Unifying Framework for Spectrum-Preserving Graph Sparsification and Coarsening. (NeurIPS19)

- [ ] Graph Coarsening with Neural Networks. (ICLR21)

- [ ] Spectral Sparsification of Graphs.

- [ ] Attention-based Transformation from Latent Features to Point Clouds.

- [ ] Learning Representations and Generative Models for 3D Point Clouds. (ICML18)

- [x] TOP-N: Equivariant Set and Graph Generation without Exchangeability. (ICLR22)

- [x] GG-GAN: A Geometric Graph Generative Adversarial Network. (21)

## June 2023

- [ ] LION: Latent Point Diffusion Models for 3D Shape Generation. (NeurIPS22) 

- [ ] Graph Contrastive Learning with Augmentations. (NeurIPS22)

- [ ] Latent Graph Inference using Product Manifolds.(ICLR23) 

- [ ] Differentiable Graph Module (DGM) for Graph Convolutional Networks. (22)

- [ ] Riemannian Score-Based Generative Modelling (NeurIPS22)

- [ ] Hyperbolic Graph Convolutional Neural Networks (NeurIPS19) [Talk](https://www.youtube.com/watch?v=8_BOxvdMqsA&ab_channel=AIPursuitbyTAIR)

- [ ] Hyperbolic Graph Neural Networks (NeurIPS19)

- [ ] Graph Domain Adaptation via Theory-Grounded Spectral Regularizazion.(ICLR23) 

- [ ] MOLE-BERT: Rethinking Pre-training Graph Neural Networks for Molecules.(ICLR23)