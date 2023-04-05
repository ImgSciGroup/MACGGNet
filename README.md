# MACGGNet
Abstract
Learning performance is unsatisfactory when training deep-learning networks without prior-knowledge guidance. In this paper, a multi-scale change detection neural network guided by a change gradient image (CGI) was proposed. First, a multiscale information attentional module was embedded in the backbone of UNet to achieve a multiscale information fusion task of bi-temporal images. Second, the position channel attention module was promoted to make the neural network pay more attention to the spectral and spatial information in the multiscale fused feature map. Finally, a change gradient guide module was proposed to optimize backpropagation and overcome the negative effects of pseudo-change. Compared with seven state-of-the-art methods using three pairs of real remote sensing images, the proposed approach could smoothen the salt-and-pepper noise from the detection maps and improve the detection accuracy. The quantitative improvement is about 1.67% and 3.00% in terms of overall accuracy and Kappa coefficient, respectively, thus confirming the feasibility and superiority of the proposed approach for detecting land cover change with remotely sensed images.
MACGGNet
The MACGGNet is designed to learn and predict change maps from bi-temporal images with remote sensing images.
Requirements
Python 3.6
Pytorch 1.2.0
Q & A
For any questions, please contact Zhongpingdong_Mal@hotmail.com，Lvzhiyong_fly@hotmail.com.
