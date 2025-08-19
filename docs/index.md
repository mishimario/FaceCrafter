# Project Page: FaceCrafter: Identity-Conditional Diffusion with Disentangled Control over Facial Pose, Expression, and Emotion

This is the official project page for our BMVC 2025 paper:  
**"FaceCrafter: Identity-Conditional Diffusion with Disentangled Control over Facial Pose, Expression, and Emotion"**  
Kazuaki Mishima, Antoni Bigata Casademunt, Stavros Petridis, Maja Pantic, Kenji Suzuki  

📄 [Paper (arXiv)]()  
💻 [Code (GitHub)]()  

---

## Abstract
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

## Method

例:  

---

## Results

---

## Citation
@inproceedings{mishima2025facecrafter,
  title     = {FaceCrafter: Identity-Conditional Diffusion with Disentangled Control over Facial Pose, Expression, and Emotion},
  author    = {Mishima, Kazuaki and Casademunt, Antoni Bigata and Petridis, Stavros and Pantic, Maja and Suzuki, Kenji},
  booktitle = {Proceedings of the British Machine Vision Conference (BMVC)},
  year      = {2025}
}

