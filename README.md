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
- **论文来源** : 2019CVPR ;
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


#### 2020年6月23号

#### 苏志翔
- **论文名字** : TEA: Temporal Excitation and Aggregation for Action Recognition ;
- **论文来源** : ICCV2019 ;
- **代码地址** : 还没发布 ; 
- **方法简称** : TEA ;
- **方法方向** : 显著性检测 ;
- **快速获取** : 暂时没有 ;

| 方法介绍 |
| :-------- |
| 时态建模是视频动作识别的关键。它通常既考虑短期的移动，也考虑长期的聚集。在本文中，我们提出了一个时间激发和聚集(TEA)模块，包括一个运动激发(ME)模块和一个多时间聚集(MTA)模块，专门设计来捕获短期和长期的时间演化。特别是对于短程运动建模，ME模块从时空特征计算特征级的时间差异。然后，它利用这些差异来激发特征的动作敏感通道。在以往的工作中，长期的时间聚合通常是通过叠加大量的局部时间卷积来实现的。每次卷积处理一个局部时间窗口。相比之下，MTA模块提出将局部卷积变形为一组子卷积，形成层次化残差结构。在不引入附加参数的情况下，对特征进行一系列的子卷积处理，每一帧可以完成多个邻域的时间聚合。最终的时间维的等效感受域被相应地扩大，从而能够在远帧上建立长期的时间关系。茶块的两个组成部分在时态建模中是互补的。最后，我们的方法在几个行动识别基准上取得了令人印象深刻的结果，例如Kinetics, Something-Something, HMDB51，和UCF101，这证明了它的有效性和效率。 |

#### 王鑫鑫
- **论文名字** : Skeleton-Based Action Recognition with Directed Graph Neural Networks ;
- **论文来源** : 2019CVPR ;
- **代码地址** : [连接](https://github.com/kenziyuliu/Unofficial-DGNN-PyTorch) 或者 https://github.com/kenziyuliu/Unofficial-DGNN-PyTorch ;
- **方法简称** : DGNN ;
- **方法方向** : 行为骨骼识别 ;
- **快速获取**
```powershell
git clone https://github.com/TiantianWang/ICCV17_SRM.git
```
