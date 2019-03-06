# Scalable ML and ML for Database System
Paper list about adopting machine learning techniques into data management tasks. Mainly consider ones published in top data management venues.

For stand alone ML Systems, please refer to [Application](app.md).

## <a name='ml-in-db'> Machine Learning in Database System
* A-Tree: A Bounded Approximate Index Structure. 	arXiv:1801.10207  &nbsp;[Paper](https://arxiv.org/abs/1801.10207)
  
* Learning State Representations for Query Optimization with Deep Reinforcement Learning. arXiv:1803.08604  &nbsp;[Paper](https://arxiv.org/abs/1803.08604) 

* Learning to Optimize Join Queries With Deep Reinforcement Learning. arXiv:1808.03196 &nbsp;[Paper](https://arxiv.org/abs/1808.03196) &nbsp; [Blog](https://rise.cs.berkeley.edu/blog/sql-query-optimization-meets-deep-reinforcement-learning/)

* Towards a Learning Optimizer for Shared Clouds. PVLDB 12(3), 210-222, 2018. &nbsp;[Paper](http://www.vldb.org/pvldb/vol12/p210-wu.pdf)
* The Case for Learned Index Structures. SIGMOD 2018: 489-504. &nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3183713.3196909)
  
* Query-based Workload Forecasting for Self-Driving Database Management Systems. SIGMOD 2018, 631-645. &nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3183713.3196908)&nbsp;[Code](https://github.com/malin1993ml/QueryBot5000)

* Automatic Database Management System Tuning Through Large-scale Machine Learning. SIGMOD 2017, 1009-1024.&nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3035918.3064029)&nbsp;[Code](https://github.com/cmu-db/ottertune)

* Learning Memory Access Patterns. ICML 2018: 1924-1933.&nbsp;[Paper](http://proceedings.mlr.press/v80/hashemi18a.html)

* Self-Driving Database Management Systems. CIDR 2017. &nbsp;[Paper](http://cidrdb.org/cidr2017/papers/p42-pavlo-cidr17.pdf)

* Database Learning: Toward a Database that Becomes Smarter Every Time. SIGMOD 2017, 587-602. &nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3035918.3064013) &nbsp;[Project](http://verdictdb.org/)


## <a name='scale-ml'> Large Scale Machine Learning

### System based on Spark

* A Cost-based Optimizer for Gradient Descent Optimization. SIGMOD 2017, 977-992.&nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3035918.3064042)

* KeystoneML: Optimizing pipelines for large-scale advanced analytics. ICDE 2017: 535–546.&nbsp;[Paper](https://ieeexplore.ieee.org/document/7930005)&nbsp;[Project](http://keystone-ml.org/)

* SystemML: Declarative Machine Learning on Spark. PVLDB 9(13): 1425-1436, 2016.&nbsp;[Paper](http://www.vldb.org/pvldb/vol9/p1425-boehm.pdf)&nbsp;[Project](https://systemml.apache.org/)

* MLbase: A Distributed Machine-learning System. CIDR 2013.&nbsp;[Paper](http://cidrdb.org/cidr2013/Papers/CIDR13_Paper118.pdf) &nbsp;[Project](http://mlbase.org/)

### Specific Algorithms

* DimBoost: Boosting Gradient Boosting Decision Tree to Higher Dimensions. SIGMOD 2018, 1363-1376.&nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3183713.3196892)

* Scalable Training of Hierarchical Topic Models. PVLDB 11(7), 826-839, 2018. &nbsp;[Paper](http://www.vldb.org/pvldb/vol11/p826-chen.pdf)

* LDA*: A Robust and Large-scale Topic Modeling System. PVLDB 10(11), 1406-1417, 2017. &nbsp;[Paper](http://www.vldb.org/pvldb/vol10/p1406-yu.pdf)

* Scalable Kernel Density Classification via Threshold-Based Pruning. SIGMOD 2017, 945-959.&nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3035918.3064035)

* WarpLDA: a Cache Efficient O(1) Algorithm for Latent Dirichlet Allocation. PVLDB 9(10): 744-755, 2016. &nbsp;[Paper](http://www.vldb.org/pvldb/vol9/p744-chen.pdf)

### Linear Algebra

* Towards Linear Algebra over Normalized Data. PVLDB 10(11): 1214-1225, 2017.&nbsp;[Paper](http://www.vldb.org/pvldb/vol10/p1214-chen.pdf)

* Scalable Linear Algebra on a Relational Database System. ICDE 2017: 523-534. .&nbsp;[Paper](https://ieeexplore.ieee.org/document/7930004)

* Compressed Linear Algebra for Large-Scale Machine Learning. PVLDB 9(12): 960-971, 2016.&nbsp;[Paper](http://www.vldb.org/pvldb/vol9/p960-elgohary.pdf)

* Learning Generalized Linear Models Over Normalized Data. SIGMOD 2015: 1969-1984. &nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=2723372.2723713)

* Exploiting Matrix Dependency for Efficient Distributed Matrix Computation. SIGMOD 2015:93-105.&nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=2723372.2723712)

### Relational DBMS

* The BUDS Language for Distributed Bayesian Machine Learning. SIGMOD 2017, 961-976.&nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3035918.3035937)

* Are Key-Foreign Key Joins Safe to Avoid when Learning High-Capacity Classifiers? PVLDB 11(3), 366-379, 2017.&nbsp;[Paper](http://www.vldb.org/pvldb/vol11/p366-shah.pdf)

* Learning Linear Regression Models over Factorized Joins. SIGMOD 2016, 3-18.&nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=2882903.2882939)

* The MADlib Analytics Library or MAD Skills, the SQL. PVLDB 5(12): 1700-1711, 2012.&nbsp;[Paper](http://www.vldb.org/pvldb/2/vldb09-219.pdf)

### Misc (to be categorized later)

* Sketching Linear Classifiers over Data Streams. SIGMOD 2018: 757-772.&nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3183713.3196930) &nbsp;[Code](https://github.com/stanford-futuredata/wmsketch)
  
* SketchML: Accelerating Distributed Machine Learning with Data Sketches. SIGMOD 2018, 1269-1284.&nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3183713.3196894)

* Helix: Holistic Optimization for Accelerating Iterative Machine Learning. PVLDB 12(4), 446-460, 2018.&nbsp;[Paper](http://www.vldb.org/pvldb/vol12/p446-xin.pdf)

* ColumnML: Column-Store Machine Learning with On-The-Fly Data Transformation. PVLDB 12(4), 348-361, 2018.&nbsp;[Paper](http://www.vldb.org/pvldb/vol12/p348-kara.pdf)
