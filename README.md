# awesome-protein-representation-learning

This repository contains a list of papers on the **Protein Representation Learning (PRL)**, we categorize them based on their published years. We will try to make this list updated. If you found any error or any missed paper, please don't hesitate to open issues or pull requests.


# Papers on Protein Design

## Year 2023

### 1. Modeling Interaction


- #### mutation effect for protein-protein interaction
  - [NIPS 2023]**Predicting a Protein’s Stability under a Million Mutations**[[paper]](https://arxiv.org/pdf/2310.12979)
  - [NIPS 2023]**Predicting mutational effects on protein-protein binding via a side-chain diffusion probabilistic model**[[paper]](https://arxiv.org/abs/2310.19849)

 
- #### interaction between protein and ligands
  - [NIPS 2023]**FABind: Fast and Accurate Protein-Ligand Binding**[[paper]](https://arxiv.org/abs/2310.06763)
  - [NIPS 2023]**Unsupervised Protein-Ligand Binding Energy Prediction via Neural Euler's Rotation Equation**[[paper]](https://arxiv.org/abs/2301.10814)
  - [NIPS 2023]**DrugCLIP: Contrastive Protein-Molecule Representation Learning for Virtual Screening**[[paper]](https://arxiv.org/abs/2310.06367)
  - [ICML 2023]**Learning Subpocket Prototypes for Generalizable Structure-based Drug Design**[[paper]](https://openreview.net/forum?id=gfdK6nK8AI)
  - [NIPS 2023]**Functional-Group-Based Diffusion for Pocket-Specific Molecule Generation and Elaboration**[[paper]](https://arxiv.org/abs/2306.13769)
 
- #### interaction between sequence and structure
  - [NIPS 2023]**Protein Design with Guided Discrete Diffusion**[[paper]](https://arxiv.org/abs/2305.20009)

 
- #### interaction between protein and protein
  - [NIPS 2023]**AVIDa-hIL6: A Large-Scale VHH Dataset Produced from an Immunized Alpaca for Predicting Antigen-Antibody Interactions**[[paper]](https://arxiv.org/abs/2306.03329)
  

  

  

### 2. Hierarchical structure modeling


- [NIPS 2023]**Pre-Training Protein Encoder via Siamese Sequence-Structure Diffusion Trajectory Prediction**[[paper]](https://arxiv.org/abs/2301.12068)
- [NIPS 2023]**Disentangled Wasserstein Autoencoder for T-Cell Receptor Engineering**[[paper]](https://arxiv.org/abs/2210.08171)
- [NIPS 2023]**Full-Atom Protein Pocket Design via Iterative Refinement**[[paper]](https://arxiv.org/abs/2310.02553)
- [NIPS 2023]**Graph Denoising Diffusion for Inverse Protein Folding**[[paper]](https://arxiv.org/abs/2306.16819)






- #### side chain comptability
  - [NIPS 2023]**DiffPack: A Torsional Diffusion Model for Autoregressive Protein Side-Chain Packing**[[paper]](https://arxiv.org/abs/2306.01794)
 
- #### protein docking
  - [NIPS 2023]**SyNDock: N Rigid Protein Docking via Learnable Group Synchronization**[[paper]](https://arxiv.org/abs/2305.15156)

- #### using MSA
  - [NIPS 2023]**OpenProteinSet: Training data for structural biology at scale**[[paper]](https://arxiv.org/abs/2308.05326)

- #### full-atom modeling
  - [ICML 2023]**End-to-End Full-Atom Antibody Design**[[paper]](https://openreview.net/forum?id=zAXusLf6R8)

- #### co-design of amino acid sequences and three-dimensional structures
  - [ICML 2023]**AbODE: Ab initio antibody design using conjoined ODEs**[[paper]](https://openreview.net/forum?id=EB5unD2ojL)
 
- #### protein backbone
  - [ICML 2023]**Generating Novel, Designable, and Diverse Protein Structures by Equivariantly Diffusing Oriented Residue Clouds**[[paper]](https://openreview.net/forum?id=4Kw5hKY8u8)

### 3. Decoding Strategy

- #### for protein sequence
  - [NIPS 2023]**Protein Design with Guided Discrete Diffusion**[[paper]](https://arxiv.org/abs/2305.20009)

- #### for bidirection mapping
  - [ICML 2023]**Bidirectional Learning for Offline Model-based Biological Sequence Design**[[paper]](https://openreview.net/forum?id=CUORPu6abU)


- #### using LLM for prtein sequence encoding decoding
  - [ICML 2023]**Reprogramming Pretrained Language Models for Antibody Sequence Infilling**[[paper]](https://openreview.net/forum?id=K2gn1WiLAu)
  - [NIPS 2023]**Exploring evolution-aware & -free protein language models as protein function predictors**[[paper]](https://arxiv.org/abs/2206.06583)
 

- #### diffusion model
   - [ICML 2023]**Exploring Chemical Space with Score-based Out-of-distribution Generation**[[paper]](https://openreview.net/forum?id=WP07wAWxty)
 
- #### improve the robusity of the sequence design
  - [ICML 2023]**Importance Weighted Expectation-Maximization for Protein Sequence Design**[[paper]](https://arxiv.org/abs/2305.00386)
  - [ICML 2023]**Extrapolative Controlled Sequence Generation via Iterative Refinement**[[paper]](https://openreview.net/forum?id=EuUeVUS6UV)
  - [NIPS 2023]**ProteinNPT: Improving Protein Property Prediction and Design with Non-Parametric Transformers**[[paper]](https://openreview.net/forum?id=AwzbQVuDBk)
  - [NIPS 2023]**Building datasets and benchmarks for deep learning on protein structures**[[paper]](https://openreview.net/pdf?id=27vPcG4vKV)
  - [NIPS 2023]**PoET: A generative model of protein families as sequences-of-sequences**[[paper]](https://arxiv.org/abs/2306.06156)
  - [NIPS 2023]**ProteinGym: Large-Scale Benchmarks for Protein Fitness Prediction and Design**[[paper]](https://proceedings.neurips.cc/paper_files/paper/2023/file/cac723e5ff29f65e3fcbb0739ae91bee-Paper-Datasets_and_Benchmarks.pdf)
  - [NIPS 2023]**CELL-E 2: Translating Proteins to Pictures and Back**[[paper]](https://www.biorxiv.org/content/10.1101/2023.10.05.561066v1)
  - [ICML 2023]**Importance Weighted Expectation-Maximization for Protein Sequence Design**[[paper]](https://arxiv.org/abs/2305.00386)



- #### converting coarse-grained (CG) protein representations back into detailed all-atom representations
  - [ICML 2023]**Chemically Transferable Generative Backmapping of Coarse-Grained Proteins**[[paper]](https://openreview.net/forum?id=7DnvWyVkUo)
 

- #### a benchmark helps us to understand
  - [NIPS 2023]**PEER: A Comprehensive and Multi-Task Benchmark for Protein Sequence Understanding**[[paper]](https://arxiv.org/abs/2206.02096)


- #### bench mark for geomotry representation study
   - [NIPS 2023]**Symmetry-Informed Geometric Representation for Molecules, Proteins, and Crystalline Materials**[[paper]](https://arxiv.org/abs/2306.09375)
 
- #### 
  




