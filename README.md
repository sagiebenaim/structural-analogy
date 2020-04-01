# Structural-analogy from a Single Image Pair

### [Sagie Benaim](https://sagiebenaim.github.io/), [Ron Mokady](mailto:ron.mokady@gmail.com), [Amit Bermano](https://www.cs.tau.ac.il/~amberman/), [Daniel Cohen-Or](https://www.cs.tau.ac.il/~dcor/), [Lior Wolf](https://www.cs.tau.ac.il/~wolf/)

![teaser](https://github.com/sagiebenaim/structural-analogy/blob/master/images/teaser.png)

## Abstract

The task of unsupervised image-to-image translation has
seen substantial advancements in recent years through the use of deep
neural networks. Typically, the proposed solutions learn the characterizing
distribution of two large, unpaired collections of images, and are able
to alter the appearance of a given image, while keeping its geometry
intact. In this paper, we explore the capabilities of neural networks to
understand image structure given only a single pair of images, A and
B. We seek to generate images that are structurally aligned : that is,
to generate an image that keeps the appearance and style of B, but
has a structural arrangement that corresponds to A. The key idea is to
map between image patches at different scales. This enables controlling
the granularity at which analogies are produced, which determines the
conceptual distinction between style and content. In addition to structural
alignment, our method can be used to generate high quality imagery in
other conditional generation tasks utilizing images A and B only: guided
image synthesis, style and texture transfer, as well as text translation.
Our code will be made publicly available.

## Paper

Our paper, indlucing results from the supplementary material, is available [here](link}

## Code

Pytorch implementation of our work is available [here](link)

## Videos

As detailed in of the paper, we provide translation results here :, where only a single frame is present in the target. 

![balloons2birds](https://github.com/sagiebenaim/structural-analogy/blob/master/images/birds.gif)

![fire2stone](https://github.com/sagiebenaim/structural-analogy/blob/master/images/volcano.mp4)

