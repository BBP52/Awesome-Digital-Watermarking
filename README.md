# Digital Watermarking
A list of papers about Digital-Watermarking.
## Contents
- [Papers](#papers)
- [Papers2](#papers2)

## Papers
 | Title | Affiliation | Venue and Year | Methods | Merits | Demerits | Link | Database | Code |
 | ----- | ----------- | -------------- | ------- | ------ | -------- | ---- | ------ | ---- |
 | 中文水印字库的自动生成方法 | 中国科大 | 中国图象图形学报 2022 | 基于编码—解码器网络的自动生成中文字库的文档水印算法 ![Pic](https://BBP52.github.io/pic/Network_1.jpg) | 在数字传输和打印扫描场景下都具有较好的鲁棒性 | 不适用于打印拍照和屏幕拍照的场景 | [Paper](http://www.cjig.cn/html/2022/1/20220118.htm) | | |
 | A screen-shooting resilient document image watermarking scheme using deep neural network | 南大 | IET IP 2022 | 文档图像水印：DNN。编码器、译码器：U-Net style。失真层：模拟屏幕拍摄过程中的失真。一种嵌入强度调整策略 ![Pic](https://BBP52.github.io/pic/Network_2_1.jpg) | 视觉质量相比提高，而位精度损失较小 | 只针对英文文档和屏幕拍摄 | [Paper](https://ietresearch.onlinelibrary.wiley.com/doi/epdf/10.1049/ipr2.12653) | [DocImgEN](https://github.com/gslxr/Document-image-watermarking) | [code](https://github.com/gslxr/Document-image-watermarking) |
 | FontCode Embedding Information in Text Documents using Glyph Perturbation | Columbia University | TOG 2018 | 文本信息嵌入技术：设计了算法来构建字形码本和查找表，将英语文本转化为ASCII或Unicode；CNNs构造和字形识别，字体流形。特殊字形文档。 ![Pic](https://BBP52.github.io/pic/Network_3.jpg) ![Pic](https://BBP52.github.io/pic/Network_3_2.jpg) | 应用广泛、抗干扰能力强、还原过程有一定纠错能力。 | 内存大、字体限制、打印文本褶皱影响识别。 | [Paper](https://dl.acm.org/doi/10.1145/3152823) | | |
 | TERA Screen-to-Camera Image Code with Transparency, Efficiency, Robustness and Adaptability | 中国科大、南大 | TMM 2022 | Screen-to-Camera Image Code：首先对信息序列进行BCH&CRC纠错编码，然后根据颜色分解原理嵌入到图像中形成两个互补的子帧。高帧率显示（大于60Hz）。注意力机制网络进行提取。 ![Pic](https://BBP52.github.io/pic/Network_4.jpg) | 可以主动防屏幕-相机翻拍。可以用于警示水印、泄露追踪等。 | 容易受到裁剪攻击、可嵌入的信息容量不大。 | [Paper](https://ieeexplore.ieee.org/document/9362313) | [COCO](http://mscoco.org/)| |
 | Screen-Shooting Resilient Watermarking | 中国科大、南大 | TIFS 2018 | | | | [Paper](https://ieeexplore.ieee.org/document/8513859) | | |
 | Wavelet-Based CNN for Robust and High-Capacity Image Watermarking | 中大、彭城实验室 | ICME 2022 | | | | [Paper](https://ieeexplore.ieee.org/document/9859725) | | |
 | Wavelet-Based CNN for Robust and High-Capacity Image Watermarking | 中大、彭城实验室 | ICME 2022 | | | | [Paper](https://ieeexplore.ieee.org/document/9859725) | | |

## Papers2
 | Title | Affiliation | Venue and Year | Methods | Merits | Demerits | Link | Database | Code |
 | ----- | ----------- | -------------- | ------- | ------ | -------- | ---- | ------ | ---- |
 | 中文水印字库的自动生成方法 | 中国科大 | 中国图象图形学报 2022 | 基于编码—解码器网络的自动生成中文字库的文档水印算法 ![Pic](https://BBP52.github.io/pic/Network_1.jpg) | 在数字传输和打印扫描场景下都具有较好的鲁棒性 | 不适用于打印拍照和屏幕拍照的场景 | [Paper](http://www.cjig.cn/html/2022/1/20220118.htm) | | |
