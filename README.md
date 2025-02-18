<img src="icon.png" align="right" />

# Awesome Contrastive Learning Papers&Codes 
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome#readme)
> A comprehensive list of awesome Contrastive Learning Papers&amp;Codes.

Contrastive learning papers at the top conferences, research include, but are not limited to: CV, NLP, Audio, Video, Multimodal, Graph, Language, etc.
## [Content](#content)

![](https://img.shields.io/badge/Status-building-brightgreen) ![](https://img.shields.io/badge/PRs-Welcome-red) 
![License](https://img.shields.io/github/license/benedekrozemberczki/awesome-graph-embedding.svg?color=blue)
[![repo size](https://img.shields.io/github/repo-size/coder-duibai/Contrastive-Learning-Papers-Codes.svg)](https://github.com/coder-duibai/Contrastive-Learning-Papers-Codes/tree/main.zip)
<table>
<tr><td colspan="2"><a href="#survey-papers">1. Survey Papers</a></td></tr> 
<tr><td colspan="2"><a href="#problems">2. Problems</a></td></tr> 

<tr>
	<td>&emsp;<a href=#computer-vision>2.1 Computer Vision</a></td>
	<td>&emsp;<a href=#audio>2.2 Audio</a></td>
</tr>
<tr>
	<td>&emsp;<a href=#Videos-and-Multimodal>2.3 Videos and Multimodal</a></td>
	<td>&emsp;<a href=#NLP>2.4 NLP</a></td>
</tr>
<tr>
	<td>&emsp;<a href=#language-contrastive-learning>2.5 Language Contrastive Learning</a></td>
	<td>&emsp;<a href=#graph>2.6 Graph</a></td>
</tr>
<tr>
	<td>&emsp;<a href=#adversarial-learning>2.7 Adversarial Learning</a></td>
	<td>&emsp;<a href=#applications>2.8 Recommendation</a></td>
</tr>
<tr>
	<td>&emsp;<a href=#recommendation>2.9 Applications</a></td>
</tr>
</table>

## Must-read Papers
### [Survey Papers](#content)
1. **A Survey on Contrastive Self-supervised Learning**. <br />
Authors:Ashish Jaiswal, Ashwin Ramesh Babu, Mohammad Zaki Zadeh, Debapriya Banerjee, Fillia Makedon. [paper](https://arxiv.org/abs/2011.00362)
## [Problems](#content)
### [Computer Vision](#content)
1. **[PCL] Prototypical Contrastive Learning of Unsupervised Representations**. ICLR2021. <br />
Authors:Junnan Li, Pan Zhou, Caiming Xiong, Steven C.H. Hoi. [paper](https://arxiv.org/abs/2005.04966) [code](https://github.com/salesforce/PCL)
2. **[BalFeat] Exploring Balanced Feature Spaces for Representation Learning**. ICLR2021. <br />
Authors:Bingyi Kang, Yu Li, Sa Xie, Zehuan Yuan, Jiashi Feng. [paper](https://openreview.net/forum?id=OqtLIabPTit)
3. **[MiCE] MiCE: Mixture of Contrastive Experts for Unsupervised Image Clustering**. ICLR2021. <br />
Authors:Tsung Wei Tsai, Chongxuan Li, Jun Zhu. [paper](https://openreview.net/forum?id=gV3wdEOGy_V) [code](https://github.com/TsungWeiTsai/MiCE)
4. **[i-Mix] i-Mix: A Strategy for Regularizing Contrastive Representation Learning**. ICLR2021. <br />
Authors:Kibok Lee, Yian Zhu, Kihyuk Sohn, Chun-Liang Li, Jinwoo Shin, Honglak Lee. [paper](https://arxiv.org/abs/2010.08887) [code](https://github.com/kibok90/imix) 
5. **Contrastive Learning with Hard Negative Samples**. ICLR2021. <br />
Authors:Joshua Robinson, Ching-Yao Chuang, Suvrit Sra, Stefanie Jegelka. [paper](https://arxiv.org/abs/2010.04592) [coder](https://github.com/joshr17/HCL)
6. **[LooC] What Should Not Be Contrastive in Contrastive Learning**. ICLR2021. <br />
Authors:Tete Xiao, Xiaolong Wang, Alexei A. Efros, Trevor Darrell. [paper](https://arxiv.org/abs/2008.05659)
7. **[MoCo] Momentum Contrast for Unsupervised Visual Representation Learning**. CVPR2020. <br />
Authors:Kaiming He, Haoqi Fan, Yuxin Wu, Saining Xie, Ross Girshick. [paper](https://arxiv.org/abs/1911.05722) [code](https://github.com/facebookresearch/moco)
8. **[MoCo v2] Improved Baselines with Momentum Contrastive Learning**. 
Authors:Xinlei Chen, Haoqi Fan, Ross Girshick, Kaiming He. [paper](https://arxiv.org/abs/2003.04297) [code](https://github.com/facebookresearch/moco)
9. **[SimCLR] A Simple Framework for Contrastive Learning of Visual Representations**. ICML2020.<br />
Authors:Ting Chen, Simon Kornblith, Mohammad Norouzi, Geoffrey Hinton. [paper](https://arxiv.org/abs/2002.05709) [code](https://github.com/google-research/simclr)
10. **[SimCLR v2] Big Self-Supervised Models are Strong Semi-Supervised Learners**. NIPS2020.<br />
Authors:Ting Chen, Simon Kornblith, Kevin Swersky, Mohammad Norouzi, Geoffrey Hinton. [paper](https://arxiv.org/abs/2006.10029) [code](https://github.com/google-research/simclr)
11. **[BYOL] Bootstrap your own latent: A new approach to self-supervised Learning**.<br />
Authors:Jean-Bastien Grill, Florian Strub, Florent Altché, Corentin Tallec, Pierre H. Richemond, Elena Buchatskaya, Carl Doersch, Bernardo Avila Pires, Zhaohan Daniel Guo, Mohammad Gheshlaghi Azar, Bilal Piot, Koray Kavukcuoglu, Rémi Munos, Michal Valko. [paper](https://arxiv.org/abs/2006.07733) [code](https://github.com/deepmind/deepmind-research/tree/master/byol)
12. **[SwAV] Unsupervised Learning of Visual Features by Contrasting Cluster Assignments**. NIPS2020. <br />
Authors:Mathilde Caron, Ishan Misra, Julien Mairal, Priya Goyal, Piotr Bojanowski, Armand Joulin. [paper](https://arxiv.org/abs/2006.09882) [code](https://github.com/facebookresearch/swav)
13. **[SimSiam] Exploring Simple Siamese Representation Learning**. CVPR2021. <br />
Authors:Xinlei Chen, Kaiming He. [paper](https://openaccess.thecvf.com/content/CVPR2021/html/Chen_Exploring_Simple_Siamese_Representation_Learning_CVPR_2021_paper.html) [code](https://github.com/PatrickHua/SimSiam/blob/main/models/simsiam.py)
14. **Hard Negative Mixing for Contrastive Learning**. NIPS2020. <br />
Authors:Yannis Kalantidis, Mert Bulent Sariyildiz, Noe Pion, Philippe Weinzaepfel, Diane Larlus. [paper](https://arxiv.org/abs/2010.01028)
15. **Supervised Contrastive Learning**. NIPS2020. <br />
Authors:Prannay Khosla, Piotr Teterwak, Chen Wang, Aaron Sarna, Yonglong Tian, Phillip Isola, Aaron Maschinot, Ce Liu, Dilip Krishnan. [paper](https://arxiv.org/abs/2004.11362)
16. **[LoCo] LoCo: Local Contrastive Representation Learning**. NIPS2020. <br />
Authors:Yuwen Xiong, Mengye Ren, Raquel Urtasun. [paper](https://arxiv.org/abs/2008.01342)
17. **What Makes for Good Views for Contrastive Learning?**. NIPS2020.  <br />
Authors:Yonglong Tian, Chen Sun, Ben Poole, Dilip Krishnan, Cordelia Schmid, Phillip Isola. [paper](https://arxiv.org/abs/2005.10243)
18. **[ContraGAN] ContraGAN: Contrastive Learning for Conditional Image Generation**. NIPS2020. <br />
Authors:Minguk Kang, Jaesik Park. [paper](https://arxiv.org/abs/2006.12681) [code](https://github.com/POSTECH-CVLab/PyTorch-StudioGAN)
19. **[SpCL] Self-paced Contrastive Learning with Hybrid Memory for Domain Adaptive Object Re-ID**. NIPS2020. <br />
Authors:Yixiao Ge, Feng Zhu, Dapeng Chen, Rui Zhao, Hongsheng Li. [paper](https://arxiv.org/abs/2006.02713) [code](https://github.com/yxgeee/SpCL)

### [Audio](#content)
1. **wav2vec 2.0: A Framework for Self-Supervised Learning of Speech Representations**.<br />
Authors:Alexei Baevski, Henry Zhou, Abdelrahman Mohamed, Michael Auli. [paper](https://arxiv.org/abs/2006.11477) [code](https://github.com/pytorch/fairseq)

### [Videos and Multimodal](#content)
1. **Time-Contrastive Networks: Self-Supervised Learning from Video**.<br />
Authors: Pierre Sermanet; Corey Lynch; Yevgen Chebotar; Jasmine Hsu; Eric Jang; Stefan Schaal; Sergey Levine. [paper](https://ieeexplore.ieee.org/abstract/document/8462891)
2. **Contrastive Multiview Coding**. <br />
Authors:Yonglong Tian, Dilip Krishnan, Phillip Isola. [paper](https://link.springer.com/chapter/10.1007%2F978-3-030-58621-8_45) [code](https://github.com/HobbitLong/CMC/)
3. **Learning Video Representations using Contrastive Bidirectional Transformer**.<br />
Authors:Chen Sun, Fabien Baradel, Kevin Murphy, Cordelia Schmid. [paper](https://arxiv.org/abs/1906.05743)
4. **End-to-End Learning of Visual Representations from Uncurated Instructional Videos**. CVPR2020.<br /> 
Authors:Antoine Miech, Jean-Baptiste Alayrac, Lucas Smaira, Ivan Laptev, Josef Sivic, Andrew Zisserman. [paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Miech_End-to-End_Learning_of_Visual_Representations_From_Uncurated_Instructional_Videos_CVPR_2020_paper.html) [code](https://www.di.ens.fr/willow/research/mil-nce/)
5. **Multi-modal Self-Supervision from Generalized Data Transformations**.<br /> 
Authors:Mandela Patrick, Yuki M. Asano, Polina Kuznetsova, Ruth Fong, João F. Henriques, Geoffrey Zweig, Andrea Vedaldi. [paper](https://arxiv.org/abs/2003.04298)
6. **Support-set bottlenecks for video-text representation learning**. ICLR2021. <br />
Authors:Mandela Patrick, Po-Yao Huang, Yuki Asano, Florian Metze, Alexander Hauptmann, João Henriques, Andrea Vedaldi. [paper](https://arxiv.org/abs/2010.02824)
7. **Contrastive Learning of Medical Visual Representations from Paired Images and Text**. ICLR2021. <br />
Authors:Yuhao Zhang, Hang Jiang, Yasuhide Miura, Christopher D. Manning, Curtis P. Langlotz. [paper](https://arxiv.org/abs/2010.00747)
8. **AVLnet: Learning Audio-Visual Language Representations from Instructional Videos**.<br />
Authors:Andrew Rouditchenko, Angie Boggust, David Harwath, Brian Chen, Dhiraj Joshi, Samuel Thomas, Kartik Audhkhasi, Hilde Kuehne, Rameswar Panda, Rogerio Feris, Brian Kingsbury, Michael Picheny, Antonio Torralba, James Glass. [paper](https://arxiv.org/abs/2006.09199)
9. **Self-Supervised MultiModal Versatile Networks**. NIPS2020. <br />
Authors:Jean-Baptiste Alayrac, Adrià Recasens, Rosalia Schneider, Relja Arandjelović, Jason Ramapuram, Jeffrey De Fauw, Lucas Smaira, Sander Dieleman, Andrew Zisserman. [paper](https://arxiv.org/abs/2006.16228)
10. **Memory-augmented Dense Predictive Coding for Video Representation Learning**.<br />
Authors:Tengda Han, Weidi Xie, Andrew Zisserman. [paper](https://link.springer.com/chapter/10.1007%2F978-3-030-58580-8_19) [code](https://www.robots.ox.ac.uk/~vgg/research/DPC/)
11. **Spatiotemporal Contrastive Video Representation Learning**.<br />
Authors:Rui Qian, Tianjian Meng, Boqing Gong, Ming-Hsuan Yang, Huisheng Wang, Serge Belongie, Yin Cui. [paper](https://arxiv.org/abs/2008.03800) [code](https://github.com/tensorflow/models/tree/master/official/)
12. **Self-supervised Co-training for Video Representation Learning**. NIPS2020.<br />
Authors:Tengda Han, Weidi Xie, Andrew Zisserman. [paper](https://arxiv.org/abs/2010.09709)




### [NLP](#content)
1. **[CALM] Pre-training Text-to-Text Transformers for Concept-centric Common Sense**. ICLR2021. <br />
Authors:Wangchunshu Zhou, Dong-Ho Lee, Ravi Kiran Selvam, Seyeon Lee, Xiang Ren. [paper](https://openreview.net/forum?id=3k20LAiHYL2) [code](https://github.com/INK-USC/CALM)
2. **Residual Energy-Based Models for Text Generation**. ICLR2021. <br />
Authors:Yuntian Deng, Anton Bakhtin, Myle Ott, Arthur Szlam, Marc'Aurelio Ranzato. [paper](https://arxiv.org/abs/2004.11714)
3. **Contrastive Learning with Adversarial Perturbations for Conditional Text Generation**. ICLR2021. <br />
Authors:Seanie Lee, Dong Bok Lee, Sung Ju Hwang. [paper](https://arxiv.org/abs/2012.07280)
4. **[CoDA] CoDA: Contrast-enhanced and Diversity-promoting Data Augmentation for Natural Language Understanding**. ICLR2021. <br />
Authors:Yanru Qu, Dinghan Shen, Yelong Shen, Sandra Sajeev, Jiawei Han, Weizhu Chen. [paper](https://arxiv.org/abs/2010.08670)
5. **[FairFil] FairFil: Contrastive Neural Debiasing Method for Pretrained Text Encoders**. ICLR2021. <br />
Authors:Pengyu Cheng, Weituo Hao, Siyang Yuan, Shijing Si, Lawrence Carin. [paper](https://arxiv.org/abs/2103.06413)
6. **Towards Robust and Efficient Contrastive Textual Representation Learning**. ICLR2021. <br />
Authors:Liqun Chen, Yizhe Zhang, Dianqi Li, Chenyang Tao, Dong Wang, Lawrence Carin. [paper](https://openreview.net/forum?id=mDAZVlBeXWx)
7. **Self-supervised Contrastive Zero to Few-shot Learning from Small, Long-tailed Text data**. ICLR2021. <br />
Authors:Nils Rethmeier, Isabelle Augenstein. [paper](https://openreview.net/forum?id=_cadenVdKzF)
8. **Approximate Nearest Neighbor Negative Contrastive Learning for Dense Text Retrieval**. ICLR2021. <br />
Authors:Lee Xiong, Chenyan Xiong, Ye Li, Kwok-Fung Tang, Jialin Liu, Paul Bennett, Junaid Ahmed, Arnold Overwijk. [paper](https://arxiv.org/abs/2007.00808)
9. **Self-Supervised Contrastive Learning for Efficient User Satisfaction Prediction in Conversational Agents**. NAACL2021. <br />
Authors:Mohammad Kachuee, Hao Yuan, Young-Bum Kim, Sungjin Lee. [paper](https://arxiv.org/abs/2010.11230)
10. **SOrT-ing VQA Models : Contrastive Gradient Learning for Improved Consistency**. NAACL2021. <br />
Authors:Sameer Dharur, Purva Tendulkar, Dhruv Batra, Devi Parikh, Ramprasaath R. Selvaraju. [paper](https://aclanthology.org/2021.naacl-main.248/)
11. **Supporting Clustering with Contrastive Learning**. NAACL2021. <br />
Authors:Dejiao Zhang, Feng Nan, Xiaokai Wei, Shangwen Li, Henghui Zhu, Kathleen McKeown, Ramesh Nallapati, Andrew Arnold, Bing Xiang. [paper](https://arxiv.org/abs/2103.12953)
12. **Understanding Hard Negatives in Noise Contrastive Estimation**. NAACL2021. <br />
Authors:Wenzheng Zhang, Karl Stratos. [paper](https://arxiv.org/abs/2104.06245)
13. **Contextualized and Generalized Sentence Representations by Contrastive Self-Supervised Learning: A Case Study on Discourse Relation Analysis**. NAACL2021. <br />
Authors:Hirokazu Kiyomaru, Sadao Kurohashi. [paper](https://aclanthology.org/2021.naacl-main.442/)
14. **Fine-Tuning Pre-trained Language Model with Weak Supervision: A Contrastive-Regularized Self-Training Approach**. NAACL2021. <br />
Authors:Yue Yu, Simiao Zuo, Haoming Jiang, Wendi Ren, Tuo Zhao, Chao Zhang. [paper](https://arxiv.org/abs/2010.07835)


### [Language Contrastive Learning](#content)

1. **Distributed Representations of Words and Phrases and their Compositionality**. 2013NIPS. <br />
Authors:Tomas Mikolov, Ilya Sutskever, Kai Chen, Greg Corrado, Jeffrey Dean. [Paper](https://arxiv.org/abs/1310.4546)

2. **An efficient framework for learning sentence representations**.<br />
Authors:Lajanugen Logeswaran, Honglak Lee. [Paper](https://arxiv.org/abs/1803.02893)
3. **XLNet: Generalized Autoregressive Pretraining for Language Understanding**.<br /> 
Authors:Zhilin Yang, Zihang Dai, Yiming Yang, Jaime Carbonell, Ruslan Salakhutdinov, Quoc V. Le. [Paper](https://arxiv.org/abs/1906.08237)
4. **A Mutual Information Maximization Perspective of Language Representation Learning**. <br /> 
Authors:Lingpeng Kong, Cyprien de Masson d'Autume, Wang Ling, Lei Yu, Zihang Dai, Dani Yogatama. [Paper](https://arxiv.org/abs/1910.08350)
5. **InfoXLM: An Information-Theoretic Framework for Cross-Lingual Language Model Pre-Training**. <br /> 
Authors:Zewen Chi, Li Dong, Furu Wei, Nan Yang, Saksham Singhal, Wenhui Wang, Xia Song, Xian-Ling Mao, Heyan Huang, Ming Zhou. [Paper](https://arxiv.org/abs/2007.07834)
### [Graph](#content)
1. **[GraphCL] Graph Contrastive Learning with Augmentations**. NIPS2020. <br />
Authors:Yuning You, Tianlong Chen, Yongduo Sui, Ting Chen, Zhangyang Wang, Yang Shen. [paper](https://proceedings.neurips.cc/paper_files/paper/2020/hash/3fe230348e9a12c13120749e3f9fa4cd-Abstract.html)
2. **Contrastive Multi-View Representation Learning on Graphs**. ICML2020. <br />
Authors:Kaveh Hassani, Amir Hosein Khasahmadi. [Paper](https://arxiv.org/abs/2006.05582)
3. **[GCC] GCC: Graph Contrastive Coding for Graph Neural Network Pre-Training**. KDD2020. <br /> 
Authors:Jiezhong Qiu, Qibin Chen, Yuxiao Dong, Jing Zhang, Hongxia Yang, Ming Ding, Kuansan Wang, Jie Tang. [Paper](https://arxiv.org/abs/2006.09963)
4. **[InfoGraph] InfoGraph: Unsupervised and Semi-supervised Graph-Level Representation Learning via Mutual Information Maximization**. ICLR2020. <br />
Authors:Fan-Yun Sun, Jordan Hoffmann, Vikas Verma, Jian Tang. [Paper](https://arxiv.org/abs/1908.01000)

### [Adversarial Learning](#content)
1. **Contrastive Learning with Adversarial Examples**. NIPS2020. <br />
Authors:Chih-Hui Ho, Nuno Vasconcelos. [paper](https://arxiv.org/abs/2010.12050)


### [Recommendation](#content)
1. **Self-Supervised Hypergraph Convolutional Networks for Session-based Recommendation**. AAAI2021. <br />
Authors:Xin Xia, Hongzhi Yin, Junliang Yu, Qinyong Wang, Lizhen Cui, Xiangliang Zhang. [paper](https://arxiv.org/abs/2012.06852) [code](https://github.com/xiaxin1998/DHCN)
2. **Self-Supervised Multi-Channel Hypergraph Convolutional Network for Social Recommendation**. WWW2021. <br />
Authors:Junliang Yu, Hongzhi Yin, Jundong Li, Qinyong Wang, Nguyen Quoc Viet Hung, Xiangliang Zhang. [paper](https://arxiv.org/abs/2101.06448) [code](https://github.com/Coder-Yu/QRec)
3. **Self-supervised Graph Learning for Recommendation**. SIGIR2021. <br />
Authors:Jiancan Wu, Xiang Wang, Fuli Feng, Xiangnan He, Liang Chen, Jianxun Lian, Xing Xie. [paper](https://arxiv.org/abs/2010.10783) [code](https://github.com/wujcan/SGL)

### [Applications](#content)
1. **Contrastive Learning for Unpaired Image-to-Image Translation**.<br />
Authors:Taesung ParkAlexei A. Efros, Richard ZhangJun-Yan Zhu. [paper](https://link.springer.com/chapter/10.1007/978-3-030-58545-7_19)

## About Me
你好，我是对白。目前是一名大厂算法工程师，也是一位本科独立创业并拿过数百万融资的小哥哥。日常在[知乎](https://www.zhihu.com/people/coder_duibai)和微信分享算法知识、创业心得和人生感悟。<br />
欢迎关注我的微信公众号，后台回复关键词：**对比学习**，即可获取对比学习最新论文合集（包含以上所有论文哦~）

![加载失败](https://github.com/lijinze9456yy000/awesome-contrastive-learning-papers-codes/blob/main/Wechat.jpeg)
