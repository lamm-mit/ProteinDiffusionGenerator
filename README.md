# ProteinDiffusionGenerator
Generative method to design novel proteins using a diffusion model

Reference: B. Ni, D.L. Kaplan, M.J. Buehler, Generative design of de novo proteins based on secondary structure constraints using an attention-based diffusion model, Chem, 2023

Summary

We report two generative deep learning models that predict amino acid sequences and 3D protein structures based on secondary structure design objectives in either overall sequence- or detailed residue-level. Both models are robust regarding imperfect inputs and offer de novo design capacity as they can discover new protein sequences not yet discovered from natural mechanisms or systems. And the residue-level secondary structure design model generally yields higher accuracy and more novel sequences. These findings suggest unexplored opportunities for new protein designs and functional outcomes within the vast amino acid sequences beyond known proteins. Our models, based on an attention-based diffusion model and trained on a dataset extracted from known 3D protein structures, offer numerous downstream applications in conditional generative design of various biological or engineering systems. Future work may include additional conditioning, and an exploration of other functional properties of the generated proteins for various properties beyond structural objectives.

The Bigger Picture

The design of de novo protein sequences has great potential in achieving superior combinations of novel functions and mechanical properties beyond known, natural proteins. However, the tremendous number of possible sequences and the cost of experimental testing make the effective search and validation of superior de novo protein candidates extremely challenging. Here, we leverage a diffusion model-based deep learning framework to efficiently generate novel protein sequences that meet desired secondary structure fractional content or type sequences. The generated sequences show novelty beyond existing, natural ones. By generating various novel sequences with the desired structural features robustly, our model provides rapid avenues for target-guided de novo protein design that leads to novel discoveries of superior protein materials for various biological and engineering applications. The method can be extended, in future work, to other chemical synthesis problems and design scenarios.
