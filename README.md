# ProteinDiffusionGenerator
## Generative method to design novel proteins using an attention-based diffusion model

#### Model A: Design based on overall secondary structure content
#### Model B: Design based on per-residue secondary structure features

Reference: B. Ni, D.L. Kaplan, M.J. Buehler, Generative design of de novo proteins based on secondary structure constraints using an attention-based diffusion model, Chem, 2023

![TOC_small](https://user-images.githubusercontent.com/101393859/225438367-3fc51d61-bef3-4fc8-9511-092d0ea84fc7.png)

### Summary

We report a generative deep learning model that predicts amino acid sequences and 3D protein structures based on secondary structure design objectives. Two models are presented; first, a model that produces solutions based on overall fractional content of secondary structure (Model A). Second, a model that produces solutions based on residue-level secondary structure design objectives that facilitate more precise structural control (Model B). Both approaches offer de novo design capacity as they can discover new protein sequences not yet invented (or known) from natural mechanisms or systems. However, we find that the residue-level secondary structure design model generally yields higher accuracy with respect to the design parameters, and also produces de novo sequences that share only limited similarity with existing proteins.  These findings suggest unexplored opportunities for new protein designs and functional outcomes within the vast, unexplored amino acid sequences beyond known proteins. Our models, based on an attention-based diffusion model and trained on a dataset extracted from known 3D protein structures, offers numerous downstream applications in conditional generative design of various biological or engineering systems. Future work may include additional conditioning, and an exploration of other functional properties of the generated proteins for various properties beyond structural objectives. 

### The Bigger Picture

The design of de novo protein sequences has great potential in achieving superior combinations of novel functions and mechanical properties beyond known, natural proteins. However, the tremendous number of possible sequences and the cost of experimental testing make the effective search and validation of superior de novo protein candidates extremely challenging. Here, we leverage a diffusion model-based deep learning framework to efficiently generate novel protein sequences that meet desired secondary structure fractional content or type sequences. The generated sequences show novelty beyond existing, natural ones. By generating various novel sequences with the desired structural features robustly, our model provides rapid avenues for target-guided de novo protein design that leads to novel discoveries of superior protein materials for various biological and engineering applications. The method can be extended, in future work, to other chemical synthesis problems and design scenarios.

## Installation and use

This code requires that OmegaFold be installed:

```
pip install git+https://github.com/HeliXonProtein/OmegaFold.git
```

Two Jupyter notebooks are included in this repository that feature the two models.

Model A: ProteinDiffusionGenerator_Model_A.ipynb

Model B: ProteinDiffusionGenerator_Model_B.ipynb

## Pretrained model weights

Model A:

Early stopping: https://www.dropbox.com/s/mz4afbfs0da4vb2/Model_A_early.pt?dl=0

Final: https://www.dropbox.com/s/r79cf7uo80z3v15/Model_A_final.pt?dl=0

Model B:

https://www.dropbox.com/s/vr1laqe2rpsj6ip/Model_B_final.pt?dl=0 
