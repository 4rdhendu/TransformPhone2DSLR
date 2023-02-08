# TransformPhone2DSLR
**Transform your Smartphone into a DSLR Camera: Learning the ISP in the Wild** [[Paper]](https://arxiv.org/abs/2203.10636)

# Abstract
We propose a trainable Image Signal Processing (ISP) framework that produces DSLR quality images given RAW images captured by a smartphone. To address the color misalignments between training image pairs, we employ a color-conditional ISP network and optimize a novel parametric color mapping between each input RAW and reference DSLR image. During inference, we predict the target color image by designing a color prediction network with efficient Global Context Transformer modules. The latter effectively leverage global information to learn consistent color and tone mappings. We further propose a robust masked aligned loss to identify and discard regions with inaccurate motion estimation during training. Lastly, we introduce the ISP in the Wild (ISPW) dataset, consisting of weakly paired phone RAW and DSLR sRGB images. We extensively evaluate our method, setting a new state-of-the-art on two datasets.

# Proposed Framework

![TransformPhone2DSLR](https://github.com/4rdhendu/TransformPhone2DSLR/blob/main/overview.png)

# Results

For quantitative and qualitative results refer to the paper.  

# Code will be released soon

Star this project to get notified.
