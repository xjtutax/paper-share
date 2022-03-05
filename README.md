# paper-share
本项目是记录西安交通大学天地网实验室税务大数据小组线下论文分享会的文档，记录内容主要包括论文原文、分享ppt。

## 知识图谱

### 扁平实体识别
名字  | 发表  | 简介 | 分享人 | 原文 | 代码
 ---- | ----- | ------ | ------ | ------ | ------ 
 CGN  | EMNLP 2019 | 提出协作图网络捕获词典信息 |张浩堃|[paper](https://aclanthology.org/D19-1396/) |[code](https://github.com/DianboWork/Graph4CNER) 
 Simple-Lexicon  | ACL 2020 | 简化Lattice-LSTM的结构  | 赵子涵 | [paper](https://aclanthology.org/2020.acl-main.528/) | [code](https://github.com/v-mipeng/LexiconAugmentedNER) 
 LR-CNN  | IJCAI 2019 | 提出了带有rethinking机制的基于CNN的方法来合并词汇  | 王凯 | [paper](https://www.ijcai.org/proceedings/2019/692) | [code](https://github.com/guitaowufeng/LR-CNN) 
 FLAT  | ACL 2020 | 基于Transformer无损引入词汇信息及融合词汇信息动态结构  | 张载 | [paper](https://arxiv.org/abs/2004.11795) | [code](https://github.com/LeeSureman/Flat-Lattice-Transformer) 
 
### 嵌套/非连续实体识别
名字  | 发表  | 简介 | 分享人 | 原文 | 代码
 ---- | ----- | ------ | ------ | ------ | ------ 
 ARNs  | ACL 2019 | 利用实体的头部驱动短语结构识别嵌套实体  | 张载 | [paper](https://aclanthology.org/2020.acl-main.528/) | [code](https://github.com/sanmusunrise/ARNs) 
 MLC  | Anonymous ACL2022 submission | 基于Multi-LSTM-CRF的级联二分类模型，一次识别一种类型  | 武乐飞 | [paper](https://openreview.net/forum?id=cL4tgY1ZxS) | 暂无 
 HIT  | EMNLP 2020  | 利用头尾对和令牌交互序列完成实体分类，降低复杂度  | 王凯 | [paper](https://aclanthology.org/2020.emnlp-main.486/) | 暂无
 Triaffine  | Arxiv预发布 | 提出了triaffine mechanism三仿射变换机制，融合多种异质信息 |武乐飞|[paper](https://arxiv.org/abs/2110.07480) | 暂无
 sodner  | ACL 2021 | 使用RE的思路同时识别嵌套和不连续实体 |张浩堃|[paper](https://aclanthology.org/2021.acl-long.372.pdf) | [code](https://github.com/foxlf823/sodner)
 
 ### 统一命名实体识别
 名字  | 发表  | 简介 | 分享人 | 原文 | 代码
 ---- | ----- | ------ | ------ | ------ | ------ 
 BARTNER  | ACL 2021 | 将实体识别建模为序列生成任务，基于指针生成网络构建了一个统一的命名实体识别框架  | 武乐飞 | [paper](https://arxiv.org/abs/2106.01223) | [code](https://github.com/yhcc/BARTNER) 
 
 ### 句子级关系抽取
 名字  | 发表  | 简介 | 分享人 | 原文 | 代码
 ---- | ----- | ------ | ------ | ------ | ------ 
 CasRel  | ACL 2020 | 解决三元组重叠  | 张宇航 | [paper](https://aclanthology.org/2020.acl-main.136/) | [code](https://github.com/weizhepei/CasRel) 
 
 ###  篇章级/文档级关系抽取
 名字  | 发表  | 简介 | 分享人 | 原文 | 代码
 ---- | ----- | ------ | ------ | ------ | ------ 
 GAIN  | EMNLP 2020 | 提出一种图聚合和推理网络用于文档级的关系抽取  | 赵子涵 | [paper](https://aclanthology.org/2020.emnlp-main.127/) | [code](https://github.com/DreamInvoker/GAIN) 
 Paths  | ACL 2021 | 启发式地选择有用的句子进行关系抽取  | 张宇航 | [paper](https://arxiv.org/abs/2106.01793) | [code](https://github.com/AndrewZhe/Three-Sentences-Are-All-You-Need) 
 
 ###  实体关系联合抽取
 名字  | 发表  | 简介 | 分享人 | 原文 | 代码
 ---- | ----- | ------ | ------ | ------ | ------ 
 PURE  | NAACL 2021 | 使用了一种pipeline而非joint的方式超越了以前的模型  | 武乐飞 | [paper](https://aclanthology.org/2021.naacl-main.5/) | [code](https://github.com/princeton-nlp/PURE) 
 
 ###  互补标签学习
 名字  | 发表  | 简介 | 分享人 | 原文 | 代码
 ---- | ----- | ------ | ------ | ------ | ------ 
 LM  |  ECCV 2018 Oral | 提供了一种无偏地估计转移概率的方法  | 吴雨萱 | [paper](https://arxiv.org/abs/1711.09535) | 暂无
 GAN-CL  | IEEE 2021 | 利用生成对抗机制来提高从互补标签学习的性能  | 吴雨萱 | [paper](https://ieeexplore.ieee.org/document/9489374) | 暂无 
 
 
 ## 图神经网络