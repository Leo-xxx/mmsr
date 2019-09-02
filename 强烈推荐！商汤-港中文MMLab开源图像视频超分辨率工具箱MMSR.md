## 强烈推荐！商汤-港中文MMLab开源图像视频超分辨率工具箱MMSR

原创： CV君 [我爱计算机视觉](javascript:void(0);) *5天前*

点击我爱计算机视觉标星，更快获取CVML新技术

------



![img](https://mmbiz.qpic.cn/mmbiz_png/BJbRvwibeSTvB3yhCnvsROG2dSrRmh9CXSsd4d5nOIOQdRFS5OSH0qrrClGr4yO6dknZfgGjoAyNrdNGK8Wk3KA/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



近一年，图像视频超分辨率突然变得异常火热，各大AI巨头和新锐均在发力。



52CV曾经第一时间报道了在今年CVPR 2019上 [商汤EDVR算法获NTIRE 2019 视频恢复比赛全部四项冠军，代码将开源！](http://mp.weixin.qq.com/s?__biz=MzIwMTE1NjQxMQ==&mid=2247486964&idx=1&sn=b3a2c61bc518944547f6d46ed8787b37&chksm=96f37fa0a184f6b6e317b89d159a05da09b9f283dd18dd3e8945655965e34ba3a0d2256810af&scene=21#wechat_redirect)



EDVR代表着该领域的顶尖水平，商汤之前已将其开源。



近日，MMLab整合近两年的研究成果（BasicSR, ESRGAN,  EDVR）开源了图像视频超分辨率工具箱MMSR，再一次引起不少朋友的关注。





代码链接：

https://github.com/open-mmlab/mmsr



**该工具箱亮点：**



\1. 统一的框架。虽然取名MMSR，但其并不仅仅限于超分辨率任务，该库能够很容易地适应其他底层视觉的任务，比如去噪(denoise)，去模糊(deblurring)等。



\2. 先进的算法。MMSR目前包括PIRM18冠军模型ESRGAN, NTIRE19的冠军模型EDVR，并且还支持了图像超分的SRResNet和SRGAN(有改动)的训练和测试，视频超分的DUF和TOF的测试，并在持续开发中，作者称后续会支持更多的模型。



\3. 容易拓展。作者称无论是改模型结构、数据处理、损失函数还是训练方式，在该库都非常容易尝试新的研究算法。



MMLab开源了不少含有state-of-the-art算法的工具箱：

[OpenMMLab的新篇章](http://mp.weixin.qq.com/s?__biz=MzIwMTE1NjQxMQ==&mid=2247487339&idx=3&sn=d46a15c5aded6b2307f9c070a3a2fb28&chksm=96f37d3fa184f42901188e6651ac3cebe96eeb22882bb6a96f632af8308717874c2eda6b2dc6&scene=21#wechat_redirect)


  