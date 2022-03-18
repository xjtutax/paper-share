# paper-share
本项目是记录西安交通大学天地网实验室税务大数据小组线下论文分享会的文档，记录内容主要包括论文原文、分享ppt。

## 知识图谱

[相关论文阅读列表](https://github.com/xjtutax/paper-share/blob/main/%E7%9F%A5%E8%AF%86%E5%9B%BE%E8%B0%B1/%E8%AE%BA%E6%96%87%E9%98%85%E8%AF%BB%E5%88%97%E8%A1%A8.md)

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
 W2NER  | AAAI 2022 | 提出一种新的词-词关系分类结构,该方法通过对实体边界标识和实体词之间的相邻关系进行有效建模，解决了统一的NER问题  | 张浩堃 | [paper](https://arxiv.org/pdf/2112.10070.pdf) | [code](https://github.com/ljynlp/w2ner) 

### 句子级关系抽取

 名字  | 发表  | 简介 | 分享人 | 原文 | 代码
 ---- | ----- | ------ | ------ | ------ | ------ 
 CasRel  | ACL 2020 | 解决三元组重叠  | 张宇航 | [paper](https://aclanthology.org/2020.acl-main.136/) | [code](https://github.com/weizhepei/CasRel) 
 QA-based | 2021 | 附加验证模型来提升关系抽取性能 | 王凯 | [paper](https://arxiv.org/abs/2104.02934) | [NO code，PPT](https://github.com/xjtutax/paper-share/blob/main/%E7%9F%A5%E8%AF%86%E5%9B%BE%E8%B0%B1/%E5%8F%A5%E5%AD%90%E7%BA%A7%E5%85%B3%E7%B3%BB%E6%8A%BD%E5%8F%96/%E7%8E%8B%E5%87%AF-3-18-%E8%AE%BA%E6%96%87%E5%88%86%E4%BA%AB.pptx)
 ###  篇章级/文档级关系抽取
 名字  | 发表  | 简介 | 分享人 | 原文 | 代码
 ---- | ----- | ------ | ------ | ------ | ------ 
 GAIN  | EMNLP 2020 | 提出一种图聚合和推理网络用于文档级的关系抽取  | 赵子涵 | [paper](https://aclanthology.org/2020.emnlp-main.127/) | [code](https://github.com/DreamInvoker/GAIN) 
 Paths  | ACL 2021 | 启发式地选择有用的句子进行关系抽取  | 张宇航 | [paper](https://arxiv.org/abs/2106.01793) | [code](https://github.com/AndrewZhe/Three-Sentences-Are-All-You-Need) 
 SSAN  | AAAI 2021 | 将实体结构依赖合并到标准的自注意力机制中  | 赵子涵 | [paper](https://arxiv.org/abs/2102.10249v1) | [code1](https://github.com/PaddlePaddle/Research/tree/master/KG/AAAI2021_SSAN), [code2](https://github.com/BenfengXu/SSAN) 

 ###  实体关系联合抽取
 名字  | 发表  | 简介 | 分享人 | 原文 | 代码
 ---- | ----- | ------ | ------ | ------ | ------ 
 PURE  | NAACL 2021 | 使用了一种pipeline而非joint的方式超越了以前的模型  | 武乐飞 | [paper](https://aclanthology.org/2021.naacl-main.5/) | [code](https://github.com/princeton-nlp/PURE) 
 TPLinker  | COLING20 | TPLinker将抽取标注框架统一为字符对链接问题，即Token Pair Linking problem,TPLinker是单阶段解码，训练和推断阶段抽取三元组不存在差异 | 张浩堃 | [paper](https://arxiv.org/pdf/2010.13415.pdf) | [code](https://github.com/131250208/TPlinker-joint-extraction) 

 ###  互补标签学习
 名字  | 发表  | 简介 | 分享人 | 原文 | 代码
 ---- | ----- | ------ | ------ | ------ | ------ 
 LM  |  ECCV 2018 Oral | 提供了一种无偏地估计转移概率的方法  | 吴雨萱 | [paper](https://arxiv.org/abs/1711.09535) | 暂无
 GAN-CL  | IEEE 2021 | 利用生成对抗机制来提高从互补标签学习的性能  | 吴雨萱 | [paper](https://ieeexplore.ieee.org/document/9489374) | 暂无 

### 相关学习与调研

| 名字                                       | 简介                      | 分享人 | 分享时间  |
| ------------------------------------------ | ------------------------- | ------ | --------- |
| Contrastive Learning and Applicationin NLP | 对比学习及其在NLP中的应用 | 武乐飞 | 2022.3.11 |



 ## 图神经网络

 ### 交通流时序预测
 名字  | 发表  | 简介 | 分享人 | 原文 | 代码
 ---- | ----- | ------ | ------ | ------ | ------ 
 ASTGCN  |  AAAI 2019 | 提出基于注意力的时空图卷积网络来解决交通流预测问题  | 雷潇靓 | [paper](https://aaai.org/ojs/index.php/AAAI/article/view/3881) | [code](https://github.com/guoshnBJTU/ASTGCN-r-pytorch)
 ### 异构图神经网络
 名字  | 发表  | 简介 | 分享人 | 原文 | 代码
 ---- | ----- | ------ | ------ | ------ | ------ 
 HetG  |  KDD 2019 | 提出HetGNN框架来解决异质图节点嵌入问题  | 王亦琛 | [paper](https://www3.nd.edu/~dial/publications/zhang_2019_heterogeneous.pdf) |  [code](https://github.com/chuxuzhang/KDD2019_HetGNN)
