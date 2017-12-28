# idea
webar-->传图-->图像检索：基于内容的检索（深度高层特征+哈希检索）推荐
1. https://imatge-upc.github.io/retrieval-2016-icmr/
2. http://imatge-upc.github.io/retrieval-2016-deepvision/
3. 团队主页： https://github.com/imatge-upc


Exploiting Local Features from Deep Networks for Image Retrieval （CVPR 2015 workshop）
这篇文章发表在CVPR 2015 workshop上，是来自于马里兰大学帕克学院Joe Yue-Hei Ng等人的工作。近期的很多研究工作表明，相比于全相连层的输出，卷积层的特征图谱（feature map）更适用于实例搜索。本篇文章介绍了如何将卷积层的特征图谱转化为“局部特征”，并使用VLAD将其编码为图像特征。另外，作者还进行了一系列的相关试验去观察不同卷积层的特征图谱对实例搜索准确率的影响。



## 图像检索
DeepFashion︱衣物时尚元素关键点定位+时尚元素对齐技术
http://blog.csdn.net/sinat_26917383/article/details/63682987

用Python和OpenCV创建一个图片搜索引擎的完整指南
http://blog.csdn.net/kezunhai/article/details/46417041

Recent Advance in Content-based Image Retrieval: A Literature Survey
https://arxiv.org/pdf/1706.06064.pdf

CVPR2015的论文《Deep Learning of Binary Hash Codes for Fast Image Retrieval》实现的海量数据下的基于内容图片检索系统，250w图片下，对于给定图片，检索top 1000相似时间约为1s 教程：http://blog.csdn.net/han_xiaoyang/article/details/50856583 源码：https://github.com/kevinlin311tw/caffe-cvprw15

Image Retrieval(CSDN)
http://m.blog.csdn.net/flowerboya/article/details/72858464

Learning Deep Representations of Fine-grained Visual Descriptions
    intro: CVPR 2016
    arxiv: http://arxiv.org/abs/1605.05395
    github: https://github.com/reedscot/cvpr2016

## 图像分类
Traffic-Sign Detection and Classification in the Wild 路标检测分类
http://cg.cs.tsinghua.edu.cn/traffic-sign/

## 图像识别
基于Tensorflow的交通标志识别 http://www.jianshu.com/p/d8feaddc7bdf  源码：https://github.com/waleedka/traffic-signs-tensorflow

## 图片语义分析
语义分析的一些方法(三) http://www.flickering.cn/ads/2015/02/%e8%af%ad%e4%b9%89%e5%88%86%e6%9e%90%e7%9a%84%e4%b8%80%e4%ba%9b%e6%96%b9%e6%b3%95%e4%b8%89/

## 细粒度的识别: Fine-grained Recognition
Fine-Grained Classification之车型识别http://m.blog.csdn.net/qq_14845119/article/details/76083042

## 图像标注/语义标注：Semantic Annotation
Image Tag Assignment, Refinement and Retrieval资源主页：
http://www.micc.unifi.it/tagsurvey/


1. 基于迁移学习与深度卷积特征的图像标注方法研究 
http://kns.cnki.net/KCMS/detail/detail.aspx?dbcode=CDFD&dbname=CDFDLAST2017&filename=1017119555.nh&uid=WEEvREcwSlJHSldRa1FhcTdWZDhMQ0V6aHdlbDJNNDFrejBiMmVQR3hIZz0=$9A4hF_YAuvQ5obgVAqNKPCYcEjKensW4ggI8Fm4gTkoUKaID8j8gFw!!&v=MjExNDIxTHV4WVM3RGgxVDNxVHJXTTFGckNVUkwyZVplZHNGQ25rVTdyQlZGMjZHYks1RjlUSnFwRWJQSVI4ZVg=
2. 基于深度学习的图像语义标注与描述研究 https://github.com/dr-weiyiming/idea/blob/master/%E5%9F%BA%E4%BA%8E%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E7%9A%84%E5%9B%BE%E5%83%8F%E8%AF%AD%E4%B9%89%E6%A0%87%E6%B3%A8%E4%B8%8E%E6%8F%8F%E8%BF%B0%E7%A0%94%E7%A9%B6_%E9%83%91%E6%B0%B8%E5%93%B2.caj



## 语义嵌入：Semantic Embedding
统一化视觉语义嵌入与多模态神经语言模型: https://segmentfault.com/a/1190000004890723

## 迁移学习
CNTK 301: Image Recognition with Deep Transfer Learning
https://cntk.ai/pythondocs/CNTK_301_Image_Recognition_with_Deep_Transfer_Learning.html
