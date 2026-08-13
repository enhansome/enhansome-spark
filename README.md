[<img src="https://cdn.rawgit.com/awesome-spark/awesome-spark/f78a16db/spark-logo-trademark.svg" align="right">](https://spark.apache.org/)

# Awesome Spark with stars

A curated list of awesome [Apache Spark](https://spark.apache.org/) packages and resources.

*Apache Spark is an open-source cluster-computing framework. Originally developed at the [University of California](https://www.universityofcalifornia.edu/), [Berkeley's AMPLab](https://amplab.cs.berkeley.edu/), the Spark codebase was later donated to the [Apache Software Foundation](https://www.apache.org/), which has maintained it since. Spark provides an interface for programming entire clusters with implicit data parallelism and fault-tolerance*  ([Wikipedia 2017](#wikipedia-2017)).

Users of Apache Spark may choose between different the Python, R, Scala and Java programming languages to interface with the Apache Spark APIs.

## Packages

### Language Bindings

* [.NET for Apache Spark](https://github.com/dotnet/spark) ⭐ 2,098 | 🐛 200 | 🌐 C# | 📅 2026-07-31 <img src="https://img.shields.io/github/last-commit/dotnet/spark.svg"> - .NET bindings.
* [sparklyr](https://github.com/rstudio/sparklyr) ⭐ 972 | 🐛 355 | 🌐 R | 📅 2026-07-02 <img src="https://img.shields.io/github/last-commit/rstudio/sparklyr.svg"> - An alternative R backend, using [`dplyr`](https://github.com/hadley/dplyr) ⭐ 5,057 | 🐛 91 | 🌐 R | 📅 2026-06-02.
* [Kotlin for Apache Spark](https://github.com/Kotlin/kotlin-spark-api) ⭐ 481 | 🐛 19 | 🌐 Kotlin | 📅 2026-06-18 <img src="https://img.shields.io/github/last-commit/Kotlin/kotlin-spark-api.svg"> - Kotlin API bindings and extensions.
* [sparkle](https://github.com/tweag/sparkle) ⭐ 449 | 🐛 16 | 🌐 Haskell | 📅 2025-07-30 <img src="https://img.shields.io/github/last-commit/tweag/sparkle.svg"> - Haskell on Apache Spark.
* [spark-connect-go](https://github.com/apache/spark-connect-go) ⭐ 251 | 🐛 25 | 🌐 Go | 📅 2026-05-15 <img src="https://img.shields.io/github/last-commit/apache/spark-connect-go.svg"> - Golang bindings.
* [spark-connect-rs](https://github.com/sjrusso8/spark-connect-rs) ⭐ 116 | 🐛 11 | 🌐 Rust | 📅 2025-06-10 <img src="https://img.shields.io/github/last-commit/sjrusso8/spark-connect-rs.svg"> - Rust bindings.
* [spark-connect-csharp](https://github.com/mdrakiburrahman/spark-connect-csharp) ⭐ 2 | 🐛 1 | 🌐 C# | 📅 2024-04-23 <img src="https://img.shields.io/github/last-commit/mdrakiburrahman/spark-connect-csharp.svg"> - C# bindings.

### Notebooks and IDEs

* [almond](https://almond.sh/) <img src="https://img.shields.io/github/last-commit/almond-sh/almond.svg"> - A scala kernel for [Jupyter](https://jupyter.org/).
* [Apache Zeppelin](https://zeppelin.incubator.apache.org/) <img src="https://img.shields.io/github/last-commit/apache/zeppelin.svg"> - Web-based notebook that enables interactive data analytics with plugable backends, integrated plotting, and extensive Spark support out-of-the-box.
* [Polynote](https://polynote.org/)  <img src="https://img.shields.io/github/last-commit/polynote/polynote.svg"> - Polynote: an IDE-inspired polyglot notebook. It supports mixing multiple languages in one notebook, and sharing data between them seamlessly. It encourages reproducible notebooks with its immutable data model. Originating from [Netflix](https://medium.com/netflix-techblog/open-sourcing-polynote-an-ide-inspired-polyglot-notebook-7f929d3f447).
* [sparkmagic](https://github.com/jupyter-incubator/sparkmagic) ⭐ 1,366 | 🐛 167 | 🌐 Python | 📅 2025-09-09 <img src="https://img.shields.io/github/last-commit/jupyter-incubator/sparkmagic.svg"> - [Jupyter](https://jupyter.org/) magics and kernels for working with remote Spark clusters, for interactively working with remote Spark clusters through [Livy](https://github.com/cloudera/livy) ⭐ 1,007 | 🐛 24 | 🌐 Scala | 📅 2022-10-05, in Jupyter notebooks.

### General Purpose Libraries

* [spark-daria](https://github.com/mrpowers-io/spark-daria) ⭐ 767 | 🐛 18 | 🌐 Scala | 📅 2026-06-22 <img src="https://img.shields.io/github/last-commit/mrpowers-io/spark-daria.svg"> - A Scala library with essential Spark functions and extensions to make you more productive.
* [quinn](https://github.com/mrpowers-io/quinn) ⭐ 687 | 🐛 25 | 🌐 Python | 📅 2026-06-09 <img src="https://img.shields.io/github/last-commit/mrpowers-io/quinn.svg"> - A native PySpark implementation of spark-daria.
* [Joblib Apache Spark Backend](https://github.com/joblib/joblib-spark) ⭐ 249 | 🐛 20 | 🌐 Python | 📅 2026-03-24 <img src="https://img.shields.io/github/last-commit/joblib/joblib-spark.svg"> - [`joblib`](https://github.com/joblib/joblib) ⭐ 4,382 | 🐛 438 | 🌐 Python | 📅 2026-08-05 backend for running tasks on Spark clusters.
* [Apache DataFu](https://github.com/apache/datafu/tree/master/datafu-spark) ⭐ 124 | 🐛 3 | 🌐 Java | 📅 2026-07-09 <img src="https://img.shields.io/github/last-commit/apache/datafu.svg"> - A library of general purpose functions and UDF's.
* [itachi](https://github.com/yaooqinn/itachi) ⭐ 63 | 🐛 1 | 🌐 Scala | 📅 2023-09-04 <img src="https://img.shields.io/github/last-commit/yaooqinn/itachi.svg"> - A library that brings useful functions from modern database management systems to Apache Spark.

### SQL Data Sources

SparkSQL has [serveral built-in Data Sources](https://spark.apache.org/docs/latest/sql-data-sources-load-save-functions.html#manually-specifying-options) for files. These include `csv`, `json`, `parquet`, `orc`, and `avro`. It also supports JDBC databases as well as Apache Hive. Additional data sources can be added by including the packages listed below, or writing your own.

* [Spark Cassandra Connector](https://github.com/datastax/spark-cassandra-connector) ⭐ 1,951 | 🐛 28 | 🌐 Scala | 📅 2025-04-29 <img src="https://img.shields.io/github/last-commit/datastax/spark-cassandra-connector.svg"> - Cassandra support including data source and API and support for arbitrary queries.
* [Mongo-Spark](https://github.com/mongodb/mongo-spark) ⭐ 731 | 🐛 3 | 🌐 Java | 📅 2026-08-13 <img src="https://img.shields.io/github/last-commit/mongodb/mongo-spark.svg"> - Official MongoDB connector.
* [Spark XML](https://github.com/databricks/spark-xml) ⚠️ Archived <img src="https://img.shields.io/github/last-commit/databricks/spark-xml.svg"> - XML parser and writer.

### Storage

* [Apache Iceberg](https://github.com/apache/iceberg) ⭐ 9,137 | 🐛 897 | 🌐 Java | 📅 2026-08-13 <img src="https://img.shields.io/github/last-commit/apache/iceberg.svg"> - Upserts, Deletes And Incremental Processing on Big Data..
* [Delta Lake](https://github.com/delta-io/delta) ⭐ 8,938 | 🐛 923 | 🌐 Scala | 📅 2026-08-13 <img src="https://img.shields.io/github/last-commit/delta-io/delta.svg"> - Storage layer with ACID transactions.
* [Apache Hudi](https://github.com/apache/hudi) ⭐ 6,213 | 🐛 2,958 | 🌐 Java | 📅 2026-08-13 <img src="https://img.shields.io/github/last-commit/apache/hudi.svg"> - Upserts, Deletes And Incremental Processing on Big Data..
* [lakeFS](https://docs.lakefs.io/integrations/spark.html) <img src="https://img.shields.io/github/last-commit/treeverse/lakefs.svg"> - Integration with the lakeFS atomic versioned storage layer.

### Bioinformatics

* [Hail](https://github.com/hail-is/hail) ⭐ 1,069 | 🐛 359 | 🌐 Python | 📅 2026-08-13 <img src="https://img.shields.io/github/last-commit/hail-is/hail.svg"> - Genetic analysis framework.
* [ADAM](https://github.com/bigdatagenomics/adam) ⭐ 1,056 | 🐛 43 | 🌐 Scala | 📅 2026-03-17 <img src="https://img.shields.io/github/last-commit/bigdatagenomics/adam.svg"> - Set of tools designed to analyse genomics data.

### GIS

* [Apache Sedona](https://github.com/apache/incubator-sedona) ⭐ 2,378 | 🐛 97 | 🌐 Java | 📅 2026-08-12 <img src="https://img.shields.io/github/last-commit/apache/incubator-sedona.svg"> - Cluster computing system for processing large-scale spatial data.

### Graph Processing

* [GraphFrames](https://github.com/graphframes/graphframes) ⭐ 1,201 | 🐛 47 | 🌐 Scala | 📅 2026-08-12 <img src="https://img.shields.io/github/last-commit/graphframes/graphframes.svg"> - Data frame based graph API.
* [neo4j-spark-connector](https://github.com/neo4j-contrib/neo4j-spark-connector) ⭐ 324 | 🐛 7 | 🌐 Scala | 📅 2026-08-13 <img src="https://img.shields.io/github/last-commit/neo4j-contrib/neo4j-spark-connector.svg"> - Bolt protocol based, Neo4j Connector with RDD, DataFrame and GraphX / GraphFrames support.

### Machine Learning Extension

* [ModelDB](https://mitdbg.github.io/modeldb) <img src="https://img.shields.io/github/last-commit/mitdbg/modeldb.svg"> - A system to manage machine learning models for `spark.ml` and [`scikit-learn`](https://github.com/scikit-learn/scikit-learn) ⭐ 66,973 | 🐛 2,124 | 🌐 Python | 📅 2026-08-13 <img src="https://img.shields.io/github/last-commit/scikit-learn/scikit-learn.svg">.
* [BigDL](https://github.com/intel-analytics/BigDL) ⚠️ Archived <img src="https://img.shields.io/github/last-commit/intel-analytics/BigDL.svg"> - Distributed Deep Learning library.
* [Microsoft ML for Apache Spark](https://github.com/Azure/mmlspark) ⭐ 5,236 | 🐛 203 | 🌐 Scala | 📅 2026-08-13 <img src="https://img.shields.io/github/last-commit/Azure/mmlspark.svg"> - A distributed ml library with support for LightGBM, Vowpal Wabbit, OpenCV, Deep Learning, Cognitive Services, and Model Deployment.
* [MLeap](https://github.com/combust/mleap) ⭐ 1,540 | 🐛 110 | 🌐 Scala | 📅 2026-07-21 <img src="https://img.shields.io/github/last-commit/combust/mleap.svg"> - Execution engine and serialization format which supports deployment of `o.a.s.ml` models without dependency on `SparkSession`.
* [Sparkling Water](https://github.com/h2oai/sparkling-water) ⭐ 979 | 🐛 43 | 🌐 Scala | 📅 2025-11-05 <img src="https://img.shields.io/github/last-commit/h2oai/sparkling-water.svg"> -  [H2O](http://www.h2o.ai/) interoperability layer.
* [JPMML-Spark](https://github.com/jpmml/jpmml-spark) ⭐ 99 | 🐛 1 | 🌐 Scala | 📅 2026-02-08 <img src="https://img.shields.io/github/last-commit/jpmml/jpmml-spark.svg"> - PMML transformer library for Spark ML.
* [Apache SystemML](https://systemml.apache.org/) <img src="https://img.shields.io/github/last-commit/apache/systemml.svg"> - Declarative machine learning framework on top of Spark.
* [Mahout Spark Bindings](https://mahout.apache.org/users/sparkbindings/home.html) \[status unknown] - linear algebra DSL and optimizer with R-like syntax.
* [KeystoneML](http://keystone-ml.org/) - Type safe machine learning pipelines with RDDs.
* [MLflow](https://mlflow.org/docs/latest/python_api/mlflow.spark.html#module-mlflow.spark) <img src="https://img.shields.io/github/last-commit/mlflow/mlflow.svg"> - Machine learning orchestration platform.

### Middleware

* [spark-jobserver](https://github.com/spark-jobserver/spark-jobserver) ⭐ 2,836 | 🐛 111 | 🌐 Scala | 📅 2026-03-03 <img src="https://img.shields.io/github/last-commit/spark-jobserver/spark-jobserver.svg"> - Simple Spark as a Service which supports objects sharing using so called named objects. JVM only.
* [Apache Kyuubi](https://github.com/apache/kyuubi) ⭐ 2,360 | 🐛 515 | 🌐 Scala | 📅 2026-08-13 <img src="https://img.shields.io/github/last-commit/apache/kyuubi.svg"> - A distributed multi-tenant JDBC server for large-scale data processing and analytics, built on top of Apache Spark.
* [Livy](https://github.com/apache/incubator-livy) ⭐ 958 | 🐛 46 | 🌐 Scala | 📅 2026-08-06 <img src="https://img.shields.io/github/last-commit/apache/incubator-livy.svg"> - REST server with extensive language support (Python, R, Scala), ability to maintain interactive sessions and object sharing.
* [Apache Toree](https://github.com/apache/incubator-toree) ⭐ 750 | 🐛 20 | 🌐 Scala | 📅 2026-08-07 <img src="https://img.shields.io/github/last-commit/apache/incubator-toree.svg"> - IPython protocol based middleware for interactive applications.

### Monitoring

* [Data Mechanics Delight](https://github.com/datamechanics/delight) ⚠️ Archived <img src="https://img.shields.io/github/last-commit/datamechanics/delight.svg"> - Cross-platform monitoring tool (Spark UI / Spark History Server replacement).

### Utilities

* [Optimus](https://github.com/ironmussa/Optimus/) ⭐ 1,537 | 🐛 30 | 🌐 Python | 📅 2024-12-02 <img src="https://img.shields.io/github/last-commit/ironmussa/Optimus.svg"> - Data Cleansing and Exploration utilities with the goal of simplifying data cleaning.
* [Flintrock](https://github.com/nchammas/flintrock) ⭐ 650 | 🐛 40 | 🌐 Python | 📅 2024-12-13 <img src="https://img.shields.io/github/last-commit/nchammas/flintrock.svg"> - A command-line tool for launching Spark clusters on EC2.
* [sparkly](https://github.com/Tubular/sparkly) ⭐ 62 | 🐛 6 | 🌐 Python | 📅 2025-12-04 <img src="https://img.shields.io/github/last-commit/Tubular/sparkly.svg"> - Helpers & syntactic sugar for PySpark.

### Natural Language Processing

* [spark-nlp](https://github.com/JohnSnowLabs/spark-nlp) ⭐ 4,155 | 🐛 29 | 🌐 Scala | 📅 2026-08-13 <img src="https://img.shields.io/github/last-commit/JohnSnowLabs/spark-nlp.svg"> - Natural language processing library built on top of Apache Spark ML.

### Streaming

* [Apache Bahir](https://bahir.apache.org/) <img src="https://img.shields.io/github/last-commit/apache/bahir.svg"> - Collection of the streaming connectors excluded from Spark 2.0 (Akka, MQTT, Twitter. ZeroMQ).

### Interfaces

* [Apache Beam](https://beam.apache.org/) <img src="https://img.shields.io/github/last-commit/apache/beam.svg"> - Unified data processing engine supporting both batch and streaming applications. Apache Spark is one of the supported execution environments.
* [Koalas](https://github.com/databricks/koalas) ⭐ 3,372 | 🐛 108 | 🌐 Python | 📅 2024-03-20 <img src="https://img.shields.io/github/last-commit/databricks/koalas.svg"> - Pandas DataFrame API on top of Apache Spark.

### Data quality

* [deequ](https://github.com/awslabs/deequ) ⭐ 3,638 | 🐛 70 | 🌐 Scala | 📅 2026-07-21 <img src="https://img.shields.io/github/last-commit/awslabs/deequ.svg"> - Deequ is a library built on top of Apache Spark for defining "unit tests for data", which measure data quality in large datasets.
* [python-deequ](https://github.com/awslabs/python-deequ) ⭐ 826 | 🐛 101 | 🌐 Jupyter Notebook | 📅 2026-07-21 <img src="https://img.shields.io/github/last-commit/awslabs/python-deequ.svg"> - Python API for Deequ.

### Testing

* [spark-testing-base](https://github.com/holdenk/spark-testing-base) ⭐ 1,555 | 🐛 94 | 🌐 Scala | 📅 2026-08-07 <img src="https://img.shields.io/github/last-commit/holdenk/spark-testing-base.svg"> - Collection of base test classes.
* [chispa](https://github.com/MrPowers/chispa) ⭐ 774 | 🐛 37 | 🌐 Python | 📅 2026-08-09 <img src="https://img.shields.io/github/last-commit/MrPowers/chispa.svg"> - PySpark test helpers with beautiful error messages.
* [spark-fast-tests](https://github.com/mrpowers-io/spark-fast-tests) ⭐ 457 | 🐛 22 | 🌐 Scala | 📅 2026-04-02 <img src="https://img.shields.io/github/last-commit/mrpowers-io/spark-fast-tests.svg"> - A lightweight and fast testing framework.

### Web Archives

* [Archives Unleashed Toolkit](https://github.com/archivesunleashed/aut) ⭐ 158 | 🐛 5 | 🌐 Scala | 📅 2025-12-05 <img src="https://img.shields.io/github/last-commit/archivesunleashed/aut.svg"> -  Open-source toolkit for analyzing web archives.

### Workflow Management

* [Cromwell](https://github.com/broadinstitute/cromwell#spark-backend) ⭐ 1,080 | 🐛 813 | 🌐 Scala | 📅 2026-08-04 <img src="https://img.shields.io/github/last-commit/broadinstitute/cromwell.svg"> - Workflow management system with [Spark backend](https://github.com/broadinstitute/cromwell#spark-backend) ⭐ 1,080 | 🐛 813 | 🌐 Scala | 📅 2026-08-04.

## Resources

### Books

* [Advanced Analytics with Spark](http://shop.oreilly.com/product/0636920035091.do) - Useful collection of Spark processing patterns. Accompanying GitHub repository: [sryza/aas](https://github.com/sryza/aas) ⭐ 1,525 | 🐛 4 | 🌐 Scala | 📅 2024-09-25.
* [Spark in Action](https://www.manning.com/books/spark-in-action) - New book in the Manning's "in action" family with +400 pages. Starts gently, step-by-step and covers large number of topics. Free excerpt on how to [setup Eclipse for Spark application development](http://freecontent.manning.com/how-to-start-developing-spark-applications-in-eclipse/) and how to bootstrap a new application using the provided Maven Archetype. You can find the accompanying GitHub repo [here](https://github.com/spark-in-action/first-edition) ⭐ 270 | 🐛 4 | 🌐 Scala | 📅 2017-07-01.
* [Learning Spark, 2nd Edition](https://www.oreilly.com/library/view/learning-spark-2nd/9781492050032/) - Introduction to Spark API with Spark 3.0 covered. Good source of knowledge about basic concepts.
* [Mastering Apache Spark](https://jaceklaskowski.gitbooks.io/mastering-apache-spark/) - Interesting compilation of notes by [Jacek Laskowski](https://github.com/jaceklaskowski). Focused on different aspects of Spark internals.

### Papers

* [Large-Scale Intelligent Microservices](https://arxiv.org/pdf/2009.08044.pdf) - Microsoft paper that presents an Apache Spark-based micro-service orchestration framework that extends database operations to include web service primitives.
* [Resilient Distributed Datasets: A Fault-Tolerant Abstraction for In-Memory Cluster Computing](https://people.csail.mit.edu/matei/papers/2012/nsdi_spark.pdf) - Paper introducing a core distributed memory abstraction.
* [Spark SQL: Relational Data Processing in Spark](https://amplab.cs.berkeley.edu/wp-content/uploads/2015/03/SparkSQLSigmod2015.pdf) - Paper introducing relational underpinnings, code generation and Catalyst optimizer.
* [Structured Streaming: A Declarative API for Real-Time Applications in Apache Spark](https://cs.stanford.edu/~matei/papers/2018/sigmod_structured_streaming.pdf) - Structured Streaming is a new high-level streaming API, it is a declarative API based on automatically incrementalizing a static relational query.

### MOOCS

* [Data Science and Engineering with Apache Spark (edX XSeries)](https://www.edx.org/xseries/data-science-engineering-apache-spark) - Series of five courses ([Introduction to Apache Spark](https://www.edx.org/course/introduction-apache-spark-uc-berkeleyx-cs105x), [Distributed Machine Learning with Apache Spark](https://www.edx.org/course/distributed-machine-learning-apache-uc-berkeleyx-cs120x), [Big Data Analysis with Apache Spark](https://www.edx.org/course/big-data-analysis-apache-spark-uc-berkeleyx-cs110x), [Advanced Apache Spark for Data Science and Data Engineering](https://www.edx.org/course/advanced-apache-spark-data-science-data-uc-berkeleyx-cs115x), [Advanced Distributed Machine Learning with Apache Spark](https://www.edx.org/course/advanced-distributed-machine-learning-uc-berkeleyx-cs125x)) covering different aspects of software engineering and data science. Python oriented.
* [Big Data Analysis with Scala and Spark (Coursera)](https://www.coursera.org/learn/big-data-analysys) - Scala oriented introductory course. Part of [Functional Programming in Scala Specialization](https://www.coursera.org/specializations/scala).

### Workshops

* [AMP Camp](http://ampcamp.berkeley.edu) - Periodical training event organized by the [UC Berkeley AMPLab](https://amplab.cs.berkeley.edu/). A source of useful exercise and recorded workshops covering different tools from the [Berkeley Data Analytics Stack](https://amplab.cs.berkeley.edu/software/).

### Projects Using Spark

* [Oryx 2](https://github.com/OryxProject/oryx) ⚠️ Archived - [Lambda architecture](http://lambda-architecture.net/) platform built on Apache Spark and [Apache Kafka](http://kafka.apache.org/) with specialization for real-time large scale machine learning.
* [Photon ML](https://github.com/linkedin/photon-ml) ⭐ 797 | 🐛 27 | 🌐 Terra | 📅 2021-08-30 - A machine learning library supporting classical Generalized Mixed Model and Generalized Additive Mixed Effect Model.
* [Crossdata](https://github.com/Stratio/Crossdata) ⚠️ Archived - Data integration platform with extended DataSource API and multi-user environment.
* [PredictionIO](https://prediction.io/) - Machine Learning server for developers and data scientists to build and deploy predictive applications in a fraction of the time.

### Docker Images

* [jupyter/docker-stacks/pyspark-notebook](https://github.com/jupyter/docker-stacks/tree/master/pyspark-notebook) ⭐ 8,453 | 🐛 8 | 🌐 Python | 📅 2026-08-09 - PySpark with Jupyter Notebook and Mesos client.
* [sequenceiq/docker-spark](https://github.com/sequenceiq/docker-spark) ⭐ 757 | 🐛 27 | 🌐 Shell | 📅 2021-03-11 - Yarn images from [SequenceIQ](http://www.sequenceiq.com/).
* [apache/spark](https://hub.docker.com/r/apache/spark) - Apache Spark Official Docker images.
* [datamechanics/spark](https://hub.docker.com/r/datamechanics/spark) - An easy to setup Docker image for Apache Spark from [Data Mechanics](https://www.datamechanics.co/).

### Miscellaneous

* [Spark with Scala Gitter channel](https://gitter.im/spark-scala/Lobby) - "*A place to discuss and ask questions about using Scala for Spark programming*" started by [@deanwampler](https://github.com/deanwampler).
* [Apache Spark User List](http://apache-spark-user-list.1001560.n3.nabble.com/) and [Apache Spark Developers List](http://apache-spark-developers-list.1001551.n3.nabble.com/) - Mailing lists dedicated to usage questions and development topics respectively.

## References

<p id="wikipedia-2017">Wikipedia. 2017. “Apache Spark — Wikipedia, the Free Encyclopedia.” <a href="https://en.wikipedia.org/w/index.php?title=Apache_Spark&amp;oldid=781182753" class="uri">https://en.wikipedia.org/w/index.php?title=Apache_Spark&amp;oldid=781182753</a>.</p>

## License

<p xmlns:dct="http://purl.org/dc/terms/">
<a rel="license" href="http://creativecommons.org/publicdomain/mark/1.0/">
<img src="https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/publicdomain.svg"
     style="border-style: none;" alt="Public Domain Mark" />
</a>
<br />
This work (<span property="dct:title">Awesome Spark</span>, by <a href="https://github.com/awesome-spark/awesome-spark" rel="dct:creator">https://github.com/awesome-spark/awesome-spark</a>), identified by <a href="https://github.com/zero323" rel="dct:publisher"><span property="dct:title">Maciej Szymkiewicz</span></a>, is free of known copyright restrictions.
</p>

Apache Spark, Spark, Apache, and the Spark logo are <a href="https://www.apache.org/foundation/marks/">trademarks</a> of <a href="http://www.apache.org">The Apache Software Foundation</a>. This compilation is not endorsed by The Apache Software Foundation.

Inspired by [sindresorhus/awesome](https://github.com/sindresorhus/awesome) ⭐ 495,288 | 🐛 100 | 📅 2026-06-30.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-13._
