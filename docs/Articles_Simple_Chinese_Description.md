### Conference Papers
1. Yuqing Geng,**Wenlong Tian***, Ruixuan Li, Weijun Xiao, Chunping Ouyang, Yongbing Liu, Qifei Liu, Jing Li, Xuming Ye and Zhiyong Xu， Context-aware Resemblance Detection based Deduplication Ratio Prediction for Cloud Storage. The 9th IEEE/ACM International Conference on Big Data Computing, Applications and Technologies BDCAT 2022,Vancouver, Washington, USA, December 6-9, 2022. 
> 随着云存储的普及，人们更倾向于将自己的数据外包到云端，以获得更好的灵活性和可靠性。毫无疑问，这些数据中存在很多冗余。然而，高端带去去重存储需要进行大量计算，并增加了数据管理的复杂性。潜在的客户需要了解他们外包数据中的冗余比例，以决定是否值得采用高端带去重存储。因此，许多研究人员之前尝试预测冗余比例。然而，现有的机制忽视了包含许多重复数据的相似块之间的冗余比例。虽然相似性检测，即在相似数据中检测重复部分，已成为一个热门问题，但由于无法接受的计算成本，它几乎不被应用于传统的去重比例估算。因此，我们在预测范围和响应时间方面分析了去重比例预测的局限性和挑战，并进一步提出了一种新颖的预测方案。通过利用上下文感知的相似性检测和置信区间理论，我们的方法可以在去重比例预测方面实现更快的估算速度和更高的准确性，相比于最先进的方法。最后，实验结果表明我们的方法可以在真实工作负载上高效、有效地估计相似块中的重复块和冗余数据的比例。

>This work is supported by the State Scholarship Fund of  China for studying abroad under grants 202108430055, the  National Natural Science Foundation of China under grants  U1836204, Natural Science Foundation of Hunan Province  of China under grant 2021JJ40468, 2022JJ30495, Hunan  Province research foundation under grant 20B515, National  Training Program of Innovation and Entrepreneurship for  Undergraduates under grants 202110555052, S202110555215.


2.Baisong Li, **Wenlong Tian***, Ruixuan Li, Weijun Xiao, Zhongming Fu, Xuming Ye, Renjiao Duan, Yusheng Li, Zhiyong Xu: Cross-domain Resemblance Detection based on Meta-learning for Cloud Storage. The 41st IEEE -- International Performance Computing and Communications Conference, IPCCC, 2022, Austin, TX, USA, November 11-13, 2022.
  
> 云存储在我们的日常生活中得到了广泛的应用。云存储中的外包数据中存在大量冗余。传统的重复数据删除技术在块级别有效地拆分这些数据并删除重复的块，以节省网络带宽并提高云存储效用。但它忽略了相似块之间的冗余。相似消冗最近已成为检测相似数据中这些冗余部分的热门话题。 CARD 是目前首次提出将人工智能方法同数据相似消冗的工作，通过引入具有相似性检测的神经网络，可以有效地消除这些冗余。然而，CARD 模型的源域可能具有明显不同的输入分布。这种直接将将人工智能方法同相似消冗的结合无法处理没有提前训练过的领域数据，换而言之，在这种场景下，CARD这一类型的方法都可能表现的比传统方法还差。这种跨域设置可能会连续降低 CARD 的性能。为了克服这个问题，我们提出了一种称为 MetaContext 的跨域相似度检测方案。该方法将块上下文感知模型和元学习思想相结合，通过引入learn-to-learn的思想，即使在跨域的领域数据场景下，也能够表现出比传统的方法和CARD更好的相似消冗效果。最后，我们实现 MetaContext 并在一系列真实的工作负载下进行系列实验。结果表明，我们的方法通过learn-to-learn思路的引入，不仅使得我们的方法无需海量的数据与训练样本，过大的加载训练模型，同时也能够更加高效低检测和消除相似数据之间的冗余。
  
>This work is supported by the State Scholarship Fund of China for studying abroad, the  National Natural Science Foundation of China under grants U1836204, Natural Science Foundation of Hunan Province of China under grant 2021JJ40468, 2022JJ30495, National Training Program of Innovation and Entrepreneurship for Undergraduates under grants 202110555052, S202110555215.


3. Zhigang Xu, Qing Sun, Hongmu Han, Xinhua Dong, Yan Zhongzhen, Zhiqiang Zheng, **Wenlong Tian**, BMTAC: A Decentralized, Auditable, Time-Limited, Multi-Authority Attribute Access Control Scheme in Blockchain Environment. The 19th IEEE International Conference on Ubiquitous Intelligence and Computing, UIC 2022, Haikou, China, December 15-18, 2022

4. Yue Yuan, Yongbin Liu, Chunping Ouyang, **Wenlong Tian** and Wenlong Fang, 基于一对多关系的多模态虚假新闻检测, China Conference on Knowledge Graph and Semantic Computing, CCKS 2022, QingHuangDao, China, August 24-27, 2022

5.Xuming Ye, Xiaoye Xue, **Wenlong Tian***, Ruixuan Li, Weijun Xiao, Zhiyong Xu, Yaping Wan: Chunk Content is not Enough: Chunk-Context Aware Resemblance Detection for Deduplication Delta Compression. 31st Data Compression Conference, DCC 2022, Snowbird, UT, USA, March 22-25, 2022. （Accepted） [video](https://sigport.org/documents/chunk-content-not-enough-chunk-context-aware-resemblance-detection-deduplication-delta) , [PDF](/papers/2022DCC.pdf) , [Full Version](https://arxiv.org/abs/2106.01273), [Detailed](https://mooc1-1.chaoxing.com/nodedetailcontroller/visitnodedetail?courseId=225506193&knowledgeId=571996233)

> 随着云存储的日益普及，识别和删除用户之间的重复数据对于服务提供商来说变得越来越重要。因此，许多研究人员已经开始关注相似消冗技术，重点研究数据相似性的检测方法，以期望去除相似数据之间的冗余部分，提高存储空间的利用率。传统的相似检测方法往往使用特征提取来检测具有高相似性的数据块，然后根据特征之间的距离来判断相似数据块，并利用delta encoding技术提取冗余数据部分。然而，现有的主流相似度检测方法中的特征，如“N-transform”、“Finesse”和“Odess”，只与块内容本身相关，而忽略了相似块上下文语义，我们称之为块-语境。传统方法提取的数据块特征可能会收到少量的数据变化导致相似数据块具有很远的特征距离，甚至被识别为非相似数据块，严重降低了相似检测能力。本文提出了一种新型基于块-语境的上下文感知相似性检测算法，称为 CARD，以解决传统方法的弊端。 CARD 通过引入基于神经网络的数据块上下文感知模型，并使用基于 N-sub-chunk shingles 的初始特征提取策略，有效地将每个数据块内容的内部结构与上下文信息进行特征提取，显着降低了数据块特征对于微小变化的健壮性。我们实现了一个 CARD 原型来评估其性能，并使用真实世界的数据集进行广泛的实验。结果表明，CARD 可以检测多达 75.03% 的冗余数据，并将相似度检测操作加速 5.6 到 86.7 倍。

> This work is supported by the  National Natural Science Foundation of China under grants U1836204, Teaching Reform Foundation under grant 2019YB-XJG30, Natural Science Foundation of Hunan Province of China under grant 2021JJ40468, National Training Program of Innovation and Entrepreneurship for Undergraduates under grants 202110555052, S202110555215 and the Ministry of Education Humanities and Foundation on Humanities and Social Sciences under grant 20YJC880027.


6.Xuming Ye, Jia Tang, **Wenlong Tian***, Ruixuan Li, Weijun Xiao, Zhiyong Xu: Fast Variable-Grained Resemblance Data Deduplication For Cloud Storage. IEEE International Conference on Networking, Architecture and Storage, NAS 2021, Riverside, CA, USA, October 24-26, 2021:1-8. [video](/Videos/2021NAS.mp4), [pdf](/papers/2021NAS.pdf), [Detailed](https://mooc1-1.chaoxing.com/nodedetailcontroller/visitnodedetail?courseId=225506193&knowledgeId=571993912)


 > 随着云存储的盛行，重复数据删除技术通过消除跨用户的重复数据，节省网络带宽，成为一种广泛使用的技术。然而，传统的重复数据删除几乎无法检测相似块之间的重复数据。目前，已经提出了一种称为 Finesse 的相似重复数据删除，以有效地检测和删除相似块之间的重复数据。然而，我们观察到相似块的出现也符合数据局部性原理，即相似的块往往连续出现，反之亦然。此外，当以较小的平均数据块大小处理这些相邻的相似数据块时，传统方法亦会极大地增加元数据总量，从而降低重复数据删除系统的性能。现有的相似性重复数据删除方案忽略了元数据对性能的影响。因此，我们提出了一种用于云存储的快速可变粒度相似性重复数据删除方案。它动态地组合相邻的相似块或独特块或打破这些块，位于相似块和非相似块之间的过渡区域。最后，我们实现了一个原型系统，并在真实的数据集上进行了一系列实验。结果表明，我们的方法显着减少了元数据大小，同时能够在已有方法的基础上提高重复数据删除率。


 > This work is supported by the National Key Research and Development Program of China under grants 2016YFB0800402, National Natural Science Foundation of China under grants U1836204, U1936108, University of South China University research foundation under grant 190XQD121, Teaching Reform Foundation under grant 2019YB-XJG30, Natural Science Foundation of Hunan Province of China under grant 2021JJ40468, Hunan Province research foundation under grant 19C1624, and the Ministry of Education Humanities and Foundation on Humanities and Social Sciences under grant 20YJC880027. This work is also partly supported by the National Science Foundation under grant CNS 1526190.


7.**Wenlong Tian**, Ruixuan Li, Weijun Xiao, Zhiyong Xu: PTS-Dep: A High-Performance Two-Party Secure Deduplication for Cloud Storage. HPCC/SmartCity/DSS 2018: 700-707  [pdf](/papers/2018HPCC.pdf) 


8.Dongdong Yue, Ruixuan Li, Yan Zhang, **Wenlong Tian**, Chengyi Peng: Blockchain Based Data Integrity Verification in P2P Cloud Storage. ICPADS 2018: 561-568.

9.Huikang Cao, Ruixuan Li, **Wenlong Tian**, Zhiyong Xu, Weijun Xiao: A Practical Accountability Scheme for Oblivious RAM in Cloud Storage. TrustCom/BigDataSE 2018: 397-402. ( Best Paper Award)

10.**Wenlong Tian**, Ruixuan Li, Zhiyong Xu, Weijun Xiao: Does the content defined chunking really solve the local boundary shift problem? IPCCC 2017: 1-8. [pdf](/papers/2017IPCCC.pdf)

### Journal Papers
1. **Wenlong Tian**, Qi Liu, Ruixuan Li, Zhiyong  Xu,Yan  Zhang, Yongfeng Huang. A Blockchain-based Secure Searching Strategy for Metadata in Mobile Edge Computing. IEEE Internet of Things Journal, doi:10.1109/JIOT.2023.3282043 

> 随着智能设备的普及，移动边缘计算技术能够有效处理物联网（IoT）中的大量数据。移动边缘计算产生的元数据在大规模数据管理中起着重要作用。然而，它也包含了大量用户隐私信息。传统的隐私保护解决方案要么牺牲元数据的可用性，要么与分布式环境不兼容。为了解决这个困境，我们提出了一种基于区块链的移动边缘计算元数据安全搜索策略（BSSMeta）。通过在区块链上利用轻量级代理重加密方案和分散式密钥生成方法，BSSMeta保持了元数据搜索任务的安全性。同时，为了提高搜索和上传过程的效率，我们提出了主从智能合约方法和缓冲上传策略。作为副产品，BSSMeta还支持在多用户环境中搜索元数据，并为用户提供对元数据的访问控制。最后，我们对BSSMeta进行了安全性分析，并在Hyperledger Fabric平台上实现了原型。对各种工作负载进行的实验结果表明，BSSMeta在安全性和效率方面是可行和灵活的。

>This work is supported by the State Scholarship Fund  of China for studying abroad under grants 202108430055,  Natural Science Foundation of Hunan Province of China  under grant 2021JJ40468, 2022JJ30495, 2022JJ50153, Hunan  Province research foundation under grant 22B0437, 20B515,  Hunan Province Educational Science Planning Project under  grant XJK23AJD014, National Training Program of Innovation and Entrepreneurship for Undergraduates under grants  S202210555149, 2022X10555033, 2022X10555035.


2. 阳智欢，田纹龙，何婷婷，叶旭明，唐佳，上下文语义嵌入的变粒度云存储相似数据去重技术，计算机技术与发展, 2024（已录用）

>针对云存储环境下现有相似数据去重技术效果不佳以及元数据开销大等问题，提出了上下文语义嵌入的变粒度云存储 相似数据去重技术。该技术采用基于子块重组的特征提取算法，对数据块内容内部结构进行初步特征提取，并利用 BP(Back Propagation)神经网络上下文感知模型将数据块上下文特征信息嵌入到初始特征中，实现了具有上下文语义嵌入的变粒度数据 块。通过控制数据块大小，动态地合并相邻相似数据块或非冗余数据块，减少元数据开销，并对位于相似数据块和非冗余数据 块之间过渡区域进行分割，从而获得更好的相似数据块表示形式。最后，为了评估其性能，实现了一个变粒度相似数据检测算法原型, 并使用真实世界的数据集进行了广泛的实验，实验结果表明，与最新相似性检测去重技术相比，该方法可以有效检测冗余数据并且加速相似性检测速度 5.6 至 17.8 倍。

>基金项目：湖南省自然科学基金项目(2021JJ40468)；湖南省教育厅优青项目(22B0437)；湖南省教师教育研究基地 (XJK23AJD014)

3.**Wenlong Tian**, Ruixuan Li, Zhiyong Xu, Weijun Xiao. Loco-Store Locality-Based Oblivious Data  Storage. IEEE Transactions on Dependable and Secure Computing(2022),TDSC, 19(2): 1395-1406 (2022) [pdf](/papers/2022TDSC.pdf)

 > 针对云存储用户因其访问模式序列被监听而导致的用户隐私泄露问题，论文提出一种基于时空局部性原理的不经意数据存储隐私保护方案。针对云存储数据的访问特点，该方案通过引入不经意随机访问机，动态地调整数据的存取，满足云存储的可用性。此外，论文还提出基于时空局部性原理的数据驱逐算法，既保证了该方案可用性，又从理论上证明了该方案的安全性。审稿专家一致认为，时空局部性原理和不经意随机访问机制相结合，有利于在拓展未来可信安全存储达成隐私保护要求的同时为数据的存取提供较高的可用性，为后续工作带来新的启发。


 > This work was supported by the National Key Research  and Development Program of China under Grants  2016YFB0800402 and 2016QY01W0202, National Natural Science Foundation of China under Grants U1836204, U1936108,  61572221, 61433006, and U1401258, Teaching Reform Foundation under Grant 192JXJ129, South of China University  research foundation under Grant 190XQD121, Hunan Province research foundation under Grant 19C1624, and the Ministry of Education Humanities and Foundation on Humanities  and Social Sciences under Grant 20YJC880027. This work is  also supported in part by the National Science Foundation  under Grant CNS 1526190.

4. Zhigang Xu, Shiguang Zhang, Hongmu Han, Xinhua Dong, Zhiqiang Zheng, Haitao Wang, **Wenlong Tian**, Blockchain-Aided Searchable Encryption-Based Two-Way Attribute Access Control Research, Security and Communication Networks, (Accepted)

5.**Wenlong Tian**, Ruixuan Li,  Zhiyong Xu: TSS: A Two-party Secure Server-Aid Chunking Algorithm. Concurr. Comput. Pract. Exp. 34(12) (2022)  

 > 分块是安全重复数据删除系统中最重要的过程之一。它确定重复数据删除率、元数据大小和加密密钥编号。现有的分块算法可以分为客户端分块算法和服务器辅助分块算法。前者虽然可以直接应用于安全去重，但忽略了元数据大小和加密密钥数带来的管理开销。因此，提出了传统的服务器辅助分块算法。但是，它并不安全，因为客户端和服务器之间的交互是基于明文的。因此，我们提出了一种两方安全服务器辅助分块算法 TSS。它支持安全的服务器辅助交互，并减少了安全重复数据删除中的元数据大小和加密密钥数，具有可比的重复数据删除率。理论证明和实验结果表明，我们的方法优于最先进的分块算法、弹性分块算法。

 > This work is supported by the National Key Research and Development Program of China under grants 2016YFB0800402 and 2016QY01W0202, National Natural Science Foundation of China under grants U1836204, U1936108, 61572221, 61433006 and U1401258, University of South China University research foundation under grant 190XQD121, Teaching Reform Foundation under grant 2019YB-XJG30, Natural Science Foundation of Hunan Province of China under grant 2021JJ40468, Hunan Province research foundation under grant 19C1624, and the Ministry of Education Humanities and Foundation on Humanities and Social Sciences under grant 20YJC880027. This work is also partly supported by the National Science Foundation under grant CNS 1526190.


6.**Wenlong Tian**, Ruixuan Li, Cheng-Zhong Xu, Zhiyong Xu:Sed-Dedup: An efficient secure deduplication system with data modifications. Concurr. Comput. Pract. Exp. 33(15) (2021) [pdf](/papers/2021CCPE.pdf) 

7.**田纹龙**, 刘征海, 刘洋. 面向专业认证的UML建模语言课程教学改革研究[J]. 教育信息化论坛, 2022, 6(3):3.

8.Huikang Cao, Ruixuan Li, **Wenlong Tian**, Zhiyong Xu, Weijun Xiao:Blockchain-based accountability for multi-party oblivious RAM. J. Parallel Distributed Comput. 137: 224-237 (2020) (co-first Author) [pdf](/papers/2020JPDC_ORAM.pdf)

9.Dongdong Yue, Ruixuan Li, Yan Zhang, **Wenlong Tian**, Yongfeng Huang:Blockchain-based verification framework for data integrity in edge-cloud storage. J. Parallel Distributed Comput. 146: 1-14 (2020) [pdf](/papers/2020_JPDC_Blockchain.pdf)

10.何婷婷，**田纹龙**: 云环境下教师学习共同体的隐私保护--基于ORAM与群签名的融合技术. 现代教育技术, 2019, 000(001):79-85. (CSSCI)

11.Shuoyi Zhao, Ruixuan Li, **Wenlong Tian**, Weijun Xiao, Xinhua Dong, Dongjie Liao, Samee U. Khan, Keqin Li:Divide-and-conquer approach for solving singular value decomposition based on MapReduce. Concurr. Comput. Pract. Exp. 28(2): 331-350 (2016)  [pdf](/papers/2016CCPE.pdf)