# Composite Inpainting #
### Addressing Shortcomings in GAN and Patch-Based Inpainting with a Hybrid Approach ###
Authors: __Maria Alejandra Escalante__, __Kai Zhu__

This repository contains the source code of all tested inpainting and composition methods, as well as image test and result sets. The results can be found in examples folder

## Stable Diffusion
`stable_diffusion.ipynb`: Jupyter notebook used to generate stable diffusion inpainted results

## Multiscale Patch Nearest-Neighbor
`multiscale_pnn.ipynb`: Generates patch-only inpainted results using our multiscale patch nearest-neighbor method (based on GPNN and patchmatch)

## Refinement Patch Nearest-Neighbor
`refinement_pnn.ipynb`: Generates patch-GAN fusion results by processing coarse-GAN output with two-stage patchmatch to enhance GAN-generated structures with patch textures

## Blending methods
`blending_methods.ipynb`: Generates hybrid results by using both high pass filters and Gabor filters. Also used to run Deep fill gan results and join the final figuires together
