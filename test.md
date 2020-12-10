## 近三年组织病理学数据集汇总

### [竞赛类网址](https://grand-challenge.org)

### Prostate cANcer graDe Assessment (PANDA) Challenge(前列腺癌竞赛2020)
   * 会议：MICCAI 2020: the 23rd International Conference on Medical Image Computing and Computer Assisted Intervention.
   * Dataset: WSI(H&E)11000张,数据集很大
   * 任务：分类 (对前列腺癌进行gleason_score)+分割
   * 地址：https://www.kaggle.com/c/prostate-cancer-grade-assessment
   * metrics: 二次加权kappa
   * 结果：![PNADA](https://github.com/yzh741/Medical-Image-contest/blob/master/image-store/PNADA.png)
   * 有无发表论文：
   * 参赛队伍：
   
   
### ACDC2019(肺癌竞赛)    
  * 会议： The IEEE International Symposium on Biomedical Imaging (ISBI)
  * Dataset: WSI(H&E)       
  * 任务：检测和分割  
  * 地址：https://acdc-lunghp.grand-challenge.org/   
  * metrics: Dice系数  
  * 结果：![ACDC2019](https://github.com/yzh741/Medical-Image-contest/blob/master/image-store/ACDC2019.png)    
  * 有无发表论文：对于每个阶段，将邀请排名前10位的团队共同撰写联合期刊论文，每个团队最多2位作者介绍使用的方法以及此挑战中的结果。 论文将在挑战的每个阶段之后的8个月内提交给该领域的高影响力期刊（例如IEEE TMI，医学图像分析）。
     * >Li, Zhang, et al. "Deep Learning Methods for Lung Cancer Segmentation in Whole-slide Histopathology Images--the ACDC@ LungHP Challenge 2019." arXiv preprint arXiv:2008.09352 (2020).
     * [Deep Learning Methods for Lung Cancer Segmentation in Whole-slide Histopathology Images -- the ACDC@LungHP Challenge 2019](https://arxiv.org/abs/2008.09352)
     
  * 参赛队伍：516
  
  
### ECDP2020(淋巴结转移癌)
  * 会议： This Challenge is part of the 16th European Congress on Digital Pathology (ECDP2020)
  * Dataset：360 cases, 144 positives and 216 negatives       
  * 任务：分类 (对前列腺癌进行gleason_score)+分割
  * 地址：https://ecdp2020.grand-challenge.org/    
  * metrics: F1系数
  * 结果：![ECDP2020](https://github.com/yzh741/Medical-Image-contest/blob/master/image-store/EDCP2020.png)  
  * 有无发表论文：The best performing methods will be invited to collaborate on a journal paper describing and summarizing the different approaches used and the respective results achieved on the Challenge.
    * >La Barbera D, Roitero K, Della Mea V. Detection of HER2 from Haematoxylin-Eosin Slides Through a Cascade of Deep Learning Classifiers via Multi-Instance Learning[J]. Journal of Imaging, 2020, 6(9): 82.
    * [Detection of HER2 from Haematoxylin-Eosin Slides Through a Cascade of Deep Learning Classifiers via Multi-Instance Learning](https://www.mdpi.com/2313-433X/6/9/82)
  * 参赛队伍：1070
  
  
### Paip2019(肝癌)
  * 会议： MICCAI 2019
  * Dataset：50training set   10validation set  40test set       
  * 任务：癌细胞分割、活肿瘤与肿瘤面积比
  * 地址：https://paip2019.grand-challenge.org/ 
  * metrics: ![pair2019_metrics](https://github.com/yzh741/Medical-Image-contest/blob/master/image-store/pair2019_metrics.png)
  * 结果：![pair2019_task1](https://github.com/yzh741/Medical-Image-contest/blob/master/image-store/pair2019_task1.png)
          ![pair2019_task2](https://github.com/yzh741/Medical-Image-contest/blob/master/image-store/pair2019_task2.png)
  * 有无发表论文：High ranked teams will be suggested to submit papers to Health Informatics Research (HIR, www.e-hir.org) which is a SCOPUS citation journal. The submission is optional, but the HIR journal will provide a fast track review.
     * >Kim Y J, Jang H, Lee K, et al. PAIP 2019: Liver cancer segmentation challenge[J]. Medical Image Analysis, 2020, 67: 101854.
     * [PAIP 2019: Liver cancer segmentation challenge](https://www.sciencedirect.com/science/article/pii/S1361841520302188)
    
  * 参赛队伍：1194
 
### Paip2020(大肠癌)
  * 会议： Pathology AI Platform (PAIP) and the Seoul National University Hospital (SNUH)
  * Dataset：47trainging set  31validation set  40test set
  * 任务：
    * main task：分三种大肠癌分子亚型
    * mandatory task：大肠癌分割
  * 地址：https://paip2020.grand-challenge.org/
  * metrics：F1-score
  * 结果：![pair2020](https://github.com/yzh741/Medical-Image-contest/blob/master/image-store/pair2020.png)
  * 有无发表论文：High ranked teams will be suggested to submit papers to Health Informatics Research (HIR, www.e-hir.org) which is a SCOPUS citation journal. The submission is optional, but the HIR journal will provide a fast track review.
  * 参赛队伍：531

### DigestPath2019(肝癌)   
  * 会议： Pathology AI Platform (PAIP) and the Seoul National University Hospital (SNUH)
  * Dataset：50trainging set  10validation set  40test set
  * 任务：
      * task1：signet ring cell detection
      * task2：Colonoscopy tissue segmentation and classification
  * 地址：https://digestpath2019.grand-challenge.org/
  * metrics:
    * task1: FROC
    * task2: Dice Similarity Coefficient (DSC) and AUC
  * 结果：![digest_task1](https://github.com/yzh741/Medical-Image-contest/blob/master/image-store/digest_task1.png)
          ![digest_task2](https://github.com/yzh741/Medical-Image-contest/blob/master/image-store/digest_task2.png)
  * 有无发表论文：Top-ranking teams on each task will be invited to submit full papers on describing their methods to the special issue on Deep learning for Medical Image Computing of Neurocomputing (IF= 4.072). 
    * >Zhu C, Mei K, Peng T, et al. Multi-level colonoscopy malignant tissue detection with adversarial CAC-UNet[J]. arXiv preprint arXiv:2006.15954, 2020.
    * [Multi-level colonoscopy malignant tissue detection with adversarial CAC-UNet](https://arxiv.org/abs/2006.15954)
  * 参赛队伍：964

Frederick National Laboratory
