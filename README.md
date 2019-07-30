# Scalable ML and ML for Database System
Paper list about adopting machine learning techniques into data management tasks. Mainly consider ones published in top data management venues.

Other categories:
[Application](app.md)
[ML for DB](ml-for-db.md)

## <a name='scale-ml'> Large Scale Machine Learning

### System for Big Data
* PS2: Parameter Server on Spark. SIGMOD 2019: 376-388. &nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3299869.3314038)

* MLlib*: Fast Training of GLMs Using Spark MLlib. ICDE 2019: 1778-1789. &nbsp;[Paper](https://ieeexplore.ieee.org/document/8731565/)

* Helix: Holistic Optimization for Accelerating Iterative Machine Learning. PVLDB 12(4), 446-460, 2018.&nbsp;[Paper](http://www.vldb.org/pvldb/vol12/p446-xin.pdf)

* On Optimizing Operator Fusion Plans for Large-Scale Machine Learning in SystemML. PVLDB 11(12): 1755-1768, 2018.&nbsp;[Paper](http://www.vldb.org/pvldb/vol11/p1755-boehm.pdf)

* A Cost-based Optimizer for Gradient Descent Optimization. SIGMOD 2017, 977-992. &nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3035918.3064042)

* SPOOF: Sum-Product Optimization and Operator Fusion for Large-Scale Machine Learning. CIDR 2017. &nbsp;[Paper](http://cidrdb.org/cidr2017/papers/p3-elgamal-cidr17.pdf)

* KeystoneML: Optimizing pipelines for large-scale advanced analytics. ICDE 2017: 535–546. &nbsp;[Paper](https://ieeexplore.ieee.org/document/7930005)&nbsp;[Project](http://keystone-ml.org/)

* SystemML: Declarative Machine Learning on Spark. PVLDB 9(13): 1425-1436, 2016.&nbsp;[Paper](http://www.vldb.org/pvldb/vol9/p1425-boehm.pdf)&nbsp;[Project](https://systemml.apache.org/)

* MLbase: A Distributed Machine-learning System. CIDR 2013.&nbsp;[Paper](http://cidrdb.org/cidr2013/Papers/CIDR13_Paper118.pdf) &nbsp;[Project](http://mlbase.org/)

### Compression

* Tuple-oriented Compression for Large-scale Mini-batch Stochastic Gradient Descent. SIGMOD 2019, 1517-1534. &nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3299869.3300070)

* SketchML: Accelerating Distributed Machine Learning with Data Sketches. SIGMOD 2018, 1269-1284.&nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3183713.3196894)

* Compressed Linear Algebra for Large-Scale Machine Learning. PVLDB 9(12): 960-971, 2016.&nbsp;[Paper](http://www.vldb.org/pvldb/vol9/p960-elgohary.pdf)

### Linear Algebra
* Enabling and Optimizing Non-linear Feature Interactions in Linear Algebra Over Normalized Data. SIGMOD 2019, 1571-1588. &nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3299869.3319878)

* Accelerating Generalized Linear Models with MLWeaving: A One-Size-Fits-All System for Any-precision Learning. PVLDB 12(7): 807-821, 2019. &nbsp;[Paper](http://www.vldb.org/pvldb/vol12/p807-wang.pdf)

* A Comparative Evaluation of Systems for Scalable Linear Algebra-based Analytics. PVLDB 11(13): 2168-2182, 2018. &nbsp;[Paper](http://www.vldb.org/pvldb/vol11/p2168-thomas.pdf)&nbsp;[Project](https://adalabucsd.github.io/slab.html)

* Towards Linear Algebra over Normalized Data. PVLDB 10(11): 1214-1225, 2017.&nbsp;[Paper](http://www.vldb.org/pvldb/vol10/p1214-chen.pdf)

* Scalable Linear Algebra on a Relational Database System. ICDE 2017: 523-534. .&nbsp;[Paper](https://ieeexplore.ieee.org/document/7930004)

* Learning Generalized Linear Models Over Normalized Data. SIGMOD 2015: 1969-1984. &nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=2723372.2723713)

### Relational DBMS
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
