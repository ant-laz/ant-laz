<!--
**ant-laz/ant-laz** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->

### :wave: Hi, I'm Anthony !

I am a software engineer working in the data space. 

Here are some things I do : 

#### 1. Build tools for other software engineers

##### Templated Apache Spark data pipelines

For software engineers using `Apache Spark` on `Google Cloud Dataproc`, a common problem faced is to create a data pipeline to move data between `Google Cloud BigQuery` and `Google Cloud Spanner`. I solved this problem in a generic way by using `Scala` to build a `templated data pipeline` called [BigQuery to Spanner using Apache Spark in Scala](https://github.com/ant-laz/spark-bigquery-spanner). Software engineers can use my template instead of writing pipeline code themselves. Software engineers simply have to provide some parameters to the template, e.g. the input BigQuery table & the output Spanner table. 

##### CLI tools for Apache Airflow

For software engineers using `Apache Airflow` on `Google Cloud Composer`, a common problem faced is to understand the difference between 2 Google Cloud Composer environment. For example when debugging why the same Airflow DAG works in a DEV enrivonrment, but not a PROD environment. I solved this problem by using `Python` to build a `CLI tool` called [cloudcomposerdiff](https://github.com/GoogleCloudPlatform/composer-utilities/tree/main/cloudcomposerdiff) which does a diff on 2 evironments. My solution saves software engineers the time & hassle of having to manually compare lots of different attributes across 2 environments. 

#### 2. Teach other software engineers 

##### How to build streaming data pipelines

Check out this YouTube video of my conference [workshop](https://youtu.be/4lwspjbJg7I?feature=shared) on building a streaming data pipeline using Apache Beam. The code for the conference workshop can be found [here](https://github.com/ant-laz/streamingworkshop) and a cool viz tool for the pipeline output can be found [here](https://github.com/ant-laz/streamingworkshopviz) . 

##### How to build batch data pipelines

Check out my [tutorial](https://github.com/ant-laz/batchworkshop-python) on building a batch data pipeline using Apache Beam.

##### How to write performant SQL

See my [codelab](https://www.cloudskillsboost.google/catalog_lab/30937) on optimising SQL query performance in BigQuery.

See my [codelab](https://www.cloudskillsboost.google/catalog_lab/31049) on optimising the cost of data tables in BigQuery.









