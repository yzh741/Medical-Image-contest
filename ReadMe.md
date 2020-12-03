综述性的文章里面抽取这部分

病理图片中有丝分裂细胞的定位与检测

[https://www.zhihu.com/question/60067846](https://www.zhihu.com/question/60067846)

https://www.bilibili.com/video/BV16K411G71G

https://www.bilibili.com/video/BV1Za4y1v76N

---------------------------------------------------------------------------------

Frontiers in Machine Learning: Saving Lives with Interpretable ML

[https://www.microsoft.com/en-us/research/video/frontiers-in-machine-learning-saving-lives-with-interpretable-ml/](https://www.microsoft.com/en-us/research/video/frontiers-in-machine-learning-saving-lives-with-interpretable-ml/)


--------------------------------------------------------------------------------------------------------------------

[“用魔法击败魔法”？一群计算神经学家正借神经网络解释大脑](https://mp.weixin.qq.com/s?__biz=MzU2ODY2MTUwNQ==&mid=2247508438&idx=1&sn=9e50a208caf1038e427529b9905c81be&chksm=fc8862b8cbffebae22ae825b401bacc15443b4c49b4d4cae28e7d97c92ae800d147e1b652f24&mpshare=1&scene=1&srcid=1112b9owwyTP2cBtpJgT5XvG&sharer_sharetime=1605163999201&sharer_shareid=4785bcb3b8b683a4ec338cbec7cd83f4&key=091021d4f6c74a9d402cc87cbd518d341cf9be15028ba6dd7f2343d4e84c4b94ebbf8ce38f451df7f6f296e729c973d9c4ac1d35db889f177940c2ebfb46cf950a1dc622c10ae19b7af3ecd1c51ee43fd784caf54bb777f95d301877ccdee2af9eaed6dc06b4d32a50a759f9f6ad4e39310503a8a75e34b53b49cde8a8c59c5c&ascene=1&uin=MjkyNDEyNTQyNg%3D%3D&devicetype=Windows+10+x64&version=6300002f&lang=zh_CN&exportkey=A9%2BzULqE%2BNDQd73rLZULeXc%3D&pass_ticket=FIGu3tMyYqD6aGaa3AtdO2d7%2F4S7z0HuXNQY9lItYu2yh0IoDMv4W0d1zVQ7sbJ%2B&wx_header=0)




-----------------------------------------------------------------------

###分割

[https://github.com/MIC-DKFZ/nnUNet](https://github.com/MIC-DKFZ/nnUNet)


[https://nanonets.com/blog/how-to-do-semantic-segmentation-using-deep-learning/](https://nanonets.com/blog/how-to-do-semantic-segmentation-using-deep-learning/)

[https://nanonets.com/blog/semantic-image-segmentation-2020/](https://nanonets.com/blog/semantic-image-segmentation-2020/)
----------------------------------------------------------------------------------------------------------------

####简介

####研究方向

#扫描仪和WSI染色对CNN的影响

不同的组织学切片制备和染色步骤可能会导致对来自一个中心的数据进行训练的CNN无法很好地处理来自另一个中心的数据。
[Impact of rescanning and normalization on convolutional neural network performance in multi-center, whole-slide classification of prostate cancer](https://www.nature.com/articles/s41598-020-71420-0)

[ Zaneta Swiderska-Chadaj](https://www.computationalpathologygroup.eu/publications/zaneta-swiderska-chadaj/all-years/)

[Stain-transforming cycle-consistent generative adversarial networks for improved segmentation of renal histopathology](https://www.computationalpathologygroup.eu/presentations/cc-gan-renal-histopathology/)

#StreamingCNN

[StreamingCNN](https://github.com/DIAGNijmegen/StreamingCNN)

#Automatic mitosis detection in breast cancer tissue sections  有丝分裂计数对乳腺癌预后评估有帮助

手动计数组织切片中的有丝分裂肿瘤细胞
https://www.computationalpathologygroup.eu/highlights/mitosis-detection-in-he/


#Artifact detection in digitized histopathology images 伪影检测
https://www.computationalpathologygroup.eu/projects/artifact_detection/


###肿瘤间质比率（TSR）是结直肠癌和其他实体恶性肿瘤的独立预后因素。

https://www.computationalpathologygroup.eu/projects/tsr/


####肿瘤萌芽

癌症患者的个性化治疗始于对应治疗癌症的广泛评估。公众关注下一代测序作为治疗的最终选择工具。但是，幸运的是，大多数结直肠癌（CRC）患者不需要靶向治疗。荷兰对CRC人群进行筛查，加上局部治疗的改善，可防止大多数患者发生转移性疾病。

下一个挑战是如何预防对早期CRC和/或中度风险CRC的患者进行过度治疗以及对风险较高的CRC患者进行充分的治疗。这些患者的初始治疗决定部分取决于组织学参数，例如浸润深度，分化程度，淋巴管浸润和壁外血管浸润。然而，来自系统评价的证据表明，肿瘤萌芽（即在肿瘤的浸润性前端出现单个肿瘤细胞或小肿瘤细胞簇直至多达四个细胞）是可能有助于做出治疗决定的最有力的组织学标志物之一。然而，由于缺乏组织学评估的标准化，阻碍了该生物标记物的实施。已经提出数字图像分析作为确定肿瘤发芽的高度可靠的方法，这将有助于治疗决策。

在该项目中，我们将卷积神经网络与不同染色的CRC全幻灯片图像相结合，以创建一种能够检测肿瘤萌芽和肿瘤簇（PDC）的算法。这将成为对CRC浸润边缘之内和边缘的萌芽程度进行详细，可重复分析的基础（瘤内与瘤周）。通过计算WSI中每个候选位置的芽和PDC数量，可以得出特定位置的定量数据。


###可解释性
[2019MICCAI-Domain Adaptation and Representation Transfer](https://sites.google.com/view/dart2020)


####Thesis

1.  [Thijs Kooi-Computer aided diagnosis of breast cancer in mammography using deep neural networks](http://www.diagnijmegen.nl/index.php/Publication?bibkey=Kooi18)
2.  [《神经网络与深度学习》讲义](http://vdisk.weibo.com/s/ayG13we2ltDAT)，邱锡鹏。

####实验室 & Research

[亥姆霍兹人工智能合作部](https://camp.lcsr.jhu.edu/)
* ## [Stain Separation and Structure-Preserving Color Normalization for Histological Images](http://campar.in.tum.de/Chair/ProjectStainSeparation)

[Tingying Peng](http://campar.in.tum.de/Main/TingyingPeng)

[Abhishek Vahadane
](http://campar.in.tum.de/Main/AbhishekVahadane)


* [Computational Pathology Group](https://www.computationalpathologygroup.eu/)

[Geert Litjens](https://www.computationalpathologygroup.eu/members/geert-litjens/)

[Geert Litjens-Personal website](https://geertlitjens.nl/)

[Jeroen van der Laak](https://www.computationalpathologygroup.eu/members/jeroen-van-der-laak/)

* [Zizhao Zhang
](https://sites.google.com/view/zizhaozhang)



* [Faisal Mahmood](https://faisal.ai/faisal-mahmood-research-deep-learning/)

[Behzad Bozorgtabar](https://behzadbozorgtabar.com/)

* [Pathology-Learning to Cure](http://learningtocure.csail.mit.edu/#projects)


####经典论文

1.  [Wu, Nan, et al. "Deep Neural Networks Improve Radiologists' Performance in Breast Cancer Screening." arXiv preprint arXiv:1903.08297 (2019).](https://openreview.net/pdf?id=SkxYez76FE)
[openreview](https://openreview.net/forum?id=SkxYez76FE&noteId=SkxYez76FE)



####Code


* [ASAP-Automated Slide Analysis Platform](https://github.com/computationalpathologygroup/ASAP)

* [ASAP - Fluid whole-slide image viewer](https://www.computationalpathologygroup.eu/software/asap/)

* [Computational Pathology Group](https://github.com/computationalpathologygroup)
* [Pathologist-level interpretable whole-slide cancer diagnosis with deep learning
](https://github.com/zizhaozhang/nmi-wsi-diagnosis)

[Computational Pathology](https://github.com/MSKCC-Computational-Pathology)
### [Pen annotation extraction from WSI](https://github.com/MSKCC-Computational-Pathology/PenAnnotationExtractor)

* [Mahmood Lab @ Harvard/BWH](https://github.com/mahmoodlab)


* [Diagnostic Image Analysis Group](https://github.com/DIAGNijmegen?page=2)


####Dataset


    

###报告

[[#20-16] MICS在线学术讲座：彭廷莹（亥姆霍兹人工智能合作部）](https://www.bilibili.com/video/BV16K411G71G)
[[#20-03] MICS在线学术讲座：黄昆（计算病理与基因组学数据的整合分析）](https://www.bilibili.com/video/BV1Za4y1v76N)


####Challenge

[近三年病理(WSI)医学图像比赛汇总](https://zhuanlan.zhihu.com/p/298304895)

* [Retinal Image Analysis For Multi-Disearse Detection ](https://riadd.grand-challenge.org/Home/)


[Prostate cANcer graDe Assessment (PANDA) Challenge
](https://panda.grand-challenge.org/)


[Getting Started With Camelyon (Part 1)](https://geertlitjens.nl/post/getting-started-with-camelyon/)

[The CAMELYON17](https://camelyon17.grand-challenge.org/)
[The CAMELYON16](https://camelyon16.grand-challenge.org/)
[Camelyon16](https://github.com/computationalpathologygroup/Camelyon16)

[DigestPath2019](https://digestpath2019.grand-challenge.org/Home/)

[Challenge on Brain Tumor Classification 2019 (CPM-RadPath)](https://www.med.upenn.edu/cbica/cpm-rad-path-2019/)

[PAIP2020](https://paip2020.grand-challenge.org/Dataset/)
[http://www.wisepaip.org/](http://www.wisepaip.org/)

[https://pathvqachallenge.grand-challenge.org/](https://pathvqachallenge.grand-challenge.org/)



###Workshops and Courses

[COMPAY19 Workshop](https://compay19.grand-challenge.org/)


###Blog

[肿瘤病理图向-机器学习应用](https://zhuanlan.zhihu.com/p/110083982)
## [Assisting Pathologists in Detecting Cancer with Deep Learning](https://ai.googleblog.com/2017/03/assisting-pathologists-in-detecting.html)

### Special Issue 
[Computational Pathology](https://www.embs.org/jbhi/computational-pathology/)



#公司：




#FDA
























