# Digital Watermarking
A list of papers about Digital-Watermarking.
## Contents
- [Papers](#papers)
- [Papers2](#papers2)

## Papers
 | Title | Affiliation | Venue and Year | Methods | Merits | Demerits | Link | Database | Code |
 | ----- | ----------- | -------------- | ------- | ------ | -------- | ---- | ------ | ---- |
 | Kaleido You Can Watch It But Cannot Record It | 清华 | MobiCom 2015 | CIE-xyY色彩模型；人类视觉与相机拍摄的差异；色彩帧分解、照度帧污染 ![Pic](https://BBP52.github.io/pic/CIE.jpg) | 主动防翻拍、不干扰人眼观看而对视频有明显的干扰效果 | 对显示设备有较高需求，目前只针对视频 | [Paper](https://dl.acm.org/doi/10.1145/2789168.2790106) | | |
 | 中文水印字库的自动生成方法 | 中国科大 | 中国图象图形学报 2022 | 基于编码—解码器网络的自动生成中文字库的文档水印算法 ![Pic](https://BBP52.github.io/pic/Network_1.jpg) | 在数字传输和打印扫描场景下都具有较好的鲁棒性 | 不适用于打印拍照和屏幕拍照的场景 | [Paper](http://www.cjig.cn/html/2022/1/20220118.htm) | | |
 | A screen-shooting resilient document image watermarking scheme using deep neural network | 南大 | IET IP 2022 | 文档图像水印：DNN。编码器、译码器：U-Net style。失真层：模拟屏幕拍摄过程中的失真。一种嵌入强度调整策略 ![Pic](https://BBP52.github.io/pic/Network_2_1.jpg) | 视觉质量相比提高，而位精度损失较小 | 只针对英文文档和屏幕拍摄 | [Paper](https://ietresearch.onlinelibrary.wiley.com/doi/epdf/10.1049/ipr2.12653) | [DocImgEN](https://github.com/gslxr/Document-image-watermarking) | [code](https://github.com/gslxr/Document-image-watermarking) |
 | FontCode Embedding Information in Text Documents using Glyph Perturbation | Columbia University | TOG 2018 | 文本信息嵌入技术：设计了算法来构建字形码本和查找表，将英语文本转化为ASCII或Unicode；CNNs构造和字形识别，字体流形。特殊字形文档。 ![Pic](https://BBP52.github.io/pic/Network_3.jpg) ![Pic](https://BBP52.github.io/pic/Network_3_2.jpg) | 应用广泛、抗干扰能力强、还原过程有一定纠错能力。 | 内存大、字体限制、打印文本褶皱影响识别。 | [Paper](https://dl.acm.org/doi/10.1145/3152823) | | |
 | TERA Screen-to-Camera Image Code with Transparency, Efficiency, Robustness and Adaptability | 中国科大、南大 | TMM 2022 | Screen-to-Camera Image Code：首先对信息序列进行BCH&CRC纠错编码，然后根据颜色分解原理嵌入到图像中形成两个互补的子帧。高帧率显示（大于60Hz）。注意力机制网络进行提取。 ![Pic](https://BBP52.github.io/pic/Network_4.jpg) | 可以主动防屏幕-相机翻拍。可以用于警示水印、泄露追踪等。 | 容易受到裁剪攻击、可嵌入的信息容量不大。 | [Paper](https://ieeexplore.ieee.org/document/9362313) | [COCO](http://mscoco.org/)| |
 | Screen-Shooting Resilient Watermarking | 中国科大、南大 | TIFS 2018 | intensity-based scale-invariant feature transform (I-SIFT) algorithm，小尺寸模板算法插入水印，一种基于交叉验证的盲提取与重复嵌入相结合的算法：提取精度保证，BCH编码。![Pic](https://BBP52.github.io/pic/Network_5_1.jpg) | 距离鲁棒性好、水平左60°-右60°、垂直-45-60° | 提取过程慢、SIFT：仅能处理复杂纹理、不能文本 | [Paper](https://ieeexplore.ieee.org/document/8513859) | [labtiff](https://sipi.usc.edu/database/) | [code](https://gitlab.com/libtiff/libtiff) |
 | Wavelet-Based CNN for Robust and High-Capacity Image Watermarking | 中大、彭城实验室 | ICME 2022 | | | | [Paper](https://ieeexplore.ieee.org/document/9859725) | | |
 | U-Net: Convolutional Networks for Biomedical Image Segmentation | University of Freiburg | Miccai 2015 | U-Net | 允许通过重叠平铺策略对任意大的图像进行无缝分割。对大型图像的训练好，只需较少数据 | | [Paper](https://ieeexplore.ieee.org/document/9859725) | | [U-net](http://lmb.informatik.uni-freiburg.de/people/ronneber/u-net) |
 | Color constancy through inverse-intensity chromaticity space | UOT/CU | JOSAA 2004 | IIC色度特征 | 允许通过重叠平铺策略对任意大的图像进行无缝分割。对大型图像的训练好，只需较少数据 | | [Paper](https://opg.optica.org/josaa/fulltext.cfm?uri=josaa-21-3-321&id=78880) | | |
 

## Papers2
 | Title | Affiliation | Venue and Year | Methods | Merits | Demerits | Link | Database | Code |
 | ----- | ----------- | -------------- | ------- | ------ | -------- | ---- | ------ | ---- |
 | Deep Learning-based Forgery Attack on Document Images | SZU | TIP 2021 |  基于深度学习的文档图像篡改网络，并攻击现有的文档图像认证系统。ForgeNet，TENet，翻拍之前可以通过IHNet去除伪造文档图像中的半色调图案。 |  |  | [Paper](https://ieeexplore.ieee.org/document/9540787) | | |
 | Domain-agnostic document authentication against practical recapturing attacks | SZU | TIFS 2022 | |  |  | [Paper](https://ieeexplore.ieee.org/document/9851649) | | |
 | Face Spoofing Detection Based on Local Ternary Label Supervision in Fully Convolutional Networks | SZU | TIFS 2020 | |  |  | [Paper](https://ieeexplore.ieee.org/document/9056824) | | |
