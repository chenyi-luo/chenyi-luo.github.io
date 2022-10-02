---
layout: default
---

My research develops fully coupled models and efficient numerical algorithms to facilitate a through understanding of natural phenomena and engineering activities. Typical applications include hydraulic fracturing and desiccation cracks. 


### Phase-field modeling of fracturing _saturated_ porous media with application to hydraulic fracturing

To describe the coupling among fractured solid, crack propagation, and the flow, we embedded the phase-field approach for brittle fracture into the Theory of Porous Media. The developed model allows an accurate description of an autonomous transformation of pore-fluid to bulk fluid as a crack propagates. Furthermore, we introduced a crack opening indicator to transform bulk fluid back to pore-fluid in a closed crack so that the reversible flow transformation is compatible with the irreversible cracking phenomena. The model has been implemented for three-dimensional simulation of hydraulic fracturing processes.

<table>
  <tr>
  <td width="42%"><img src="/resources/hf-sample.jpg"></td>
  <td width="58%"><img src="/resources/hf3d.gif"></td>
  </tr>
</table>

The developed model is also able to accurately describe the interaction between the pre-crack and newly generated cracks. The numerical simulations are found to be consistent with experimental observations.
<table>
  <tr>
  <td width="50%"><img src="/resources/precrack.jpg"></td>
  <td width="25%"><img src="/resources/caught.gif"></td>
  <td width="25%"><img src="/resources/penetrate.gif"></td>
  </tr>
</table>

### Phase-field modeling of fracturing _unsaturated_ porous media with application to desiccation cracks

To simulate fracturing unsaturated porous media, e.g., the desiccation cracking, we investigated the behaviors of different material models considering cases when cracks are driven either by the effective-stress or the total stress. The second-order stability condition of the proposed material model was examined to explain why the homogeneous solution bifurcates into a periodic solution and localization occurs in the numerical implementation without any deficiencies. We further introduced two saturation definitions to adapt the standard van Genuchten equation to the fractured unsaturated soil. The model is found to qualitatively agree with an experimentally observed increase in evaporation rate after crack generation. 

<table>
  <tr>
  <td width="51%"><img src="/resources/desiccation.jpg"></td>
  <td width="49%"><img src="/resources/dc.gif"></td>
  </tr>
</table>


### Phase-field models with directional strain decomposition and crack-opening indicator for pre-cracks under shear loading

In rain-fall induced slope failure, pre-cracks and shear deformation play important roles. We found that the standard phase-field model fails to describe the behaviors of pre-cracked solids under both compression and shear loads. Hence, we solved this problem by using the crack-opening indicator concept along with a newly introduced directional strain decomposition for detecting the crack state under complex stress states. This completed the previously proposed phase-field model for saturated porous media. 

<table>
  <tr>
  <td width="50%"><img src="/resources/tension.gif"></td>
  <td width="50%"><img src="/resources/shear.gif"></td>
  </tr>
</table>

### Fast staggered schemes for phase-field facture models

For three dimensional simulation of fracture problems, we developed fast staggered schemes which can dramatically improve the computation efficiency. We have proposed three schemes, denoted by S1, S2, and S3. The simulation results of benchmark examples demonstrated their superior performance in terms of the accuracy and efficiency as compared to the standard staggered scheme (ST).

<p align="center">
<img src="/resources/comp.jpg" width="25%">
</p>
See the preprint: Luo, C., 2022. Fast staggered schemes for the phase-field model of brittle fracture based on the fixed-stress concept. arXiv preprint arXiv:2209.07969. ([pdf](https://arxiv.org/pdf/2209.07969.pdf))
