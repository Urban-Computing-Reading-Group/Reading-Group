# Reading Group 分享


#### 11月18日 <br>
1. Competitive Analysis for Points of Interest <br>

**Summary:**<br>
*Given a heterogenous POI information network, this work proposes a competitive relationship prediction problem, which is by nature a link prediction problem. By leveraging the spatial and semantic (e.g. brand, aspect) attributes of POIs, this work proposes a GNN-based DeepR framwork to perform the task.*<br>

作者: Shuangli Li, Jingbo Zhou, Tong Xu, Hao Liu, Xinjiang Lu, Hui Xiong <br>
论文链接: https://bigdata.ustc.edu.cn/paper_pdf/2020/Shuangli_KDD20.pdf <br>
分享人: 王肇南 [PDF](/ppt/11182020-POICompete-KDD20.pptx)

#### 9月18日 <br>
1. Curb-GAN: Conditional Urban Traffic Estimation through Spatio-Temporal Generative Adversarial Networks <br>

**Summary:**<br>
*This work proposes a conditional urban traffic estimation problem, namely estimating the posterior traffic distribution given the prior of travel demand. Considering dramatic change may take place after a big urban development, this work formulates the problem as a traffic data generation problem. Regarding travel demand as the condition, and leveraging GCN, Transformer Attention to handle spatio-temporal autocorrelations, this work proposes a model named Curb-GAN to perform the task.*<br>

作者: Yingxue Zhang, Yanhua Li, Xun Zhou, Xiangnan Kong, Jun Luo <br>
论文链接: https://dl.acm.org/doi/pdf/10.1145/3394486.3403127 <br>
分享人: 王肇南 [PDF](/ppt/09182020-CurbGAN-KDD20.pdf)

#### 9月11日<br>
1.Federated Learning with Differential Privacy: Algorithms and Performance Analysis 

**Summary:**<br>

*Federated learning (FL) can preserving client's private data from being exposed. Nevertheless, information can still be divulged by the uploaded parameters from clients, e.g., weights. In this paper, based on the concept of differential privacy (DP), artificial noises are added to the parameters before aggregating. The theoretical results show that this strategy exists an optimal aggregation times and  number of participated clients. However, the evaluations also show that while the privacy is preserving, the quality of the models has declined significantly.*<br> 

作者： Kang Wei, Jun Li, Ming Ding, Chuan Ma, Howard H. Yang, Farokhi Farhad, Shi Jin, Tony Q. S. Quek, H. Vincent Poor<br>
论文链接：https://arxiv.org/pdf/1911.00222.pdf <br>
分享人： 张恺玥[PPT](/ppt/0911-kaiyuezhang-Federated%20Learning%20With%20Differential%20Privacy.pdf)


#### 9月4日<br>
1.AM-GCN: Adaptive Multi-channel Graph Convolutional Network<br>

**Summary:**<br>

  *The capability of the state-of-the-art GCNs in fusing node features and topological structures is distant from optimal or even satisfactory. The weakness may severely hinder the capability of GCNs in some classification tasks, since GCNs may not be able to adaptively learn some deep correlation information between topological structures and node features. The paper proposes an adaptive multi-channel graph convolutional networks for semi-supervised classification (AM-GCN). The central idea is that the model extracts the specific and common embeddings from node features, topological structures, and their combinations simultaneously, and uses the attention mechanism to learn adaptive importance weights of the embeddings.*

作者： Xiao Wang; Meiqi Zhu; Deyu Bo; Peng Cui; Chuan Shi; Jian Pei<br>
论文链接 https://arxiv.org/abs/2007.02265<br>
分享人：邓婕文[PPT](/ppt/邓婕文-ReadingGroup-20200904.pptx)

2.Doing in One Go: Delivery Time Inference
Based on Couriers’ Trajectories<br>

**Summary:**<br>

  *The paper aims to reduce couriers' burden by inferring the delivery time of each waybill based on couriers's trajectory and historical data. They come up with DTinf model consisting of three components:  Data Pre-processing, first components, is response for data cleaning, indentifying stay point and seperating waybills. Then the next part-Delivery Location Correction-will correct the Geocoded waybill location to an more believable and reasonable delivery location.  The last part, Delivery Event-based Matching, use corrected location and infer the most possible stay point arounding each corrected location. And the time of each stay point become the delivery time of each waybill.*

作者： Sijie Ruan, Zi Xiong<br>
论文链接 http://urban-computing.com/pdf/KDD2020%20Delivery%20Time.pdf<br>
分享人：江亦凡[PPT](/ppt/reading_group_9.4.江亦凡.pptx)


#### 8月21日<br>
1.NCF: A Neural Context Fusion Approach to Raw Mobility Annotation <br>
作者：Renjun Hu, Jingbo Zhou, Xinjiang Lu, Hengshu Zhu, Shuai Ma, and Hui Xiong <br>
论文链接：http://mashuai.buaa.edu.cn/pubs/tmc2020.pdf <br>

**Summary:**<br>
*This work solves the problem of obtaining better POI-based human mobility. The motivation is that most studies simply utilize POI check-ins to mine the concerned mobility patterns, the effectiveness, most of which is usually hindered, due to data sparsity.  So in this paper, the author strives to directly annotate the POIs associated with raw user-generated mobility records. They propose a neural context fusion approach, which integrates various context factors in people’s POI-visiting behaviors. And their approach incorporates an attention mechanism to deal with the randomized transitions in raw mobility. The domain knowledge factors, i.e., distance, time, and popularity. Using two real-life data sets, they demonstrate the utility of the obtained POI-based human mobility with a POI recommendation example.*<br>

分享人：李永康  [PPT](/ppt/李永康NCF分享.pptx)

2.Learning Stable Graphs from Multiple Environments with Selection Bias <br>

**Summary:**<br>
*This work solves the problem of learning stable graphs from multiple environments with selection bias. The motivation is that the data collection process of graph generation is full of known or unknown sample selection biases, leading to spurious correlations among entities. It achieves this by proposing a SGL framework, which consists of a GCN module for structure embedding and a designed E-VAE for high-dimensional sparse set generation.* <br>

作者：Yue He, Peng Cui, Jianxin Ma, Hao Zou, Xiaowei Wang, Hongxia Yang, and Philip S. Yu <br>
论文链接：https://ftp.cs.ucla.edu/pub/stat_ser/r381.pdf<br>
分享人：蔡泽坤  [PPT](/ppt/Zekun_Cai_20200821.pptx)


#### 8月14日<br>
1.Stable Prediction with Model Misspecification and Agnostic Distribution Shift<br>

**Summary:**<br>
*This paper focus on the problem of the different distribution between the train data and test data on linear regression. Author consider that vanishing the unstable loss, which easier effect by environment, to maintain a general minimal loss for any environment. Thus, by formula derivation, vanishing the unstable loss is equal to remove the correlation among all sample. It could be think that a noval approach to reweight the sample on linear regression.* <br>

作者：Kun Kuang, Ruoxuan Xiong, Peng Cui, Susan Athey, Bo Li <br>
论文链接：http://pengcui.thumedialab.com/papers/Stable_DWR.pdf <br>
分享人：王宏俊  [PPT](/ppt/Reading%20group%208.14.ppt)



#### 8月7日<br>
1.AutoST: Efficient Neural Architecture Search for Spatio-Temporal Prediction<br>

**Summary:**<br>
*This work solves the problem of finding the optimal neural architecture at various scenarios in cities. The motivation is that different cities may have different spatial ranges preference while the size of convolution kernel is usually fixed and empirically set, besides, the current approaches fail to fuse the low- and high-level features. The authors proposed a model named AutoST which are mainly composed of the ST-NASNet, they aim to design search space in ST-NASNet to improve the network representation ability. The search space including two basic modules: the mix convolution block and the mix skip connection block.*<br>

作者：Ting Li, Junbo Zhang, Kainan Bao, Yuxuan Liang, Yexin Li, Yu Zheng <br>
论文链接：http://urban-computing.com/pdf/AutoST_kdd20_camera_ready.pdf <br>
分享人： 王一卓 [PPT](/ppt/AutoST.pptx)

2.Spatio-Temporal Dual Graph Attention Network for query-POI <br>

**Summary:**<br>
*This paper focuses on the influence of temporal and spatial relationships and user preferences on POI-matching.The auther develop a spatio-temporal dual graph attention network (STDGAT), which can jointly model dynamic situational context and users’ sequential behaviors for intelligent query-POI matching.It first encodes the given POIname and query term with given geographic information map.The main innovation part is a network structure to collect embedding of general spatial features through a generalized network, and at the same time encode time and user preferences through a user-related network, and finally perform feature fusion and output through fusion block.*<br>

作者：Zixuan Yuan, Hao Liu, Yanchi Liu, Denghui Zhang, Fei Yi, Nengjun Zhu, Hui Xiong<br>
论文链接：https://dl.acm.org/doi/pdf/10.1145/3397271.3401159 <br>
分享人： 刘航晨 [PPT](/ppt/STDGAT.pptx)


#### 7月31日<br>
1.Hybrid Spatio-Temporal Graph Convolutional Network<br>
**Summary:**<br>
*In this paper, it propose a novel deep architecture for travel time forecasting, the Hybrid Spatio-Temporal Graph Convolutional Network (H-STGCN), which features the utilization of intended-trafficvolume data. We design the domain transformer to couple this heterogeneous modality of traffic volume. We propose a compound adjacency matrix to capture the innate nature of traffic proximity. Experiments carried out on real-world datasets showthat H-STGCN achieves remarkable improvement over the benchmark methods, especially for the prediction of non-recurring congestion. Finally, this architecture exemplifies a novel formalism to embed the knowledge of physics in a data-driven model, which can be readily applied to general spatio-temporal forecasting tasks.*<br>
作者：Rui Dai, Shenkun Xu <br>
论文链接：https://arxiv.org/pdf/2006.12715.pdf <br>
分享人： 尹渡 [PPT](/ppt/yindu-H-STGCN-0731.pdf)

2.Predicting Temporal Sets with Deep Neural Networks<br>
**Summary:**<br>
*This article mainly studies the prediction of time sets (a collection of elements with timestamps, where there are interconnections between elements). The author mainly tested the shopping data (Taobao, TaFeng, etc.) in the article. By combining GCN, attention-based temporal dependency learning module, and gated information fusing module, the loss of information in time set prediction is effectively avoided.*<br>
作者：Le Yu, Leilei Sun, Bowen Du, Chuanren Liu, Hui Xiong, Weifeng Lv1<br>
论文链接：https://arxiv.org/pdf/2006.11483.pdf <br>
分享人: 冯德帆  [PPT](/ppt/Predicting%20Temporal%20Sets%20with%20Deep%20Neural%20Networks.ppt)


#### 7月24日<br>
1.Hierarchical Graph Representation Learning with Differentiable Pooling<br>

**Summary:**<br>
*This work solves the problem of graph-level classification. The motivation is to iteratively perform node clustering and node pooling until a final node is left, which is then used to represent the entire graph. In each iteration, it softly assigns each node to a cluster based on the node feature, then derives the representation of each cluster as well as the connections between the clusters from the node assignment to form a high-level graph.*<br>

作者：Rex Ying, Jiaxuan You, Christopher Morris <br>
论文链接：https://arxiv.org/pdf/1806.08804.pdf <br>
分享人： 邓锦亮 [PPT](/ppt/Graph%20Representation%20Learning.pptx)

2.InfoGraph: Unsupervised and Semi-supervised Graph-Level Representation Learning via Mutual Information Maximization<br>

**Summary:**<br>
*This work solves the problem of unsupervised graph-level representation learning. The motivation is to maintain the information of each subgraphs with different granularity in the representation of the entire graph. It achieves this by maximizing the mutual information between the representation of the entire graph and the representation of each subgraphs (yielded as an intermediate in the process of graph representation learning).*<br>

作者：Fan-Yun Sun, Jordan Hoffmann, Vikas Verma, Jian Tang <br>
论文链接：https://arxiv.org/pdf/1908.01000.pdf <br>
分享人： 邓锦亮 [PPT](/ppt/Graph%20Representation%20Learning.pptx)

#### 7月10日 <br>
1. Convolutional Neural Networks on Graphs with Fast Localized Spectral Filtering <br>

**Summary:**<br>
*This work aims to generalize convolutional neural network (CNN) on low-dimensional regular grids to high-dimensional irregular domain, represented by graphs. Based on spectral graph theory, this work proposes a strictly localized and computational-efficient convolution kernel by using Chebyshev Polynomials approximation. A fast pooling strategy based on Graclus graph coarsening is also proposed.*<br>

作者: Michael Defferrard, Xavier Bresson, Pierre Vandergheynst<br>
论文链接: http://papers.nips.cc/paper/6081-convolutional-neural-networks-on-graphs-with-fast-localized-spectral-filtering.pdf <br>
分享人: 王肇南 [PDF](/ppt/07102020-ChebNet-NIPS16.pdf)


#### 7月3日<br>
题目：COVI White Paper <br>

**Summary:**<br>
*Manual contact tracing of people infected with Covid-19 is limited while privacy-preserving machine learning can help build up useful model. COVI is a proposed APP which is aimed at alarm people who are infected or have been in contact with an infected person by inform their likely infection risk. COVI uses NHS Bluetooth + mix-nets to protect users' information from the his/her neighbor and the government, and the encounters can be detected and traced at the same time. The simulations also shows that this app can help.*<br>

作者： Hannah Alsdurf, Yoshua Bengio, Tristan Deleu, Prateek Gupta, Daphne Ippolito, Richard Janda, Max Jarvie, Tyler Kolody, Sekoul Krastev, Tegan Maharaj, Robert Obryk, Dan Pilat, Valerie Pisano, Benjamin Prud'homme, Meng Qu, Nasim Rahaman, Irina Rish, Jean-Franois Rousseau, Abhinav Sharma, Brooke Struck, Jian Tang, Martin Weiss, Yun William Yu <br>
论文链接：https://arxiv.org/pdf/2005.08502.pdf <br>
分享人： 张恺玥 [PPT](/ppt/0703-kaiyuezhang-COVIwhitepaper.pdf)


#### 6月24日<br>
1.Flow Prediction in Spatio-Temporal Networks Based on Multitask Deep Learning<br>

**Summary:**<br>
*This work solves the problem of predicting the flows at node and on edge level. The motivation is to simultaneously predict the input/output flow and transformations in the spatio-temporal network. It achieves this by captureing the three correlation(closeness, periodic and trend) using the NODENET and EAGENET, and integrating the external factor by a fusion component.*<br>

作者：Junbo Zhang, Yu Zheng, Junkai Sun, Dekang Qi <br>
论文链接：： https://ieeexplore.ieee.org/document/8606218 <br>
分享人： 邓婕文 [PPT](/ppt/邓婕文-ReadingGroup-20200624.pptx)

#### 6月15日<br>
1.Deep Spatio-Temporal Residual Networks for Citywide Crowd Flows Prediction<br>

**Summary:**<br>
*This work solves the problem of forecasting the flow of crowds in each and every region of a city. The motivation is that this problem is of great importance to traffic management and public safety. It achieves this by convolution-based residual networks to model nearby and distant spatial dependencies between any two regions in a city.*<br>

作者：Junbo Zhang, Yu Zheng, Dekang Qi<br>
论文链接：https://arxiv.org/pdf/1610.00081v2.pdf <br>
分享人： 蔡泽坤 [PPT](/ppt/Zekun_Cai_20200605.pptx)

#### 6月12日<br>
1.Deep Multi-View Spatial-Temporal Network for Taxi Demand Prediction<br>

**Summary:**<br>
*Traditional demand prediction methods mostly rely on time series forecasting techniques, which fail to model the complex  non-linear spatial and temporal relations. The Deep Multi-View Spatial-Temporal Network (DMVST-Net) framework models both spatial and temporal relations. Specifically, the model consists of three views: temporal view (modeling correlations between future demand values with near time points via LSTM), spatial view (modeling local spatial correlation via local CNN), and semantic view (modeling correlations among regions sharing similar temporal patterns).*<br>

作者：Huaxiu Yao, Fei Wu, Jintao Ke, Xianfeng Tang, Yitian Jia, Siyu Lu, Pinghua Gong, Jieping Ye, Zhenhui Li<br>
论文链接：https://arxiv.org/abs/1802.08714<br>
分享人： 邓婕文 [PPT](/ppt/邓婕文-ReadingGroup-20200612.pptx)



