# Database and Bigdata
AI for DB, DB for AI and classical papers.

# AI for DB and AI in DB
|Paper|Summary|Year|
|-|-|-|
|SOSD: A Benchmark for Learned Indexes. | |  CoRR abs/1911. |
|ALEX: An Updatable Adaptive Learned Index. | |  SIGMOD 2020 |
|Learning Multi-dimensional Indexes. | |  SIGMOD 2020 |
|Neo: A Learned Query Optimizer. | 使用DRL进行Query优化| PVLDB 2019. |
|Plan-Structured Deep Neural Network Models for Query Performance Prediction. | Query Performance Prediction(QPP) |  PVLDB 2019. |
|DBEst: Revisiting Approximate Query Processing Engines with Machine Learning Models. | | SIGMOD 2019, 1553-1570. | 
|AI Meets AI: Leveraging Query Executions to Improve Index Recommendations. | 微软索引推荐模型 | SIGMOD 2019, 1241-1258. | 
|Automatically Indexing Millions of Databases in Microsoft Azure SQL Database | 微软落地到Azure上的工程实践 | 2019 |
|FITing-Tree: A Data-aware Index Structure. | |  SIGMOD 2019,1189-1206. |
|An End-to-End Automatic Cloud Database Tuning System Using Deep Reinforcement Learning. | CDBTune, 采用DRL进行参数调优 |  SIGMOD 2019, 415-432. | 
|QTune: A Query-Aware Database Tuning System with Deep Reinforcement Learning| 采用DRL进行参数调优, 支持workload和operator级别。 [Code](https://github.com/opengauss-mirror/openGauss-server/tree/master/src/gausskernel/dbmind/xtuner) | VLDB 2019 |
|SkinnerDB: Regret-Bounded Query Evaluation via Reinforcement Learning. | |  SIGMOD 2019, 1153-1170. | 
|SageDB: A Learned Database System. | 采用CDF构建learned index |  CIDR 2019. | 
|Learning State Representations for Query Optimization with Deep Reinforcement Learning.  | |  arXiv:1803. |
|Deep Unsupervised Cardinality Estimation. | [Blog](https://rise.cs.berkeley.edu/blog/sql-query-optimization-meets-deep-reinforcement-learning/) |  PVLDB 13(3), 279 - 292, 2019. |
|Towards a Learning Optimizer for Shared Clouds. | |  PVLDB 12(3), 210-222, 2018. | 
|Learning to Optimize Join Queries With Deep Reinforcement Learning | | 2018 |
|Query2Vec: An Evaluation of NLP Techniques for Generalized Workload Analytics| Query向量化方法，一种NLP手段 | 2018 |
|The Case for Learned Index Structures. | | SIGMOD 2018: 489-504. | 
|Query-based Workload Forecasting for Self-Driving Database Management Systems. | CMU Andy团队预测未来SQL语句的Paper [Code](https://github.com/malin1993ml/QueryBot5000) |  SIGMOD 2018, 631-645. |
|Automatic Database Management System Tuning Through Large-scale Machine Learning. | OtterTune, 是比较早的使用ML的方式进行数据库参数调优的尝试 |  SIGMOD 2017, 1009-1024. |
|Learning Memory Access Patterns. | |  ICML 2018: 1924-1933. |
|Self-Driving Database Management Systems. | Peloton, archived, [Code](https://github.com/cmu-db/peloton) |  CIDR 2017. | 
|Database Learning: Toward a Database that Becomes Smarter Every Time. | |  SIGMOD 2017, 587-602. | 
|Approximation of LRU Caches Miss Rate: Application to Power-law Popularities | 结论：LRU缓存命中率符合幂率分布 | 2017 |

# DB for AI
## System for Big Data
* DB4ML - An In-Memory Database Kernel with Machine Learning Support. SIGMOD 2020, 159-173. &nbsp;[Paper](https://dl.acm.org/doi/10.1145/3318464.3380575)

* Optimizing Machine Learning Workloads in Collaborative Environments. SIGMOD 2020, 1701-1716. &nbsp;[Paper](https://dl.acm.org/doi/10.1145/3318464.3389715)

* Dynamic Parameter Allocation in Parameter Servers. PVLDB 13(11), 1877 - 1890, 2020. &nbsp;[Paper](http://www.vldb.org/pvldb/vol13/p1877-renz-wieland.pdf)

* Crossbow: Scaling Deep Learning with Small Batch Sizes on Multi-GPU Servers. PVLDB 12(11), 1399-1413, 2019. &nbsp;[Paper](http://www.vldb.org/pvldb/vol12/p1399-koliousis.pdf)

* PS2: Parameter Server on Spark. SIGMOD 2019: 376-388. &nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3299869.3314038)

* MLlib*: Fast Training of GLMs Using Spark MLlib. ICDE 2019: 1778-1789. &nbsp;[Paper](https://ieeexplore.ieee.org/document/8731565/)

* On Optimizing Operator Fusion Plans for Large-Scale Machine Learning in SystemML. PVLDB 11(12): 1755-1768, 2018.&nbsp;[Paper](http://www.vldb.org/pvldb/vol11/p1755-boehm.pdf)

* FlexPS: Flexible Parallelism Control in Parameter Server Architecture. PVLDB 11(5): 566-579, 2018.&nbsp;[Paper](http://www.vldb.org/pvldb/vol11/p566-huang.pdf)

* A Cost-based Optimizer for Gradient Descent Optimization. SIGMOD 2017, 977-992. &nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3035918.3064042)

* SPOOF: Sum-Product Optimization and Operator Fusion for Large-Scale Machine Learning. CIDR 2017. &nbsp;[Paper](http://cidrdb.org/cidr2017/papers/p3-elgamal-cidr17.pdf)

* SystemML: Declarative Machine Learning on Spark. PVLDB 9(13): 1425-1436, 2016.&nbsp;[Paper](http://www.vldb.org/pvldb/vol9/p1425-boehm.pdf)&nbsp;[Project](https://systemml.apache.org/)

* MLbase: A Distributed Machine-learning System. CIDR 2013.&nbsp;[Paper](http://cidrdb.org/cidr2013/Papers/CIDR13_Paper118.pdf) &nbsp;[Project](http://mlbase.org/)

### Pipeline

* An Intermediate Representation for Optimizing Machine Learning Pipelines. PVLDB 12(11), 1553-1567, 2019. &nbsp;[Paper](http://www.vldb.org/pvldb/vol12/p1553-kunft.pdf)

* Democratizing Data Science through Interactive Curation of ML Pipelines. SIGMOD 2019, 1171-1188. &nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3299869.3319863)

* Helix: Holistic Optimization for Accelerating Iterative Machine Learning. PVLDB 12(4), 446-460, 2018.&nbsp;[Paper](http://www.vldb.org/pvldb/vol12/p446-xin.pdf)

* KeystoneML: Optimizing pipelines for large-scale advanced analytics. ICDE 2017: 535–546. &nbsp;[Paper](https://ieeexplore.ieee.org/document/7930005)&nbsp;[Project](http://keystone-ml.org/)

### Compression

* Tuple-oriented Compression for Large-scale Mini-batch Stochastic Gradient Descent. SIGMOD 2019, 1517-1534. &nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3299869.3300070)

* SketchML: Accelerating Distributed Machine Learning with Data Sketches. SIGMOD 2018, 1269-1284.&nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3183713.3196894)

* Compressed Linear Algebra for Large-Scale Machine Learning. PVLDB 9(12): 960-971, 2016.&nbsp;[Paper](http://www.vldb.org/pvldb/vol9/p960-elgohary.pdf)

### Linear Algebra

* SPORES: Sum-Product Optimization via Relational Equality Saturation for Large Scale Linear Algebra. PVLDB 13(11), 1919 - 1932, 2020. &nbsp;[Paper](http://www.vldb.org/pvldb/vol13/p1919-wang.pdf)

* Enabling and Optimizing Non-linear Feature Interactions in Linear Algebra Over Normalized Data. SIGMOD 2019, 1571-1588. &nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3299869.3319878)

* Accelerating Generalized Linear Models with MLWeaving: A One-Size-Fits-All System for Any-precision Learning. PVLDB 12(7): 807-821, 2019. &nbsp;[Paper](http://www.vldb.org/pvldb/vol12/p807-wang.pdf)

* A Comparative Evaluation of Systems for Scalable Linear Algebra-based Analytics. PVLDB 11(13): 2168-2182, 2018. &nbsp;[Paper](http://www.vldb.org/pvldb/vol11/p2168-thomas.pdf)&nbsp;[Project](https://adalabucsd.github.io/slab.html)

* Towards Linear Algebra over Normalized Data. PVLDB 10(11): 1214-1225, 2017.&nbsp;[Paper](http://www.vldb.org/pvldb/vol10/p1214-chen.pdf)

* Scalable Linear Algebra on a Relational Database System. ICDE 2017: 523-534. .&nbsp;[Paper](https://ieeexplore.ieee.org/document/7930004)

* Learning Generalized Linear Models Over Normalized Data. SIGMOD 2015: 1969-1984. &nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=2723372.2723713)

### Rely on Database System
* Vertica-ML: Distributed Machine Learning in Vertica Database. SIGMOD 2020, pages: 755-768. &nbsp;[Paper](https://dl.acm.org/doi/10.1145/3318464.3386137)

* Declarative Recursive Computation on an RDBMS. PVLDB 12(7): 822-835, 2019. &nbsp;[Paper](http://www.vldb.org/pvldb/vol12/p822-jankov.pdf)

* In-Database Learning with Sparse Tensors.  PODS 2018: 325-340.  &nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3196959.3196960)

* ColumnML: Column-Store Machine Learning with On-The-Fly Data Transformation. PVLDB 12(4), 348-361, 2018.&nbsp;[Paper](http://www.vldb.org/pvldb/vol12/p348-kara.pdf)

* The BUDS Language for Distributed Bayesian Machine Learning. SIGMOD 2017, 961-976.&nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3035918.3035937)

* Are Key-Foreign Key Joins Safe to Avoid when Learning High-Capacity Classifiers? PVLDB 11(3), 366-379, 2017.&nbsp;[Paper](http://www.vldb.org/pvldb/vol11/p366-shah.pdf)

* Learning Linear Regression Models over Factorized Joins. SIGMOD 2016, 3-18.&nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=2882903.2882939)

* The MADlib Analytics Library or MAD Skills, the SQL. PVLDB 5(12): 1700-1711, 2012.&nbsp;[Paper](http://www.vldb.org/pvldb/2/vldb09-219.pdf)

### Specific Algorithms

* Sketching Linear Classifiers over Data Streams. SIGMOD 2018: 757-772. &nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3183713.3196930) &nbsp;[Code](https://github.com/stanford-futuredata/wmsketch)

* DimBoost: Boosting Gradient Boosting Decision Tree to Higher Dimensions. SIGMOD 2018, 1363-1376. &nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3183713.3196892)

* Scalable Training of Hierarchical Topic Models. PVLDB 11(7), 826-839, 2018. &nbsp;[Paper](http://www.vldb.org/pvldb/vol11/p826-chen.pdf)

* LDA*: A Robust and Large-scale Topic Modeling System. PVLDB 10(11), 1406-1417, 2017. &nbsp;[Paper](http://www.vldb.org/pvldb/vol10/p1406-yu.pdf)

* Scalable Kernel Density Classification via Threshold-Based Pruning. SIGMOD 2017, 945-959.&nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3035918.3064035)

* Heterogeneity-aware Distributed Parameter Servers. SIGMOD 2017: 463-478.&nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3035918.3035933)

* WarpLDA: a Cache Efficient O(1) Algorithm for Latent Dirichlet Allocation. PVLDB 9(10): 744-755, 2016. &nbsp;[Paper](http://www.vldb.org/pvldb/vol9/p744-chen.pdf)

* Exploiting Matrix Dependency for Efficient Distributed Matrix Computation. SIGMOD 2015: 93-105.&nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=2723372.2723712)

### Training Data Acquisition

* BlinkML: Efficient Maximum Likelihood Estimation with Probabilistic Guarantees. SIGMOD 2019: 1135-1152.&nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3299869.3300077)

* Snuba: Automating Weak Supervision to Label Training Data. PVLDB 12(3), 223-236, 2018.&nbsp;[Paper](http://www.vldb.org/pvldb/vol12/p223-varma.pdf)

* Snorkel: Rapid Training Data Creation with Weak Supervision. PVLDB 11(3), 269-282, 2017.&nbsp;[Paper](http://www.vldb.org/pvldb/vol11/p269-ratner.pdf)

# Classical
to be continued.

# References
- https://github.com/jinw18/Readings_MLDB
