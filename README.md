# Mutual information regulariser implementation
# for [Information Bottlenecked Variational Autoencoder for Disentangled 3D Facial Expression Modelling](https://openaccess.thecvf.com/content/WACV2022/html/Sun_Information_Bottlenecked_Variational_Autoencoder_for_Disentangled_3D_Facial_Expression_Modelling_WACV_2022_paper.html)

## Abstract

Learning a disentangled representation is essential to build 3D face models that accurately capture identity and expression. We propose a novel variational autoencoder (VAE) framework to disentangle identity and expression from 3D input faces that have a wide variety of expressions. Specifically, we design a system that has two decoders: one for neutral-expression faces (i.e. identity-only faces) and one for the original (expressive) input faces respectively. Crucially, we have an additional mutual-information regulariser applied on the identity part to solve the issue of imbalanced information over the expressive input faces and the reconstructed neutral faces. Our evaluations on two public datasets (CoMA and BU-3DFE) show that this model achieves competitive results on the 3D face reconstruction task and state-of-the-art results on identity-expression disentanglement. We also show that by updating to a conditional VAE, we have a system that generates different levels of expressions from semantically meaningful variables.

For citation:
```
@InProceedings{Sun_2022_WACV,
    author    = {Sun, Hao and Pears, Nick and Gu, Yajie},
    title     = {Information Bottlenecked Variational Autoencoder for Disentangled 3D Facial Expression Modelling},
    booktitle = {Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)},
    month     = {January},
    year      = {2022},
    pages     = {157-166}
}
```
