# 论文仓库

Created: Sep 4, 2020 4:31 PM

不断完善中，欢迎补充Slide地址~


初衷是对不久前的KBQA调研做一个总结，未来可能会整理成一个多个KG方向资源的仓库

# **KBQA-paper**

## **KBQA系统**

### **分阶段生成**

1. Semantic parsing via staged query graph generation: Question answering with knowledge base(ACL2015 MS Wen-tau Yih) SP方法开山之作
2. Formal Query Building with Query Structure Prediction for Complex Question Answering over Knowledge Base(AAAI2020 东南大学陈永锐)
3. SPARQA: skeleton-based semantic parsing for complex questions over knowledge bases（AAAI 2020 南京大学）
4. Query Graph Generation for Answering Multi-hop Complex Questions from Knowledge Bases(ACL2020 SMU 蓝韵诗)
5. Knowledge base question answering via encoding of complex query graphs(EMNLP2018 上交)
6. A state-transition framework to answer complex questions over knowledge base(EMNLP2018 北大胡森)
7. Answering Complex Questions by Combining Information from Curated and Extracted Knowledge Bases（ACL2020）

### **IR**
1. Open Domain Question Answering Using Early Fusion of Knowledge Bases and Text（EMNLP 2018 Googel Sun haitian)
2. PullNet: Open domain question answering with iterative retrieval on knowledge bases and text(EMNLP 2019 Googel Sun haitian)
3. Improving Multi-hop Knowledge Base Question Answering by Learning Intermediate Supervision Signals（WSDM2021 SMU 蓝韵诗）

### **其他方法**
1. Case-based Reasoning for Natural Language Queries over Knowledge Bases （Google 2021）
2. TransferNet: An Effective and Transparent Framework for Multi-hop Question Answering over Relation Graph(2021 清华史佳欣)

### **模板**

1. KBQA: Learning question answering over QA corpora and knowledge bases（PVLDB2018 复旦崔万云）
2. Question answering over knowledge graphs: Question understanding via template decomposition(PVLDB2018 复旦郑卫国)
3. Leveraging frequent query substructures to generate formal queries for complex question answering(EMNLP2019 南京大学)
4. Automated template generation for question answering over knowledge graphs(WWW2017 马普所)

### **Seq2Seq**

1. Constraint-based question answering with knowledge graph(COLING2016)
2. Sequence-based structured prediction for semantic parsing(ACL2016)
3. Language to logical form with neural attention(ACL2016)
4. Neural symbolic machines: Learning semantic parsers on freebase with weak supervision(ACL2017)
5. Learning a neural semantic parser from user feedback(ACL2017)
6. Coarse-to-fine decoding for neural semantic parsing(ACL2018)
7. A syntactic neural model for general-purpose code generation（ACL2017）
8. Sequence-to-action: End-to-end semantic graph generation for semantic parsing(ACL2018)
9. Language to logical form with neural attention（ACL2016）

### **复杂问题分解**

1. The web as a knowledge-base for answering complex questions（NAACL2018）CWQ数据集 基于搜索引擎+RC回答子问题  [GitHub](https://github.com/alontalmor/WebAsKB)
2. EDG-based Question Decomposition for ComplexQuestion Answering over Knowledge Bases(ISWC2021 南京大学)
3. Complex question decomposition for semantic parsing（ACL 2020 国防科大）
4. SPARQA: skeleton-based semantic parsing for complex questions over knowledge bases（AAAI 2020 南京大学）
5. BREAK it down: A question understanding benchmark(TACL 2019 AI2)
6. Text modular networks: learning to decompose tasks in the language of existing models(NAACL 2021 AI2)
7. KQA Pro: A Large-Scale Dataset with Interpretable Programs and Accurate SPARQLs for Complex Question Answering over Knowledge Base（WWW2021 清华史佳欣）
8. Multi-hop reading comprehension through question decomposition and rescoring(ACL 2019 RC的分解)
9. Unsupervised question decomposition for question answering （EMNLP 2020 FBAI）
10. Enhancing key-value memory neural networks for knowledge based question answering（NAACL2019）



## **综述**

1. Survey on challenges of Question Answering in the Semantic Web（Semantic Web2017）
2. A Survey on Complex Knowledge Base Question Answering: Methods, Challenges and Solutions （IJCAI 2021 SMU 蓝韵诗）
3. Complex Knowledge Base Question Answering:A Survey(蓝韵诗 2021)
4. Core Techniques of Question Answering Systems over Knowledge Bases : a Survey（2017）
5. A Survey on Complex Question Answering over Knowledge Base: Recent Advances and Challenges（2020 阿里巴巴），中文翻译：[https://zhuanlan.zhihu.com/p/134090164](https://zhuanlan.zhihu.com/p/134090164)
6. Introduction to Neural Network based Approaches for Question Answering over Knowledge Graphs(2019)
7. Question Answering over Curated and Open Web Sources (SIGIR2020 Tutorial)  [Slide](http://people.mpi-inf.mpg.de/~rsaharo/sigir20slides.pdf) 

## **子任务**

### **NER**

### **Relation Linking/Detection**

1. Old is Gold: Linguistic Driven Approach for Entity and Relation Linking of Short Text（NAACL 2019）([Falcon系统](https://labs.tib.eu/falcon/) [GitHub](https://github.com/AhmadSakor/falcon))
2. EARL: Joint entity and relation linking for question answering over knowledge graphs （ISWC 2018）
3. Leveraging semantic parsing for relation linking over knowledge bases (ISWC2020 IBM Watson) (SOTA)
4. Generative Relation Linking for Question Answering over Knowledge Bases(ISWC2021 IBM Watson)
5. FALCON 2.0: An Entity and Relation Linking Tool over Wikidata （ISWC 2019）（[Falcon2.0](https://labs.tib.eu/falcon/falcon2/)  [GitHub](https://github.com/SDM-TIB/Falcon2.0)）（开源系统SOTA）
6. Scalable knowledge graph construction over text using deep learning based predicate mapping （WWW2019）
7. Learning Representation Mapping for Relation Detection in Knowledge Base Question Answering(ACL2019 南京大学)
8. PATTY: A taxonomy of relational patterns with semantic types （EMNLP 2012 马普所）
9. Towards Combinational Relation Linking over Knowledge Graphs （复旦）

### **Entity Linking**

1. LNN-EL: A Neuro-Symbolic Approach to Short-text Entity Linking （ACL2021 IBM Watson）
2. Autoregressive entity retrieval(ICLR 2021 FBAI)
3. Efficient One-Pass End-to-End Entity Linking for Questions(EMNLP 2020 FBAI)
4. Scalable Zero-shot Entity Linking with Dense Entity Retrieval(EMNLP 2020 FBAI)
5. PNEL: Pointer Network based End-To-End Entity Linking over Knowledge Graphs (ISWC 2020)
6. KBPearl: A knowledge base population system supported by joint entity and relation linking(PVLDB 2020)


## **Futrue direction**

### **可解释性**

### **鲁棒性**

### **多源知识融合**

### **对话QA**

## **数据集**

1. **ComplexQuestion**: Constraint-based question answering with knowledge graph(COLING2016)
微软亚研院周明组提出

    论文：[Constraint-Based Question Answering with Knowledge Graph](https://www.aclweb.org/anthology/C16-1236/)

    数据集：[https://github.com/JunweiBao/MulCQA/tree/ComplexQuestions](https://github.com/JunweiBao/MulCQA/tree/ComplexQuestions)

    简介：2100条（1300/800）

2. **ComplexWebQuestion**: 

    The web as a knowledge-base for answering complex questions(NAACL2018)
    
    子问题的回答基于搜索引擎上的RC
3. **WebQuestion** [train](http://nlp.stanford.edu/static/software/sempre/release-emnlp2013/lib/data/webquestions/dataset_11/webquestions.examples.train.json.bz2)   [test](http://nlp.stanford.edu/static/software/sempre/release-emnlp2013/lib/data/webquestions/dataset_11/webquestions.examples.test.json.bz2)

    论文：Semantic Parsing on Freebase from Question-Answer Pairs（EMNLP2013斯坦福）

    简介：5810条（3778/2032） 斯坦福大学，根据Google Suggest API构建
4. **WebQuestionSP**:

    Semantic Parsing via Staged Query Graph Generation: Question Answering with Knowledge Base（ACL 2015）
    
    微软yih-wen tau
5. **SimpleQuestion**

    论文：[Large-scale Simple Question Answering with Memory Networks](https://arxiv.org/pdf/1506.02075.pdf)（2015）

    数据集：[https://research.fb.com/downloads/babi/](https://research.fb.com/downloads/babi/)

    简介：108442条（75910/10845/21687）Freebase  全是一个三元组就可以回答的问题

6. **Free917**  
     [train](http://nlp.stanford.edu/static/software/sempre/release-emnlp2013/data/free917.train.examples.canonicalized.json.bz2)    [test](http://nlp.stanford.edu/static/software/sempre/release-emnlp2013/data/free917.test.examples.canonicalized.json.bz2)

    简介：917条  Freebase
7. **QALD series**:
资源地址：[https://github.com/ag-sc/QALD](https://github.com/ag-sc/QALD)

    论文

    QALD-7: [https://svn.aksw.org/papers/2017/ESWC_2017_QALD/public.pdf](https://svn.aksw.org/papers/2017/ESWC_2017_QALD/public.pdf)

    QALD-8: [http://ceur-ws.org/Vol-2241/paper-05.pdf](http://ceur-ws.org/Vol-2241/paper-05.pdf)

    QALD-9: [http://ceur-ws.org/Vol-2241/paper-06.pdf](http://ceur-ws.org/Vol-2241/paper-06.pdf)

    评测地址

    QALD-7: [http://gerbil-qa.aksw.org/gerbil/experiment?id=201706300001](http://gerbil-qa.aksw.org/gerbil/experiment?id=201706300001)

    QALD-8: [http://gerbil-qa.aksw.org/gerbil/experiment?id=201710220000](http://gerbil-qa.aksw.org/gerbil/experiment?id=201710220000)

    QALD-9: [http://gerbil-qa.aksw.org/gerbil/experiment?id=201810080002](http://gerbil-qa.aksw.org/gerbil/experiment?id=201810080002)

8. **LC-QuAD**: [http://lc-quad.sda.tech/lcquad1.0.html](http://lc-quad.sda.tech/lcquad1.0.html)
9. **LC-QuAD 2.0**: [http://lc-quad.sda.tech/](http://lc-quad.sda.tech/)
10. **KQA Pro** 
    
    [KQA Pro: A Large-Scale Dataset with Interpretable Programs and Accurate SPARQLs for Complex Question Answering over Knowledge Base(WWW 2021 清华)](https://arxiv.org/abs/2007.03875)

    [github](https://github.com/shijx12/KQAPro_Baselines)

    [homepage](http://thukeg.gitee.io/kqa-pro/)

    wikidata，120K有SPARQL标注，KB子集
11. **CRONKGQA** 

    [Question Answering over Temporal Knowledge Graphs（ACL2021)](https://aclanthology.org/2021.acl-long.520/)

    [github](https://github.com/apoorvumang/CronKGQA)

    时间问答数据集，wikidata，410K,KB子集
12. **CoQA**
13. **GraphQuestion**  

    论文：[On Generating Characteristic-rich Question Sets for QA Evaluation](https://www.aclweb.org/anthology/D16-1054/)（2016）

    数据集：[https://github.com/ysu1989/GraphQuestions](https://github.com/ysu1989/GraphQuestions)

    简介：Freebase

12. **30M Factoid Question**

    论文：[Generating Factoid QuestionsWith Recurrent Neural Networks: The 30M Factoid Question-Answer Corpus](https://arxiv.org/pdf/1603.06807.pdf)

    数据集：[https://academictorrents.com/details/973fb709bdb9db6066213bbc5529482a190098ce](https://academictorrents.com/details/973fb709bdb9db6066213bbc5529482a190098ce)

    简介：30M条问答对

13. **MetaQA
数据集：**[https://drive.google.com/drive/folders/0B-36Uca2AvwhTWVFSUZqRXVtbUE](https://drive.google.com/drive/folders/0B-36Uca2AvwhTWVFSUZqRXVtbUE)
14. **CSQA**
15. **ReClor**
论文: ReClor: A Reading Comprehension Dataset Requiring Logical Reasoning(ICLR2020)
项目地址：[http://whyu.me/reclor/](http://whyu.me/reclor/)
16. **CLEVRER**
论文: [CLEVRER: CoLlision Events for Video REpresentation and Reasoning(ICLR2020)](https://arxiv.org/pdf/1910.01442.pdf)
项目地址: [http://clevrer.csail.mit.edu/](http://clevrer.csail.mit.edu/)
17. **CommonsenseQA**
论文: Cosmos QA: Machine Reading Comprehension with Contextual Commonsense Reasoning
特拉维夫大学常识问答任务,SOTA(0.9179)
项目地址: [https://www.tau-nlp.org/commonsenseqa](https://www.tau-nlp.org/commonsenseqa)
18. **Hotpot QA**
19. **TriviaQA** 阅读理解数据集
论文:TriviaQA: A Large Scale Distantly Supervised Challenge Dataset for Reading Comprehension
20. **Mutual** 对话数据集
西湖大学张岳组
**论文地址：**[MuTual: A Dataset for Multi-Turn Dialogue Reasoning](http://arxiv.org/abs/2004.04494)
**github地址：**[https://github.com/Nealcly/MuTu](https://link.zhihu.com/?target=https%3A//github.com/Nealcly/MuTual)

## 优秀开源工具

1. SEMPRE: Semantic Parsing with Execution 斯坦福
[项目地址](https://nlp.stanford.edu/software/sempre/)     [tutorial](https://github.com/percyliang/sempre/blob/master/TUTORIAL.md)    [GitHub](https://github.com/percyliang/sempre)
    - **简介：**NL转换成逻辑形式，支持lambda calculus，lambda DCS等
2. Stanza: A Python NLP Library for Many Human Languages斯坦福官方NLP工具包
ACL2020 demo

## 其他开源工具

1. 中文近义词  [https://github.com/chatopera/Synonyms](https://github.com/chatopera/Synonyms)

## 讲习班 Slide

学习讲习班大佬们的总结，可以迅速了解一个领域

可参考刘知远老师给出的清单 [如何不出国门走进NLP学术前沿（刘知远）](https://zhuanlan.zhihu.com/p/35380020)

主要有：中国中文信息学会（CIPS）中国计算机学会（CCF)  中国人工智能学会（CAAI）等

1. [KEQA 2019(南京大学)](http://ws.nju.edu.cn/conf/keqa2019/)
    1. [Natural Language Question Answering over Knowledge Graph](http://ws.nju.edu.cn/conf/keqa2019/resources/%E9%82%B9%E7%A3%8A%20--%20Question%20Answering%20Over%20Knowledge%20Graph.pdf)  邹磊 (北京大学）
    2. [Matching Questions and Answers in Dialogues from Online Forums](http://ws.nju.edu.cn/conf/keqa2019/resources/%E6%9C%B1%E5%85%B6%E7%AB%8B%20--%20Matching%20Questions%20and%20Answers%20in%20Dialogues%20from%20Online%20Forums-more.pdf)  朱其立 (上海交通大学）
    3. [知识图谱中的关联搜索](http://ws.nju.edu.cn/conf/keqa2019/resources/%E7%A8%8B%E9%BE%9A%20--%20%E7%9F%A5%E8%AF%86%E5%9B%BE%E8%B0%B1%E4%B8%AD%E7%9A%84%E5%85%B3%E8%81%94%E6%90%9C%E7%B4%A2.pdf) 程龚 (南京大学）
    4. [Understanding User Generated Information](http://ws.nju.edu.cn/conf/keqa2019/resources/%E9%92%B1%E9%93%81%E4%BA%91%20--%20Understanding%20User%20Generated%20Data.pdf) 钱铁云 (武汉大学）
    5. [事理图谱的构建及应用](http://ws.nju.edu.cn/conf/keqa2019/resources/%E4%B8%81%E6%95%88%20--%20%E4%BA%8B%E7%90%86%E5%9B%BE%E8%B0%B1%E7%9A%84%E6%9E%84%E5%BB%BA%E5%8F%8A%E5%BA%94%E7%94%A8.pdf) 丁效 (哈尔滨工业大学）
    6. [搜索引擎中的智能问答](http://ws.nju.edu.cn/conf/keqa2019/resources/%E5%BC%A0%E5%A5%87%20--%20%E6%90%9C%E7%B4%A2%E5%BC%95%E6%93%8E%E4%B8%AD%E7%9A%84%E6%99%BA%E8%83%BD%E9%97%AE%E7%AD%94.pdf) 张奇 (复旦大学）
2. CCF 学科前沿讲习班第 108 期
    1. 大规模图神经网络与实践 杨红霞 （阿里巴巴）
    2. 知识计算即服务：赋能企业知识化转型 袁晶（华为云）
    3. [知识图谱融合方法](https://github.com/nju-websoft/KnowledgeGraphFusion) 胡伟(南京大学)
    4. 生活领域知识图谱的构建及应用 张富峥（美团点评）
    5. 知识图谱与众包数据库 李国良（清华大学）
    6. 大规模知识图谱和自动化构建关键技术及应用 肖仰华（复旦大学）
3. [CIPS 前沿讲习班 2019](http://conference.cipsc.org.cn/ssatt2019/) 
    1. 面向自然语言处理的深度学习基础 邱锡鹏（复旦大学）颜航（复旦大学）
    2. 开放域语义解析 韩先培（中国科学院软件研究所）陈波（中国科学院软件研究所）
    3. 图神经网络在自然语言处理中的应用 张岳（西湖大学）
    4. 基于深度学习的机器阅读理解 崔一鸣（科大讯飞）
    5. 问答系统 唐都钰（微软亚洲研究院）段楠（微软亚洲研究院）
    6. 任务型对话系统 车万翔（哈尔滨工业大学）车万翔（哈尔滨工业大学）
    7. 人工智能在人机对话系统中的技术现状与挑战 严睿（北京大学）
4. [CIPS 前沿讲习班 2018](http://conference.cipsc.org.cn/ssatt2018/)
    1. 语义表示学习	刘知远（清华大学）
    2. 深度学习与词法句法语义分析	车万翔（哈尔滨工业大学）
    3. 深度学习与机器翻译 张家俊（中国科学院自动化研究所）涂兆鹏（腾讯AI Lab）
    4. 深度强化学习与GAN基础 俞扬（南京大学）
    5. 信息检索中的深度强化学习新进展	徐君（中国科学院计算技术研究所）庞亮（中国科学院计算技术研究所）
    6. 对话系统中的深度学习进展 李纪为（香侬科技）
    7. 知识图谱中的深度学习新进展 William Wang （University California, Santa Barbara）
5. [CIPS 前沿讲习班 2017](http://www.cipsc.org.cn/att2017/)  
    1. 深度学习基础知识 邱锡鹏，复旦大学
    2. 深度学习工具实战 龚经经，复旦大学
    3. 深度学习与词法句法语义分析 车万翔，哈尔滨工业大学
    4. 深度学习与知识获取 刘康，中科院自动化所
    5. 深度学习与机器翻译 熊德意，苏州大学
    6. 深度学习与自动问答 冯岩松，北京大学
    7. 深度学习与社会计算 赵鑫，中国人民大学
    8. 深度学习与信息检索 郭嘉丰，中科院计算所
6.
