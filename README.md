# Regularization in medical image registration
This repo serves as a code resource for different regularization techniques applied in medical image registration.
For more information see the paper:

🕮 **From Model Based to Learned Regularization in Medical Image Registration: A Comprehensive Review** (Reithmeir et al., 2025, in review). Available on [arXiv](https://arxiv.org/abs/2412.15740).

Feel free to contact me if you think there is something missing or you want to collaborate!

![Alt text](figs/overview.png "overview")
***
![Alt text](figs/model-based.png "model-based")
## Model-based regularization ✨
 ℹ️ Model-based regularization applies a global, user-defined model on the deformation. 

**global smoothness**

**local discontinuities**

**inverse consistency and cycle consistency**

**local invertibility**

**volume preservation**

**diffeomorphisms**

**physics-inspired properties**

***
![Alt text](figs/problem-specific.png "problem-specific")
## Problem-specific regularization ✨
ℹ️ Problem-specific regularization is tailired towards the data by taking additional data knowledge into account. It is often spatially-adaptive.

**multi-structure registration**

**images with topology changes**
- **missing regions**
- **shrinking/growing regions**

**organ-specific motion**

- **sliding motion**
- **cyclic motion**
***
![Alt text](figs/learned.png "learned")
## learned regularization ✨
ℹ️ Learned regularization uses ML/DL models to learn spatially-adaptive deformation properties from a training dataset.

**learned local smoothness properties**

**learned feasible deformation spaces**

**test time adaptive regularization**
***