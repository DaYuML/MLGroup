# 欢迎使用组会报告

@(from)[马克飞象|帮助|Markdown]

**组会报告**记录每一次的组会的PPT报告和相应论文以及相应的github代码地址。
 
- **命名方式** ：日期+汇报者+论文名字；
- **论文来源** ：日期+会议或者期刊；
- **代码来源** ：记录下github地址即可，重要的代码可以git clone 到本地 命名方式(日期+汇报者+论文名字)。

-------------------



## 2020年
> 一般采用学期制，上半年学期就是春季，暑期是夏季（7月1号-8月31号），下半年学期就是冬季（毕竟合肥没有秋天嘛）

正如您在阅读的这份文档，它使用简单的符号标识不同的标题，将某些文字标记为**粗体**或者*斜体*，创建一个[链接](http://www.example.com)或一个脚注[^demo]。下面列举了几个高级功能，更多语法请按`Ctrl + /`查看帮助。 

### 2020春季

#### 2020年6月16号

#### 曾凡晨
- **论文名字** : Skeleton-Based Action Recognition with Directed Graph Neural Networks ;
- **论文来源** : 2019CVPR;
- **代码地址** : [连接](https://github.com/kenziyuliu/Unofficial-DGNN-PyTorch) 或者 https://github.com/kenziyuliu/Unofficial-DGNN-PyTorch ;
- **方法简称** : DGNN ;
- **方法方向** : 行为骨骼识别 ;
- **快速获取** :
```powershell
git clone https://github.com/TiantianWang/ICCV17_SRM.git
```

| 方法介绍 |
| :-------- |
| 在这项工作中，我们根据人体关节和骨骼之间的运动相关性，将骨骼数据表示为有向无环图 (DAG)。设计了一种新的有向图神经网络，用于提取关节、骨骼及其相互关系的信息，并根据提取的特征进行预测。另外，为了更好地适应动作识别任务，在训练过程的基础上，对图的拓扑结构进行了自适应(Adaptive)，使其得到了显著的改进。在双流框架下，利用骨架序列的运动信息，结合空间信息，进一步提高性能。|



#### 吕祥杰
- **论文名字** : A Stagewise Refinement Model for Detecting Salient Objects in Images ;
- **论文来源** : 2017ICCV ;
- **代码地址** : [链接](https://github.com/TiantianWang/ICCV17_SRM) 或者 https://github.com/TiantianWang/ICCV17_SRM ; 
- **方法简称** : SRM ;
- **方法方向** : 显著性检测 ;
- **快速获取** : 
```powershell
git clone https://github.com/kenziyuliu/Unofficial-DGNN-PyTorch.git
```

| 方法介绍 |
| :-------- |
| 深度卷积神经网络(CNNs)已经成功地应用于计算机视觉中的各种问题，包括显著目标检测。为了准确地检测和分割显著性目标，需要同时提取和结合高级语义特征和低级精细细节。这对CNNs来说是一个挑战，因为多次的子采样操作，如pooling和convolution，会导致初始图像分辨率明显降低，导致空间细节的丢失和更精细的结构。为了解决这一问题，我们提出了一种新的金字塔pooling模块和多阶段显著性检测细化机制来增强前馈神经网络。首先，利用我们的深度馈向网络生成一个粗略的预测图。 |
