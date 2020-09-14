不断完善中

# **KBQA-paper**

## **KBQA系统**

### **分阶段生成**

1. Formal Query Building with Query Structure Prediction for Complex Question Answering over Knowledge Base(AAAI2020)东南大学陈永锐
2. Answering Complex Questions by Combining Information from Curated and Extracted Knowledge Bases(ACL2020)
3. Query Graph Generation for Answering Multi-hop Complex Questions from Knowledge Bases(ACL2020)
4. Knowledge base question answering via encoding of complex query graphs(EMNLP2018)
5. Semantic parsing via staged query graph generation: Question answering with knowledge base(ACL2015)
6. A state-transition framework to answer complex questions over knowledge base(EMNLP2018)
7. Answering Complex Questions by Combining Information from Curated and Extracted Knowledge Bases（ACL2020）

### **模板**

1. KBQA: Learning question answering over QA corpora and knowledge bases（VLDB2018）
2. Question answering over knowledge graphs: Question understanding via template decomposition(VLDB2018)
3. Leveraging frequent query substructures to generate formal queries for complex question answering(EMNLP2019)
4. Automated template generation for question answering over knowledge graphs(WWW2017)

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

1. Enhancing key-value memory neural networks for knowledge based question answering（NAACL2019）
2. The web as a knowledge-base for answering complex questions（NAACL2018）基于搜索引擎+RC回答子问题  [GitHub](https://github.com/alontalmor/WebAsKB)
3. Complex question decomposition for semantic parsing（ACL2020）

## **综述**

1. Survey on challenges of Question Answering in the Semantic Web（Semantic Web2017）
2. Core Techniques of Question Answering Systems over Knowledge Bases : a Survey（2017）
3. A Survey on Complex Question Answering over Knowledge Base: Recent Advances and Challenges（2020）阿里巴巴，中文翻译：[https://zhuanlan.zhihu.com/p/134090164](https://zhuanlan.zhihu.com/p/134090164)
4. Introduction to Neural Network based Approaches for Question Answering over Knowledge Graphs(2019)
5. Question Answering over Curated and Open Web Sources (SIGIR2020 Tutorial)  [Slide](http://people.mpi-inf.mpg.de/~rsaharo/sigir20slides.pdf) 

## **子任务**

### **NER**

### **Relation Linking**

### **Entity Linking**

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

2. **ComplexWebQuestion**: The web as a knowledge-base for answering complex questions(NAACL2018)
子问题的回答基于搜索引擎上的RC
3. **WebQuestion** [train](http://nlp.stanford.edu/static/software/sempre/release-emnlp2013/lib/data/webquestions/dataset_11/webquestions.examples.train.json.bz2)   [test](http://nlp.stanford.edu/static/software/sempre/release-emnlp2013/lib/data/webquestions/dataset_11/webquestions.examples.test.json.bz2)
论文：Semantic Parsing on Freebase from Question-Answer Pairs（EMNLP2013斯坦福）
简介：5810条（3778/2032） 斯坦福大学，根据Google Suggest API构建
4. **WebQuestionSP**:
5. **SimpleQuestion**

    论文：[Large-scale Simple Question Answering with Memory Networks](https://arxiv.org/pdf/1506.02075.pdf)（2015）

    数据集：[https://research.fb.com/downloads/babi/](https://research.fb.com/downloads/babi/)

    简介：108442条（75910/10845/21687）Freebase  全是一个三元组就可以回答的问题

6. **Free917**   [train](http://nlp.stanford.edu/static/software/sempre/release-emnlp2013/data/free917.train.examples.canonicalized.json.bz2)    [test](http://nlp.stanford.edu/static/software/sempre/release-emnlp2013/data/free917.test.examples.canonicalized.json.bz2)
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
10. **CoQA**
11. **GraphQuestion**  

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
