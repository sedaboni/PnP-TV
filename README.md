# Plug-and-Play gradient-based denoisers applied to CT image enhancement

### [Paper (arXiv)](https://arxiv.org/abs/2102.07510) | [Paper (ResearchGate)](https://www.researchgate.net/publication/349335536_Plug-and-Play_gradient-based_denoisers_applied_to_CT_image_enhancement)

# Abstract
Blur and noise corrupting Computed Tomography (CT) images can hide or distort small but important details, negatively affecting the diagnosis. In this paper, we present a novel gradient-based Plug-and-Play algorithm, constructed on the Half-Quadratic Splitting scheme, and we apply it to restore CT images. In particular, we consider different schemes encompassing external and internal denoisers as priors, defined on the image gradient domain. The internal prior is based on the Total Variation functional. The external denoiser is implemented by a deep Convolutional Neural Network (CNN) trained on the gradient domain (and not on the image one, as in state-of-the-art works). We also prove a general fixed-point convergence theorem under weak assumptions on both internal and external denoisers. The experiments confirm the effectiveness of the proposed framework in restoring blurred noisy CT images, both in simulated and real medical settings. The achieved enhancements in the restored images are really remarkable, if compared to the results of many state-of-the-art methods.

## Image Deblurring and Denoising
<img src="figs/synthetic.png" width="700px"/> 

# Citing
Please, consider to cite this preprint if you find it helpful.

