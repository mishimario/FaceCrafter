<div align="center">

<h1>FaceCrafter: Identity-Conditional Diffusion with Disentangled Control over Facial Pose, Expression, and Emotion</h1>

  <p style="font-weight: bold; font-size: 1.1em;">
    Kazuaki Mishima<sup>1</sup>, Antoni Bigata Casademunt<sup>2</sup>, Stavros Petridis<sup>2</sup>, Maja Pantic<sup>2</sup>, Kenji Suzuki<sup>1</sup>
  </p>
  <p>
    <sup>1</sup>Institute of Science Tokyo &nbsp;&nbsp;|&nbsp;&nbsp; <sup>2</sup>Imperial College London
  </p>

  <h3>BMVC 2025</h3>


<div style="text-align: center;">
<a href="https://arxiv.org/abs/xxxx.xxxxx">
  <img src="images/arxiv-logomark@2x.png" width="5%" style="text-decoration: none; display: block;">
</a> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://github.com/username/repo">
  <img src="images/github-mark.png" width="7%">
</a>
</div>

</div>


---

## Abstract

<div align="center">
  <img src="images/overview.png" alt="FaceCrafter" width="800">
</div>

Human facial images encode a rich spectrum of information, encompassing both stable identity-related traits and mutable attributes such as pose, 
expression, and emotion. While recent advances in image generation have enabled high-quality identity-conditional face synthesis, precise control 
over non-identity attributes remains challenging, and disentangling identity from these mutable factors is particularly difficult. 
To address these limitations, we propose a novel identity-conditional diffusion model that introduces two lightweight control modules 
designed to independently manipulate facial pose, expression, and emotion without compromising identity preservation. 
These modules are embedded within the cross-attention layers of the base diffusion model, enabling precise attribute control with minimal parameter overhead. 
Furthermore, our tailored training strategy, which leverages cross-attention between the identity feature and each non-identity control feature, 
encourages identity features to remain orthogonal to control signals, enhancing controllability and diversity. 
Quantitative and qualitative evaluations, along with perceptual user studies, demonstrate that our method surpasses existing approaches 
in terms of control accuracy over pose, expression, and emotion, while also improving generative diversity under identity-only conditioning.

---


## Citation
```bibtex
@article{mishima2025facecrafter,
  title={FaceCrafter: Identity-Conditional Diffusion with Disentangled Control over Facial Pose, Expression, and Emotion},
  author={Mishima, Kazuaki and Casademunt, Antoni Bigata and Petridis, Stavros and Pantic, Maja and Suzuki, Kenji},
  journal={arXiv preprint arXiv:2505.15313},
  year={2025}
}



