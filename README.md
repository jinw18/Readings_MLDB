# Readings_MLDB
Paper list about adopting machine learning techniques into data management tasks. Mainly consider ones published in top data management venues.

## <a name='ml-in-db'> Machine Learning in Database System
* The Case for Learned Index Structures. SIGMOD 2018: 489-504. &nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3183713.3196909)
  
* Query-based Workload Forecasting for Self-Driving Database Management Systems. SIGMOD 2018, 631-645. &nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3183713.3196908)&nbsp;[Code](https://github.com/malin1993ml/QueryBot5000)

* Automatic Database Management System Tuning Through Large-scale Machine Learning. SIGMOD 2017, 1009-1024.&nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3035918.3064029)&nbsp;[Code](https://github.com/cmu-db/ottertune)

* Self-Driving Database Management Systems. CIDR 2017. &nbsp;[Paper](http://cidrdb.org/cidr2017/papers/p42-pavlo-cidr17.pdf)

* Database Learning: Toward a Database that Becomes Smarter Every Time. SIGMOD 2017, 587-602. &nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3035918.3064013) &nbsp;[Project](http://verdictdb.org/)


## <a name='scale-ml'> Scalable Machine Learning Algorithms
* Sketching Linear Classifiers over Data Streams. SIGMOD 2018: 757-772.  &nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3183713.3196930)&nbsp;[Code](https://github.com/stanford-futuredata/wmsketch)
  
* SketchML: Accelerating Distributed Machine Learning with Data Sketches. SIGMOD 2018, 1269-1284.&nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3183713.3196894)

* DimBoost: Boosting Gradient Boosting Decision Tree to Higher Dimensions. SIGMOD 2018, 1363-1376.&nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3183713.3196892)

* Scalable Training of Hierarchical Topic Models. PVLDB 11(7), 826-839 (2018)&nbsp;[Paper](http://www.vldb.org/pvldb/vol11/p826-chen.pdf)

* Scalable Kernel Density Classification via Threshold-Based Pruning. SIGMOD 2017, 945-959.&nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3035918.3064035)

* The BUDS Language for Distributed Bayesian Machine Learning. SIGMOD 2017, 961-976.&nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3035918.3035937)

* A Cost-based Optimizer for Gradient Descent Optimization. SIGMOD 2017, 977-992.&nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3035918.3064042)

* LDA*: A Robust and Large-scale Topic Modeling System. PVLDB 10(11), 1406-1417 (2017)&nbsp;[Paper](http://www.vldb.org/pvldb/vol10/p1406-yu.pdf)

* Are Key-Foreign Key Joins Safe to Avoid when Learning High-Capacity Classifiers? PVLDB 11(3), 366-379 (2017)&nbsp;[Paper](http://www.vldb.org/pvldb/vol11/p366-shah.pdf)

* Learning Linear Regression Models over Factorized Joins. SIGMOD 2016, 3-18.&nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=2882903.2882939)

  
## <a name='ml-sys'> Machine Learning Platforms and Benchmarking
* MISTIQUE: A System to Store and Query Model Intermediates for Model Diagnosis. SIGMOD 2018, 1285-1300.&nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3183713.3196934)
  
* MLBench: Benchmarking Machine Learning Services Against Human Experts. PVLDB 11(10), 1220-1232 (2018)&nbsp;[Paper](http://www.vldb.org/pvldb/vol11/p1220-liu.pdf)

* Ease.ml: Towards Multi-tenant Resource Sharing for Machine Learning Workloads. PVLDB 11(5), 607-620 (2018)&nbsp;[Paper](http://www.vldb.org/pvldb/vol11/p607-li.pdf)

* Snorkel: Rapid Training Data Creation with Weak Supervision. PVLDB 11(3), 269-282 (2017)&nbsp;[Paper](http://www.vldb.org/pvldb/vol11/p269-ratner.pdf)

## <a name='ml-app'> Specific Applications
  
* Schema Independent Relational Learning.SIGMOD 2017, 929-944. &nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3035918.3035923)

* Data Synthesis based on Generative Adversarial Networks. PVLDB 11(10), 1071-1083 (2018)&nbsp;[Paper](http://www.vldb.org/pvldb/vol11/p1071-park.pdf)

* Model-free Control for Distributed Stream Data Processing using Deep Reinforcement Learning. PVLDB 11(6), 705-718 (2018)&nbsp;[Paper](http://www.vldb.org/pvldb/vol11/p705-li.pdf)  
 
Note: We also include papers published in data management venues regarding to particular tasks, such as knowledge discovery and information extraction here, since they are closely related to machine learning issues. You can find more related papers in more related venues like KDD and WWW.  

### <a name='kbc'> Knowledge Base
* Fonduer: Knowledge Base Construction from Richly Formatted Data. SIGMOD 2018, 1301-1316.&nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3183713.3183729)&nbsp;[Code](https://github.com/HazyResearch/fonduer)
  
* Maverick: Discovering Exceptional Facts from Knowledge Graphs. SIGMOD 2018, 1317-1332. &nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3183713.3183730)

* Query-Driven On-The-Fly Knowledge Base Construction. PVLDB 11(1), 66-79 (2017)&nbsp;[Paper](http://www.vldb.org/pvldb/vol11/p66-nguyen.pdf)

* Ontological Pathfinding. SIGMOD 2016, 835-846.&nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=2882903.2882954)

* Knowledge Exploration using Tables on the Web. PVLDB 10(3), 193-204 (2016)&nbsp;[Paper](http://www.vldb.org/pvldb/vol10/p193-chirigati.pdf)

### <a name='info-ext'> Information Extraction
* CERES: Distantly Supervised Relation Extraction from the Semi-Structured Web. PVLDB 11(10), 1084-1096 (2018)&nbsp;[Paper](http://www.vldb.org/pvldb/vol11/p1084-lockard.pdf)
  
* Holistic Query Evaluation over Information Extraction Pipelines. PVLDB 11(2), 217-229 (2017)&nbsp;[Paper](http://www.vldb.org/pvldb/vol11/p217-ioannou.pdf)

* Extracting Databases from Dark Data with DeepDive. SIGMOD 2016, 847-859.&nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=2882903.2904442)

* Potential and Pitfalls of Domain-Specific Information Extraction at Web Scale. SIGMOD 2016, 759-771.&nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=2882903.2903736)
  
### <a name='entity'> Entity Matching and Resolution
* Deep Learning for Entity Matching: A Design Space Exploration. SIGMOD 2018, 19-34. &nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3183713.3196926) &nbsp;[Project](https://sites.google.com/site/anhaidgroup/projects/magellan)

* Fine-grained Concept Linking using Neural Networks in Healthcare. SIGMOD 2018, 51-66. &nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3183713.3196907)&nbsp;[Project](http://www.comp.nus.edu.sg/~dbsystem/gemini/index.html)

* Robust Entity Resolution using Random Graphs. SIGMOD Conference 2018, 3-18.&nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3183713.3183755)

* Waldo: An Adaptive Human Interface for Crowd Entity Resolution. SIGMOD Conference 2017, 1133-1148. &nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=3035918.3035931)

* In Search of an Entity Resolution OASIS: Optimal Asymptotic Sequential Importance Sampling. PVLDB 10(11), 1322-1333 (2017)&nbsp;[Paper](http://www.vldb.org/pvldb/vol10/p1322-rubinstein.pdf)

* Generating Preview Tables for Entity Graphs. SIGMOD 2016, 1797-1811. &nbsp;[Paper](https://dl.acm.org/citation.cfm?doid=2882903.2915221)

* Comparative Analysis of Approximate Blocking Techniques for Entity Resolution. PVLDB 9(9), 684-695 (2016)&nbsp;[Paper](http://www.vldb.org/pvldb/vol9/p684-papadakis.pdf)

* Online Entity Resolution Using an Oracle. PVLDB 9(5), 384-395 (2016)&nbsp;[Paper](http://www.vldb.org/pvldb/vol9/p384-firmani.pdf)

* BLAST: a Loosely Schema-aware Meta-blocking Approach for Entity Resolution. PVLDB 9(12), 1173-1184 (2016)&nbsp;[Paper](http://www.vldb.org/pvldb/vol9/p1173-simonini.pdf)

* Magellan: Toward Building Entity Matching Management Systems. PVLDB 9(12), 1197-1208 (2016). &nbsp;[Paper](http://www.vldb.org/pvldb/vol9/p1197-pkonda.pdf)

* QuERy: A Framework for Integrating Entity Resolution with Query Processing. PVLDB 9(3): 120-131 (2015) &nbsp;[Paper](http://www.vldb.org/pvldb/vol9/p120-altwaijry.pdf)
