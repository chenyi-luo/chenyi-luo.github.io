---
layout: default
---

My research develops fully coupled models and efficient numerical algorithms to facilitate a through understanding of natural phenomena and engineering activities. Typical applications include hydraulic fracturing and desiccation cracks. 


### Phase-field modeling of fracturing _saturated_ porous media with application to hydraulic fracturing

To describe the coupling among fractured solid, crack propagation, and the flow, I embedded the phase-field approach for brittle fracture into the Theory of Porous Media. The developed model allows an accurate description of an autonomous transformation of pore-fluid to bulk fluid as a crack propagates. Furthermore, I introduced a crack opening indicator to transform bulk fluid back to pore-fluid in a closed crack so that the reversible flow transformation is compatible with the irreversible cracking phenomena. The model has been implemented for three-dimensional simulation of hydraulic fracturing processes.

<img src="/resources/hf-sample.jpg" width=200px> <img src="/resources/hf3d.gif" width=245px>

### Phase-field modeling of fracturing _unsaturated_ porous media with application to desiccation cracks

To simulate fracturing unsaturated porous media, e.g., the desiccation cracking, I investigated the behaviors of different material models considering cases when cracks are driven either by the effective-stress or the total stress. I examined the second-order stability condition of the proposed material model, which explains why the homogeneous solution bifurcates into a periodic solution and localization occurs in the numerical implementation without any deficiencies. I further introduced two saturation definitions to adapt the standard van Genuchten equation to the fractured unsaturated soil. The model is found to qualitatively agree with an experimentally observed increase in evaporation rate after crack generation. 

<img src="/resources/dc.gif" width=400px>

### Phase-field models with directional strain decomposition and crack-opening indicator for pre-cracks under shear loading

In rain-fall induced slope failure, pre-cracks and shear deformation play important roles. I realized that the standard phase-field model fails to describe the behaviors of pre-cracked solids under both compression and shear loads. Hence, I solved this problem by using the crack-opening indicator concept along with a newly introduced directional strain decomposition for detecting the crack state under complex stress states. This completed my phase-field model for saturated porous media. 

### Fast staggered schemes for phase-field facture models

For three dimensional simulation of fracture problems, I developed fast staggered schemes which can dramatically improve the computation efficiency. 


See the preprint: Luo, C., 2022. Fast staggered schemes for the phase-field model of brittle fracture based on the fixed-stress concept. arXiv preprint arXiv:2209.07969. ([pdf](https://arxiv.org/pdf/2209.07969.pdf))
