# 2018_CXY
> 本仓库的目的是用来呈现 2018 年中国地质大学（武汉）信息工程学院 IPISP 实验室本科生团队产学研项目，项目的周报以及每个阶段的代码都会上传到此仓库中，欢迎有兴趣的朋友进行技术上的交流以及对我们项目当中存在的问题及时在 issue 中，由于项目成员都是第一次做 research 项目，因此如果有什么做的不好的地方就请各位大佬多多指教啦。

## Group 1
### 项目负责人：

- 杨子曦

### 项目成员：

- 易琪
- 马崧誉

### 项目开始时间：

以第一次组会时间为项目正式开始时间即 2018/11/8
### 项目主要内容：

复杂自然场景图像自动标注，通过分析和复现 2016 CVPR 论文 "Show attend and tell" 来实现自己的自然场景图像自动标注。该论文的复现大致可以分成三个部分 

-  预处理图像和 encoding 部分 
-  attend 部分主要使用 soft attention 模型
-  decoding 部分生成对应的词语

### 可参考的其他论文有：
- "Deep visual-semantic alignments for generating image descriptions."（2015）
- "Show and Tell: Lessons Learned from the 2015 MSCOCO Image Captioning Challenge."（2016）
- "Guiding Long-Short Term Memory for Image Caption Generation."（2015）
- "What Value Do Explicit High Level Concepts Have in Vision to Language Problems?."（2016）
- "Show, Attend and Tell: Neural Image Caption Generation with Visual Attention." （2015）
- "Knowing When to Look: Adaptive Attention via A Visual Sentinel for Image Captioning."（2016）
- "SCA-CNN: Spatial and Channel-wise Attention in Convolutional Networks for Image Captioning."（2016）
- "Bottom-Up and Top-Down Attention for Image Captioning and Visual Question Answering."（2017）
- "Neural Baby Talk."（2018）

### 参考以及使用数据集：
- Flickr8k
- Flick30k
- MSCOCO

### 网络模型：
- gLSTM 解决了图像仅在开始时传入 LSTM 的问题
- att-LSTM 仅传入全局特征的问题
- SCA-CNN 从之前解码层使用 RNN 换成 CNN

### MileStone：
- 第一阶段 读懂复现论文 2018/12/31 之前
- 第二阶段 复现论文 2019/1/1～2019/2/28
- 第三阶段 总结复现过程 2019/4/1～2019/4/8
- 第四阶段 提升复现过程 2019/4/9～2019/5/15
- 第五阶段 编写相关论文 2019/5/16～2019/6/1

---